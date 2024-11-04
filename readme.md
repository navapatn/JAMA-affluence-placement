**Clinician Practice Placement and Socioeconomic Data Analysis**
This project analyzes the relationship between clinician characteristics and their likelihood of practicing in socioeconomically deprived areas. By combining clinician data from the Centers for Medicare & Medicaid Services (CMS) with socioeconomic data from the Area Deprivation Index (ADI), we assess the factors influencing new clinicians’ practice location choices, especially in deprived regions.

**Data Sources**
CMS Doctors and Clinicians Data

****Source:** Centers for Medicare & Medicaid Services (CMS)**
**Date Downloaded:** August 20, 2024
**Description:** This dataset contains clinician-level records, unique by identifiers like NPI, Enrollment ID, Organization PAC ID, and Address ID. For each clinician, only the earliest record by graduation year is used to identify their first practice location.
Area Deprivation Index (ADI)

**Source: Neighborhood Atlas, Center for Health Disparities Research, University of Wisconsin**
**Date Downloaded:** September 10, 2024
**Description: **The ADI provides a socioeconomic rank based on 17 factors (income, education, employment, and housing) derived from the American Community Survey. ADI is available at the census block group level for 2015 and 2020, reflecting levels of deprivation within ZIP codes.
U.S. Census Bureau Population Data

**Source: U.S. Census Bureau**
**Date Accessed:** Manually obtained via interactive interface
**Description: **Population estimates for ZIP code areas were downloaded and converted to a CSV format for integration into the analysis pipeline.
**Analysis Overview**
Using the combined datasets, we conducted logistic and linear regression analyses to explore the association between clinician characteristics and the likelihood of practicing in areas of high socioeconomic deprivation (defined as ADI ranks in the 80th percentile and above). Key covariates include:

- Gender (reference: female)
- Specialty group (reference: primary care)
- Graduation from top-ranked medical schools
- Log of the total population in the practice area


**Motivation**
This analysis aims to provide insights into the distribution of new clinicians across different socioeconomic regions. By understanding the factors that influence initial practice placements, especially in deprived areas, this research could inform policies aimed at promoting equitable healthcare distribution.

**Code and Reproducibility**
All code and analysis scripts are publicly available in this repository. Detailed documentation for running analyses, requirements, and data processing steps are included.
