# Cochrane Mobility Data — Case Competition 2025

Spatial and mobility data analysis for the Town of Cochrane x Urban Systems Mobility Data Case Competition. Diagnosed commercial service leakage from Cochrane's downtown core and proposed data-driven interventions to improve economic retention.

**Team:** Twin Vectors (Zoya Malik & Talha Mahr)  
**Result:** 1st Place — Top 5 Finalist out of 20 competing teams

## Problem

Cochrane is one of Alberta's fastest-growing communities, yet mobility telemetry shows its downtown functions as a "touch-and-go" errand destination rather than a place for sustained visits. Residents consistently travel to Calgary for fitness, dining, and leisure — categories with high dwell-time and economic value.

## Technical Stack

| Tool | Use |
|------|-----|
| QGIS 3.40 | Spatial bounding, point-in-polygon filtering, CRS management (EPSG:4326) |
| Python (pandas, NumPy) | Chunked memory processing, statistical distribution analysis |
| Matplotlib | Histograms, time-series visualization |

## Key Metrics

- **Total Visits (Signals):** Aggregate activity intensity within the downtown bounding box
- **Unique Devices:** Proxy for distinct visitors
- **Dwell Time Proxy:** Delta between first and last signal per device per day

## Key Findings

- Weekday activity is 3.5× higher than weekends, but unique visitor count drops by only 1.8× — the weekend market exists but is unengaged.
- Median dwell time: ~7.5 minutes, consistent with errand-only behavior.
- Highest leakage categories: Fitness (12.4×) and Casual Dining (12.0×).

## Recommendations

1. Recruit a fitness anchor tenant to drive recurring high-dwell traffic.
2. Prioritize family-friendly casual dining to capture the verified 6:00 PM peak.
3. Concentrate programming in the 5:00–8:00 PM window where activity data is strongest.
4. Launch weekend bundling (market + brunch + activity) to encourage multi-stop visits.
5. Add convenience retail to prevent daily needs trips from bypassing downtown entirely.

## Repository Structure

```
cochrane-mobility-data/
├── Presentation.pdf        — Full 16-page technical slide deck
├── Project-Summary.pdf     — Executive summary
├── Briefing-Document.pdf   — Technical briefing
├── References.pdf          — Full bibliography
└── README.md
```

*All data used in this analysis was anonymized and aggregated in compliance with privacy requirements.*
