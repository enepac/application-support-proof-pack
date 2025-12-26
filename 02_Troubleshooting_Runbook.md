# Troubleshooting Runbook — Application / Operations Support (L1–L2)

## Purpose
This runbook provides a structured approach for diagnosing and resolving common application and system issues affecting daily operations, dispatching, and scheduling users.

It is designed for L1/L2 support to restore service quickly and determine when escalation is required.

---

## Scope
Applies to:
- Transport Management System (Fleet Manager)
- Scheduling and dispatch workflows
- User access and data visibility issues

---

## Common Issue Categories
1. User cannot see schedules or routes
2. Application login or access issues
3. Data inconsistencies after updates
4. Performance or synchronization delays

---

## Standard Troubleshooting Flow

### Step 1 — Confirm the Problem
- Identify who reported the issue
- Determine how many users are affected
- Ask:
  - When did it start?
  - What exactly is missing or not working?
  - Did anything change recently (updates, imports, schedule changes)?

If more than one user is affected, treat as a **system issue**, not a user issue.

---

### Step 2 — Verify User Account & Access
- Confirm the user account is active
- Check assigned role (dispatcher, scheduler, admin)
- Attempt login using:
  - The affected user account (if possible)
  - An admin account for comparison

If admin access shows the same issue, proceed to system checks.

---

### Step 3 — Check Recent Changes
- Review:
  - Recent schedule uploads
  - Data imports or file changes
  - Manual adjustments made by operations or planning teams

Look for:
- Incorrect file formats
- Missing required fields
- Partial or failed uploads

---

### Step 4 — Review System Logs / Indicators
- Check application logs related to:
  - Data synchronization
  - Import/export processes
  - Permission or validation errors

Document any error messages or timestamps.

---

### Step 5 — Apply Corrective Action
Based on findings:
- Correct data file issues
- Re-run data imports
- Refresh or reload application views
- Coordinate with users to validate restored functionality

Avoid unnecessary actions such as resetting accounts unless access is confirmed as the cause.

---

## Escalation Criteria (Tier 2)
Escalate when:
- Errors persist after data correction
- Logs indicate system-level failures
- Application services fail to respond
- Issue impacts safety, compliance, or large-scale operations

Include in escalation:
- What was reported
- Steps already taken
- Relevant logs or timestamps

---

## Documentation & Follow-up
After resolution:
- Record the incident in an incident report
- Update SOPs if a new failure pattern is identified
- Inform affected users of resolution and preventative steps

---

## Key Principle
Always diagnose **data and system behavior first** before assuming user error or access issues.
