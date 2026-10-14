# CareFlow: Clinical Pathway Process Mining - Introduction & Scope

## Introduction
CareFlow is a data analytics project that looks at hospital activity logs. The main idea is to understand how clinical activities are recorded over time, what sequences are followed, and where data quality issues exist. We are using an event-log style dataset containing case identifiers, activities, and timestamps.

This is not a medical diagnosis project. We are only analyzing the process recorded in the logs.

## Objectives for Week 1
- Inspect the event log file and understand its columns.
- Validate case IDs, activities, and timestamps.
- Find common activity sequences and transitions.
- Define meaningful KPIs for our dashboard.
- Plan the dashboard layout and what questions it should answer.
- Document limitations and data quality observations.

## What is Included in Scope
- Dataset inspection and validation
- Process discovery (activities, transitions, variants)
- KPI definition for cases, events, and activities
- Dashboard planning and documentation
- Data quality reporting

## What is NOT in Scope (as per guide)
- We will not assume Case ID = Patient ID without confirmation.
- We will not do clinical interpretation or give medical suggestions.
- We will not declare any activity as a bottleneck without proper evidence and time analysis.
- We will not claim operational improvement or cost reduction.
- We will not treat time gap between start times as waiting time directly.
- We will not share or expose any sensitive / personal data.

## Limitations We Noted
- Missing timestamps and missing end times are present.
- Case ID semantics need team confirmation.
- Timestamp order needs validation inside each case.
- Some cases have very few events, some have many - may need cleaning rules.
- Privacy - all analysis is on anonymized log data only.
