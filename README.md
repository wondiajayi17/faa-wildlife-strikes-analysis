# FAA Wildlife Strikes Analysis

## When, where, and how do wildlife strikes impact aviation?

This project analyses aircraft-wildlife strike data from the U.S. Federal Aviation Administration (FAA) to identify patterns in the **frequency, timing, location, wildlife involved, and financial impact** of aircraft strikes.

The analysis was developed in **Tableau** as an interactive dashboard, with the aim of turning a large dataset of wildlife-strike records into clear and meaningful insights about aviation safety and operational impact.

---

## Dashboard

The dashboard investigates four key areas:

### 1. When do aircraft strikes occur?

A time-series visual shows how the number of recorded strikes changed between **2000 and 2014**, while comparing strikes occurring during:

- Dawn
- Day
- Dusk
- Night

This helps identify patterns in when wildlife strikes are most frequently recorded.

### 2. Which wildlife species are involved most often?

The analysis compares wildlife species groups involved in aircraft strikes.

The results show that **birds account for the majority of recorded strikes**, with several bird groups contributing substantially to the overall number of incidents.

### 3. Where do bird strikes occur most frequently?

A geographic map shows the distribution of bird strikes across U.S. states.

The size and colour of each marker represent the number of recorded bird strikes, highlighting areas with particularly high concentrations of incidents.

### 4. Which airports have the greatest financial impact from bird strikes?

The final visual focuses on the **11 airports with the highest total reported costs associated with bird strikes**.

The bars represent total reported cost, while the different colours show the recorded level of aircraft damage, including:

- Destroyed
- Substantial
- Medium
- Minor
- None

This provides an indication of how frequent bird strikes can translate into financial and operational consequences for aviation.

---

## Key Findings

The analysis identifies several important patterns:

- Wildlife strikes increased substantially over the period analysed.
- **Birds were the most frequently involved wildlife category.**
- Bird strikes were concentrated in particular U.S. states and locations.
- The financial impact of bird strikes varied considerably between airports.
- The airports experiencing the highest reported costs were not necessarily those with simply the highest number of incidents.
- Some bird strikes were associated with substantial or destroyed aircraft damage, demonstrating that frequency alone does not fully represent the potential impact of wildlife strikes.

Overall, the analysis suggests that understanding wildlife strikes requires consideration of both **how often they occur and how severe their consequences can be**.

---

## Research Question

> **When, where, and how do wildlife strikes impact aviation?**

This question forms the basis of the Tableau dashboard and connects the analysis of time, wildlife species, geography, and financial impact.

---

## Dataset

The project uses the **FAA Wildlife Strike Database**, containing records of reported wildlife strikes involving civil aircraft.

The dataset contains information including:

- Strike date and time
- Airport
- Origin state
- Wildlife species
- Wildlife species group
- Wildlife animal category
- Aircraft information
- Phase of flight
- Damage level
- Aircraft downtime
- Reported costs
- Number of strikes

The analysis focuses primarily on records from **2000–2014** contained within the dataset used for this project.

---

## Tools Used

- **Tableau** — data visualisation and dashboard development
- **CSV** — source data
- **GitHub** — project documentation and version control

---

## Visualisation Approach

The dashboard was designed around four analytical dimensions:

| Dimension | Question | Visualisation |
|---|---|---|
| Time | When do strikes occur? | Time-series line chart |
| Wildlife | Which species are involved? | Bar chart |
| Location | Where do bird strikes occur? | Geographic map |
| Impact | Where are the financial consequences greatest? | Cost and damage chart |

This structure was chosen to create a clear progression from **frequency → wildlife → location → impact**.

---

## Limitations

The dataset contains **reported wildlife strikes**, meaning the analysis represents recorded incidents rather than necessarily every wildlife interaction involving aircraft.

Reported costs should also be interpreted carefully, as the financial information available in individual records may not represent the complete economic impact of an incident.

The analysis therefore focuses on identifying patterns within the available reported data rather than estimating the total cost of wildlife strikes across the aviation industry.

---

## Project Structure

```text
faa-wildlife-strikes-analysis/
│
├── README.md
├── dashboard/
│   └── FAA_Wildlife_Strikes.twbx
├── data/
│   └── FAA-wildlife-strikes.csv
├── images/
│   └── dashboard.png
└── insights/
    └── key-findings.md
