# Hospital Admissions Dashboard

An interactive Power BI dashboard that analyzes hospital admissions, billing, and insurance data across patients, doctors, medical conditions, and medications.

![Dashboard overview](screenshots/dashboard_overview.png)

## Project Goal

To give hospital management a quick view of admission volumes and billing, so they can see when demand peaks and where revenue comes from. Filters for year and admission type let users drill into specific periods.

## Key Insights

- The dataset covers **113K admissions** and **2.89bn in total billing**, an average of **25.49K per admission**, with an average length of stay of **15**.
- Admissions stay fairly steady through the year. They range from **8,687 in [lowest month]** to **10,050 in [peak month]**, roughly 7% above and 8% below the monthly average.
- Billing is spread almost evenly across insurance providers (Medicare, UnitedHealthcare, Cigna, Blue Cross, Aetna), each at about 0.57-0.59bn, so no single insurer dominates revenue.
- Billing is also close to even across [medications / conditions], at about 0.57-0.59bn each.

## Tools Used

- **Power BI**: star-schema data model (a facts table plus doctor, insurance, medical condition, medication, and patient dimensions), DAX measures, and visuals
- **Figma**: dashboard layout and design
- [Excel / SQL / Python, if you used them for cleaning]

## Design Process

I designed the layout in Figma first, then built it in Power BI.

![Figma design](screenshots/figma_design.png)

## Data

- **Source:** [where the data came from, with a link if it's public]
- **Cleaning steps:** [e.g. removed duplicates, fixed date formats]

## How to Open the Dashboard

1. Download `health_dashboard.pbix` from this repository.
2. Open it with [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free, Windows only).

## Author

Amira Ibrahim
Aspiring
