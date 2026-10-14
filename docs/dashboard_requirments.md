# Dashboard Requirements - CareFlow

## Purpose
To plan what our dashboard should show and how it will help different users to understand the clinical event log.

## Intended Users
- **Reviewers / Mentors:** Want a quick summary of cases and activities.
- **Process Analysts:** Want to see how activities are sequenced.
- **Hospital side viewers (aggregated):** Need overall patterns, not patient-level data.

## Key Questions the Dashboard Should Answer
1. Total how many cases and event records are there in the dataset?
2. Which activities are happening most frequently?
3. What are the common activity transitions (e.g., A -> B)?
4. Are there any missing values in Case ID, Activity, Timestamp?
5. How much time is there between two events in a case?
6. Can we filter data by activity or specific case?

## Data Fields We Considered
- case_id / Case ID
- activity / Activity Name
- timestamp / Start Time
- end_timestamp (if available, but many are missing - 577 records)

## Filters Planned
- Filter by Activity name
- Filter by Date range
- Filter by Authorized Case ID (only for validation)

## Current Limitations Noted
- Some timestamps are missing or not in proper order.
- Case ID meaning still needs to be confirmed with team - is it patient or episode?
- We should not assume waiting time directly from start times.
