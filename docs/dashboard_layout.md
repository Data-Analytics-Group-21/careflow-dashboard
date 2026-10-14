# Dashboard Layout Plan

**Project Title:** CareFlow - Clinical Pathway Process Mining Dashboard

**Theme Planned:** Dark theme #121212 background with light cards - to match Power BI style we discussed.

### Page Structure

**Top Section - Filters:**
Activity filter, Date filter, Case ID filter (for authorized testing only)

**Second Section - KPI Cards (Row 1):**
[Total Events] | [Total Cases] | [Unique Activities] | [Unique Transitions] | [Data Quality Flag]

**Middle Section - Charts:**

1. **Page 1 Idea - Activity Overview**
   - Chart 1: Activity Frequency (Horizontal Bar Chart) - To show which activities happen most.
   - Chart 2: Data Quality Summary (Table) - Missing values count.

2. **Page 2 Idea - Flow Analysis**
   - Chart 3: Activity Transitions (Horizontal Bar) - Most common A -> B pairs.
   - Chart 4: Elapsed Time (Bar chart with caveat note) - Time gap between events.

3. **Page 3 Idea - Pathway Patterns**
   - Chart 5: Variant / Pathway table - List of common activity sequences.
   - Chart 6: Case Details table - Sample case flow (anonymized).

### Visuals Choice Reason
- Bar charts for frequency because activity names are long.
- Table for pathway patterns because sequences are better read as text.
- KPI cards on top for quick overview.

This layout is for planning purpose only for Week 1.
