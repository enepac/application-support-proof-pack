# Incident Report — L1/L2 Application / IT Support

## Summary
- Date: 2019-07-22
- Reported by: Operations Supervisor (Dispatch)
- Impacted users/team: Dispatch and Scheduling Team (6–8 users)
- Service/App/System: Transport Management System (Fleet Manager)
- Severity: Medium
- Status: Resolved

## What Happened
Dispatch staff reported that scheduled bus routes were missing from the Transport Management System after a routine schedule update, preventing drivers from receiving accurate route assignments and causing delays in morning operations.

## Environment
- Device/OS: Windows desktop PCs
- Network: On-site local network
- Account type/role: Dispatcher / Scheduler user accounts
- Tools used: Transport Management System (Fleet Manager), Microsoft Excel, system admin access

## Timeline
- T0: Dispatch supervisor reported missing routes after schedule update
- T+10m: Verified issue affected multiple dispatcher accounts
- T+25m: Confirmed schedule data not visible across user views
- T+45m: Identified issue related to schedule data import
- Resolution time: ~1 hour

## Troubleshooting
1. Verified dispatcher user accounts and permissions were unchanged
2. Logged in using an admin account to confirm issue was system-wide
3. Checked most recent schedule upload files used for route planning
4. Reviewed system logs related to data synchronization and imports
5. Identified errors during the schedule data import process

## Root Cause
A malformed schedule file caused the Transport Management System to fail during data import, preventing updated route data from synchronizing correctly to dispatcher user views.

## Fix / Resolution
- Corrected the schedule data file format
- Re-imported the validated schedule into the system
- Confirmed route visibility and accuracy across all dispatcher accounts
- Coordinated with dispatch to verify normal operations resumed

## Preventative Actions
- Implemented basic validation checks on schedule files before import
- Updated internal SOP to include post-import verification steps
- Advised dispatch team to report immediately if routes are missing after updates

## Notes for Tier 2 / Knowledge Base
If route data is missing after schedule updates, check data import logs and file format first before resetting user accounts or restarting services.
