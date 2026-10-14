# KPI Definitions for CareFlow Dashboard

This file defines what each KPI means and how we calculated the initial exploratory values. Final numbers may change after data cleaning.

**1. Total Events:** Total number of valid rows after removing empty activity rows. Current exploration: ~2222 records.

**2. Total Cases:** Number of unique case IDs after validation. Current exploration: ~328 distinct IDs.

**3. Unique Activities:** How many different activity names are present. Found 36 unique activities in initial scan.

**4. Unique Transitions:** Count of distinct (Activity A -> Activity B) pairs found when we order events by timestamp inside each case.

**5. Missing Timestamps:** Number of rows where timestamp field is empty or invalid.

**6. Missing Activity Names:** Rows where activity column is blank.

**7. Average Events per Case:** Total Valid Events / Total Distinct Cases.

**8. Median Elapsed Time:** Median difference between consecutive timestamps for same case. We calculate only when both timestamps are present and timestamp2 > timestamp1.

**9. Most Frequent Activity:** The activity name with maximum count.

**10. Most Frequent Transition:** The consecutive activity pair with highest occurrence.

**Note:** 
- 577 records have no end timestamp, this might be expected as per data source.
- All numbers here are from initial inspection, not final reporting.
