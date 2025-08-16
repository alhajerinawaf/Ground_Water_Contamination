# Underground Storage Tank (UST) Contamination Analysis (California, 1970–2024)

## Overview
This project analyzes contamination cases caused by leaking underground storage tanks (LUSTs) in California between 1970 and 2024.
The dataset provides insights into how leaks were discovered, contaminants involved, communities impacted, cleanup efforts, and time taken for resolution.
The purpose of this project is to understand trends, environmental impacts, and equity concerns around UST contamination, and to provide data-driven recommendations for stronger prevention and monitoring policies.

## Dataset
The dataset used comes from California’s GeoTracker system and related environmental reporting databases.
Columns analyzed include:
* CASE_TYPE: Type of contamination case
* LEAD_AGENCY: Responsible agency for oversight
* HOW_DISCOVERED – How leaks were first detected
* STOP_METHOD – Methods used to stop leaks
* POTENTIAL_CONTAMINANTS_OF_CONCERN – Chemicals involved (e.g., gasoline, diesel, waste oil)
* POTENTIAL_MEDIA_OF_CONCERN – Environmental media at risk (soil, groundwater, etc.)
* DISADVANTAGED_COMMUNITY – Whether cases occurred in disadvantaged areas
* BEGIN_DATE, LEAK_REPORTED_DATE, NO_FURTHER_ACTION_DATE – Timeline of each case
* RESOLUTION_DAYS – Days taken to close a case

## Visualizations
We created a series of graphs to highlight key findings:
* Contamination Cases Reported (1970–2024) – Trends over time, showing a spike after 1988 EPA regulations.
* Methods of Leak Discovery – Tank closure, monitoring, and other means.
* Methods Used to Stop Leaks – Excavation, removal, monitoring.
* Contamination in Disadvantaged Communities – Equity concerns in exposure.
* Case Status (Open vs Closed) – Percentage breakdown of resolved vs ongoing cases.
* Environmental Areas at Risk – Media of concern (soil, groundwater).
* Lead Agencies – Who manages cleanup cases.
* Contaminants in Reported Cases – Top contaminants found.
* Top Counties with Cases – Geographical distribution.
* Time to Resolve Cases – Median resolution time (≈6 years).

## Key Insights
* Cases spiked in the late 1980s/early 1990s due to new federal & state reporting requirements.
* Petroleum products (gasoline, diesel, waste oil) were the most common contaminants.
* Groundwater is highly vulnerable — even 1 gallon of gasoline can contaminate 1 million gallons of water.
* Median time to resolve cases is ~6 years, showing cleanup is long and resource-intensive.
* Disadvantaged communities are disproportionately impacted, raising environmental justice concerns.

## Recommendations
* Adopt double-walled tanks to prevent future leaks.
* Stronger leak detection systems with real-time monitoring.
* Faster case resolution mechanisms, especially in groundwater cases.
* Prioritize disadvantaged communities for remediation funding and resources.

## Tools & Libraries
* Python – Data wrangling & analysis
* Pandas, NumPy – Data manipulation
* Matplotlib, Seaborn, Folium – Visualization
* Jupyter Notebook – Development environment

## References
* EPA UST Program
* California State Water Resources Control Board – GeoTracker
* AP News – Leaking Tanks Cleanup
* California Environmental Protection Agency (CalEPA)

## Contributors
Research, Data Cleaning ,Coding & Visualization : 
* Rabeaa Ali
* Nawaf AlHajeri
* Hussain AlShaway
