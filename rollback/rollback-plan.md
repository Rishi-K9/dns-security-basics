# DNS Configuration Rollback Plan

## Purpose
Document a rollback procedure for DNS resolver configuration changes.

## Configuration
- Component: Unbound DNS resolver
- Change: Example DNSSEC validation settings
- Environment: Educational project
- Deployment Status: Not deployed

## Rollback Procedure
1. Locate the modified configuration file.
2. Restore the previous configuration from a backup.
3. Validate the restored configuration.
4. Restart or reload the resolver if required.
5. Verify DNS resolution.
6. Document the results.

## Rollback Evidence
No live deployment or rollback was performed. This document provides a proposed rollback procedure.

## Outcome
A rollback procedure has been documented for educational purposes.
