# Power BI Dashboard for Demographic and Mortality Statistics

This project involves the creation of a Power BI dashboard to analyze and visualize demographic and mortality statistics in Germany. The data is sourced from official datasets provided by the Statistisches Bundesamt (Federal Statistical Office) and Robert Koch Institute. The dashboard includes insights on population distribution, mortality rates, life expectancy, and more.

---

## Table of Contents

- [Power BI Dashboard for Demographic and Mortality Statistics](#power-bi-dashboard-for-demographic-and-mortality-statistics)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Project Goals](#project-goals)
  - [Data Sources](#data-sources)
  - [Data Processing](#data-processing)
  - [Features](#features)
  - [Technical Details](#technical-details)
  - [Usage Instructions](#usage-instructions)
  - [Key Findings](#key-findings)
  - [Acknowledgments](#acknowledgments)

---

## Introduction

This project was developed as part of a seminar in the Winter Semester 2023/24 at the Frankfurt University of Applied Sciences. The main objective was to use Power BI to process, analyze, and visualize complex datasets, focusing on demographic and mortality statistics. 

**Submitted by:** Anh Quoc Nguyen  
**Supervisor:** Dozent Andreas Macho  

---

## Project Goals

- Visualize population distribution across Germany by regions and age groups.
- Analyze mortality rates over time and by cause.
- Predict future trends in mortality based on historical data.
- Provide interactive and user-friendly data representations.

![Population map](/source/image/PopulationMap.png)
![Mortality](/source/image/Mortality.png)
![Illness](/source/image/Illness.png)

---

## Data Sources

The project utilizes multiple datasets, including:

- Migration data across federal states (Bundesländer) by nationality and gender.
- Mortality statistics by region, gender, and cause of death.
- Life expectancy tables.
- Exceptional mortality events (e.g., influenza).
- Official statistical reports from 2000 to 2024.

**Sources:**  
- [Statistisches Bundesamt](https://www-genesis.destatis.de)  
- [Robert Koch Institute](https://www.rki.de)

---

## Data Processing

- **Cleaning:** Duplicate removal and data normalization using Power Query.
- **Transformation:** Reshaping and aggregating datasets into analyzable formats.
- **Storage:** Processed data is stored in a structured directory for easy import into Power BI.
- **Modeling:** Relationships between datasets are established in Power BI’s data model view.

---

## Features

- **Interactive Dashboards:** Navigate between pages with slicers and filters.
- **Visualization Tools:** Bar charts, line graphs, and demographic distributions.
- **Custom Measures:** Calculations like mortality rates per population using DAX.
- **Projections:** Predictive analysis for future mortality trends.

---

## Technical Details

- **Tools Used:** Power BI, Power Query, Excel.
- **Programming:** DAX for measures and custom calculations.
- **File Structure:**  
  - `source/` - Contains raw and processed data files.
  - Power BI `.pbix` file with integrated models and visuals.

---

## Usage Instructions

1. Clone the repository:
``` bash
   git clone https://github.com/your-username/project-name.git
```
2. Open the `BerichtErgebnis.pbix` file in Power BI Desktop.
3. Explore interactive dashboards by navigating through different pages.

---

## Key Findings

- Cardiovascular diseases remain a major cause of death but show a declining trend.
- Life expectancy has increased steadily over the analyzed years.
- Future mortality is predicted to rise, with 2.2 million deaths estimated in Germany by 2030.

---

## Acknowledgments

- **Supervision:** Dozent Andreas Macho, Frankfurt University of Applied Sciences.
- **Data Providers:** Statistisches Bundesamt and Robert Koch Institute.
- **Resources:** [Microsoft Power BI Documentation](https://learn.microsoft.com/en-us/power-bi/)
