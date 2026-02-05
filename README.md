# TOWN OF COCHRANE X URBAN SYSTEMS MOBILITY DATA CASE COMPETITION 2025
### Mitigating Economic Leakage in Downtown Cochrane
**Project Team: TWIN VECTORS (Zoya Malik & Talha Mahr)**

This repository contains the technical submission for the 2025 Urban Systems Mobility Data Case Competition. Our team, **Twin Vectors**, was selected as a **Top 5 Finalist**, placing **4th overall out of 20 competing teams**.


## Project Overview
Cochrane is one of Alberta's fastest-growing communities, yet it faces significant commercial service leakage toward the Calgary metropolitan region. While the downtown core is physically accessible, mobility data reveals that it currently functions as a "touch-and-go" center for errands rather than a place for lingering and leisure.

Our mission was to use high-resolution mobility telemetry to frame the problem, diagnose the root causes of underperformance, and recommend actionable interventions to strengthen connectivity and enhance the local economy.

## Methodology & Technical Stack
The analysis moves beyond anecdote by triangulating physical movement with consumer intent. We applied a rigorous technical workflow to process large-scale datasets while ensuring accuracy and privacy.

### Technical Stack
* **GIS & Spatial Analysis**: QGIS 3.40 was utilized for spatial bounding, point-in-polygon filtering, and coordinate reference system (CRS) management using EPSG:4326.
* **Data Science**: Python 3 with the Pandas and NumPy libraries was used for chunked memory processing and statistical distribution analysis.
* **Visualization**: Programmatic generation of histograms and time-series charts via Matplotlib.

### Key Metrics Defined
* **Total Visits (Signals)**: Measures aggregate activity intensity within the downtown bounding box.
* **Unique Devices**: Proxies distinct visitors to confirm that activity peaks are driven by people and not chatty devices.
* **Dwell Time Proxy**: Calculated as the time delta between a device’s first and last signal in a day to distinguish errand behavior from experiential visits.

## Key Diagnostic Findings
* While activity volume on weekdays is 3.5x higher than on weekends, the unique people count only drops by ~1.8x. This confirms the market is present on weekends but currently unengaged.
* The median dwell time is currently ~7.5 minutes, indicative of a functional, "touch-and-go" economy that lacks experiential "stickiness".
* Residents consistently travel to outside competitors for high-dwell "ancillary" needs, specifically Fitness (12.4x leakage) and Casual Dining (12.0x leakage).

## Proposed Action Plan
To repatriate lost demand, our study recommends five prioritized actions that leverage verified activity peaks:
1. **Recruit a Fitness Anchor**: Bring in a franchise studio to drive recurring, high-dwell foot traffic.
2. **Reliable Casual Dining**: Prioritize family-friendly dining to capture the verified 6:00 PM peak.
3. **Signature Evenings**: Concentrate programming and markets in the verified 5:00 PM – 8:00 PM success window.
4. **Weekend Bundling**: Create Linger packages (e.g., Market + Brunch + Kids Activity) to encourage multi-stop behavior.
5. **Convenience Infill**: Add grab-and-go essentials to stop "Daily Needs" trips from bypassing downtown.

## Repository Structure
* `CochraneCaseCompetitionPresentation.pdf`: Full 16-page technical slide deck covering diagnostic analysis and strategic outlook.
* `ProjectSummary.pdf`: Formal executive summary for stakeholders.
* `References.pdf`: Full bibliography 

## Project Context
* **Competition**: Town of Cochrane x Urban Systems Mobility Data Case Competition 2025.
* **Achievement**: Top 5 Finalist (4th Place / 20 Teams).
* **Dataset**: Pinnacle Platform Mobility Data provided by Azira.
* **Strategic Alignment**: Findings are grounded in the Cochrane Downtown Revitalization Plan and Envision Cochrane 2050.

---
*Technical Note: All data utilized in this analysis was anonymized and aggregated to ensure privacy compliance.*
