# Cancer Risk in California’s East Bay

## Purpose of this project

This repository is analyzing patterns of **cancer risk due to toxicity in the air** in California’s **East Bay region** (Alameda, Contra Costa, and Solano Counties). Using data from the **EPA’s EJScreen**, this project focuses on the **spatial distribution of cancer risk** and its relationship with **demographic vulnerability**. Mapping these variables visualizes how environmental burdens, such as air pollution, are related to cancer risk, and they may disproportionately affect communities of color or low-income populations.

## Repository Structure

``` bash
.
├── data
│   └── ejscreen
│       ├── california.gpkg
│       ├── east_bay_ejscreen.gpkg
│       ├── EJSCREEN_2023_BG_StatePct_with_AS_CNMI_GU_VI.gdb
├── EDS223-HW1.Rproj
├── ej_screen.qmd
├── output
└── README.md
```

## Data Access

The project uses publicly archived data from the **EPA EJScreen,** loaded in using `sf` package

## Authorship

This repository is for the EDS - 223

-   The project author: **Jay Kim**
-   Instructor: **Annie Adams**
-   Teaching Assistant: **Ale Vidal Meza**

## References

United States Environmental Protection Agency. 2015. EJSCREEN. Retrieved: October 05th, 2025, www.epa.gov/ejscreen.
