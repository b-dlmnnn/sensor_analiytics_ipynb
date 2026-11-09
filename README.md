# Semiconductor Sensor Telemetry & Interactive Anomaly Detection

This repository features an end-to-end IoT telemetry data manipulation and interactive visualization pipeline built for semiconductor hardware stress testing. It processes high-frequency sensor logs to isolate thermal spikes and analyze real-time power efficiency.

## 🚀 Key Features & Pipeline Architecture
* **Time-Series Sensor Simulation:** Generates 1,000-second high-frequency microchip stress test logs using NumPy vectorization.
* **Data Manipulation & Feature Engineering:** Computes real-time power consumption metrics (`Watt = Volt * Ampere`) and applies 10-second rolling averages (`Rolling Mean`) via Pandas to smooth out raw sensor jitter.
* **Anomaly Isolation:** Automatically detects and highlights critical hardware thermal spikes and voltage drops during stress testing.
* **Interactive Visualization:** Leverages Plotly to build dynamic, zoomable telemetry dashboards with unified hover inspection.

## 🛠️ Tech Stack & Dependencies
* **Core Environment:** Python 3.14+ / Jupyter Notebook (`.ipynb`)
* **Libraries:** Pandas, NumPy (Data Manipulation & Time-Series Processing), Plotly (Interactive Visualization Engine)
