# DNS Security Basics Report

## 1. Objective
To understand DNS resolution and identify basic DNS security risks.

## 2. DNS Resolution
DNS translates domain names into IP addresses. A DNS resolver obtains the required records from its cache or queries other DNS servers.

## 3. DNS Security Risks
- DNS spoofing: False DNS responses may redirect users.
- Cache poisoning: False records are inserted into a DNS cache.
- DNS denial of service: DNS services become unavailable due to excessive traffic.
- Misconfiguration: Incorrect DNS settings may cause security issues.

## 4. DNSSEC
DNSSEC uses digital signatures to help verify the authenticity and integrity of DNS data. It does not encrypt DNS queries.

## 5. Security Measures
- Use trusted DNS resolvers.
- Enable DNSSEC validation where supported.
- Update DNS software regularly.
- Monitor DNS configuration changes.
- Maintain a rollback plan.

## 6. Configuration
An example Unbound resolver configuration is included in `config/unbound.conf.example`. It is provided for educational purposes and has not been deployed or tested on a live server.

## 7. Rollback
A proposed rollback procedure is documented in `rollback/rollback-plan.md`. No live deployment or rollback was performed.

## 8. Conclusion
Understanding DNS resolution, spoofing, and DNSSEC helps identify common DNS security risks and appropriate preventive measures.

## 9. Interview Questions

### What is DNS?
DNS stands for Domain Name System. It translates domain names into IP addresses.

### What is DNS spoofing?
DNS spoofing involves false DNS information that may redirect users to an unintended destination.

### What is DNSSEC?
DNSSEC stands for Domain Name System Security Extensions. It uses digital signatures to help verify DNS data.
