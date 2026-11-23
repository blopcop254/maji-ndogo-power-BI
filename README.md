# Maji Ndogo Water: Power BI Project

<img src="Maji%20Ndogo%20Water%20logo.png" alt="Maji Ndogo Water logo" width="420">

A three-stage Power BI project built during the **ALX Data Analytics Program**. It follows the fictional country of Maji Ndogo from a national water survey, through to tracking where its water improvement funds went and whether the money made a difference.

## Project at a glance

| Stage | File | What it answers |
|---|---|---|
| Part 1 | `dashboards/maji_ndogo_part_1.pbix` | Who uses which water sources, and how long do people queue? |
| Part 2 | `dashboards/maji_ndogo_part_2_national_survey.pbix` | What does the national water survey show, province by province? |
| Final | `dashboards/maji_ndogo_final_funds_tracker.pbix` | Where is the improvement money going, and is it on budget? |

## What's inside each dashboard

### Part 1: Survey basics
- **National**: people served by water source type and by rural or urban location
- **Maji Ndogo**: shape map of the provinces
- **Queue time analysis**: time in queue by day of week, hour of day and population served

### Part 2: National water survey
- **National**: province map, water sources by type, rural vs urban split, share of each source type by town
- **Queues**: time in queue by province, day and hour, plus queue make-up (men, women, children)
- **Well contamination**: share of clean and polluted wells
- **Crime rate**: water-source-related incidents by type, day and hour
- **National Report**: budget and basic-access summary with a province slicer
- **Province pages** (Sokoto, Akatsi, Amanzi, Hawassa, Kilimani): budget by improvement type, cost per citizen and rural vs urban split, with navigation buttons

### Final: Tracking the water funds
- **Dashboard**: shape map of project completion, % of people with basic water access, people helped, sources still to improve, cumulative cost vs budget (KPI), cost by province and by improvement type, date and province slicers
- **Key influencers**: what drives the cost of a project
- **Vendor analysis**: average cost and completed projects per vendor, with filters for date, improvement type and rural/urban

## Key findings
<!-- Check each line against your own dashboard before publishing -->
- Rural projects cost about twice as much as urban ones
- Every province ended up over budget, with Sokoto the highest
- Some vendors only looked expensive because of where they worked. One vendor kept costs down by staying close to a single area

## Skills demonstrated
- **Data modelling**: relationships between tables, one-to-many joins, `RELATED`
- **DAX**: running totals, percentages and conditional budgets (`CALCULATE`, `FILTER`, `ALLEXCEPT`, `CONTAINSSTRING`)
- **Power Query**: cleaning data, changing data sources and refreshing a report with new data
- **Visuals**: shape maps, KPI, key influencers, slicers, drill-down pages with navigation buttons
- **Analysis**: separating what is driving cost from what is already budgeted for, and comparing vendors like for like

## Screenshots

![Final dashboard](Final%20dashboard.png)
![Vendor analysis](Vendor%20analysis.png)

## How to open
1. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free, Windows).
2. Download or clone this repo.
3. Open any `.pbix` file in the `dashboards` folder.

The data is already loaded inside each file, so there is nothing else to set up.

## Data
The data comes from the ALX Data Analytics Program's Maji Ndogo project. It is fictional and was provided for learning.

## Related work
- SQL analysis of the same database: [https://github.com/blopcop254/maji-ndogo]

## Author
**Dickens**, ALX Data Analytics Program, Kenya
- LinkedIn: [https://www.linkedin.com/in/dickens-oduor-9928453b2/]
