# SPS-Vertical-vs-Traditional

This project analyzes the efficiency of **vertical solar panels (90°)** compared to **traditional fixed-tilt panels (45°)** and **dynamic panels (daily optimal tilt)**.  
The study focuses on the **Kyiv region (Ukraine)** and extends to a **worldwide perspective** using Python and visualization tools.

## 📌 Project Goals
- Compare real electricity production from vertical panels (10kW) with theoretical efficiency.
- Analyze **seasonal differences** (winter vs. summer).
- Calculate **optimal tilt angles** for different regions monthly.
- Estimate **losses** of vertical panels compared to:
  - Traditional panels (45° tilt).
  - Dynamic panels (ideal daily tilt).
- Create an **interactive map** with recommendations (Ukraine and world).

## 🛠️ Tech Stack
- **Python** (pandas, numpy, matplotlib, pvlib, folium)
- **Data**: real production data from 10 kW vertical panels in Kyiv + solar position calculations
- **Visualization**: line charts, interactive map with folium

## 📊 Results & Insights
- Vertical panels (90°) show **much higher efficiency in winter months** when the sun is low.
- In Kyiv, vertical panels can cover energy needs in winter **8–10 kW vs. ~5 kW in summer**.
- Losses compared to 45°-panels are acceptable in regions with long winters & **increased energy demand during cold seasons**.
- The approach is useful for **urban installations**, **balcony solar**, and areas where traditional tilt is impractical.

## 🌍 Interactive Map
The project includes a **folium-based map** showing:
- Optimal tilt per city/region.
- Losses of vertical panels vs. 45° fixed panels.
- Losses of vertical panels vs. dynamic (ideal) panels.

👉 Example: 

## 📂 Repository Structure
