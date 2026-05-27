# Gravitational Wave Event Dashboard

An interactive Power BI dashboard analyzing 90+ confirmed gravitational wave 
detections from the LIGO/Virgo/KAGRA collaboration (2015–present).

## Dashboard
[PDF to be uploaded --]

## Data Source
GWOSC Event API — https://gwosc.org/eventapi/

## What This Shows
- Detection timeline across observing runs O1 through O4
- Mass distribution of merging black holes and neutron stars
- Sky localization of events in equatorial coordinates
- Signal quality (SNR) and false alarm rate analysis

## Tools Used
- Python 3.11, pandas, astropy — data extraction and cleaning
- Power BI Desktop — data modeling, DAX measures, visualization
- Power BI Service — publishing and sharing

## Key Findings
- Over 90% of detected events are binary black hole (BBH) mergers
- Detection sensitivity has improved dramatically from O1 to O3
- The most massive event detected is [find and fill in your data]
- GW170817 (the first neutron star merger) remains the closest detected event

## How to Reproduce
1. Clone this repo
2. Run `01_data_pull.ipynb` to fetch fresh data from GWOSC
3. Run `02_data_clean.ipynb` to clean and export the CSV
4. Open `GW_Dashboard.pbix` in Power BI Desktop