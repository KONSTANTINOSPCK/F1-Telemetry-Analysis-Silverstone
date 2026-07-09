# F1 Telemetry Analysis: Hamilton vs Russell (Silverstone 2024)

## Project Overview
This project focuses on Motorsport Data Analytics using official FIA telemetry data from the 2024 British Grand Prix (Silverstone) Qualifying session. Utilizing Python and the `FastF1` API, the analysis evaluates and compares the driving styles, braking points, throttle inputs, and gear selection strategies of teammates Lewis Hamilton and George Russell in their Mercedes W15 AMG cars.

The goal of this project is to demonstrate how data science techniques (time-series analysis, data visualization, and signal processing) are applied in modern Formula 1 race engineering to optimize driver performance.

## Key Insights from the Analysis
* **Cornering Strategy (Turns 3 & 4 - Village & The Loop):** George Russell optimized his entry phase, carrying ~3 km/h more apex speed into Turn 3. Conversely, Lewis Hamilton sacrificed early corner speed to rotate the car quicker, allowing him to apply 100% throttle earlier on exit and gaining a top-speed advantage on the following straight.
* **Driver Inputs & Powertrain Management:** Both drivers utilized identical gear-shifting patterns (downshifting rapidly from 8th to 3rd gear within 70 meters), keeping the V6 Turbo Hybrid engine within its optimal power band (dropping to a minimum of ~6,300 RPM before accelerating back to 11,700 RPM).

## Tech Stack & Libraries
* **Language:** Python
* **Environment:** Jupyter Notebook
* **Data Source:** FastF1 API (Official FIA Live Timing Integration)
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib

## How to Run the Project
1. Install the required dependencies:
   ```bash
   pip install fastf1 matplotlib pandas
