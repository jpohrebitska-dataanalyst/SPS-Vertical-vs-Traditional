# Executive Summary  
This project explores the efficiency of a **10 kW solar power station near Kyiv**, comparing vertical (90°), classic (45°), and dynamic tilt angles.  
Key findings show that vertical panels are nearly **ideal in winter** (November–February), while 45° panels provide **stable annual output**.  
For Ukraine, the best compromise is **45–50° fixed tilt**, while **seasonal adjustment (75°/25°)** or **dynamic systems** deliver maximum efficiency but at higher cost and complexity.  

---
## Conclusions  
This project analyzes the efficiency of a **Solar Power Station 10 kW**, located near Kyiv, oriented to the south and installed vertically (90°).  
In Ukraine, the most common installation angle is around 45° (roof- or ground-mounted panels).  

---  
## 1. Theoretical Efficiency of a Vertical Panel  
- Based on **pvlib** calculations, a vertical panel in Kyiv:  
- Shows **the lowest efficiency** during summer, unlike a classic 45° panel.  
- Has **the highest efficiency** in winter: **November–February**.  

<img width="1242" height="435" alt="image" src="https://github.com/user-attachments/assets/227d00f4-b8d3-48c5-950e-dabde45bd6c9" />  

---  
## 2. Comparison with Actual Data  
- Real data from my station (March–September 2025) aligns with the theoretical curve.  
- Deviations are explained by sunnier or cloudier days.  
- The strongest production is seen in **March–April** and **August–September**.  
- As expected, the peak output will occur in **November–February**, exactly when energy is most needed for heating.  

<img width="1240" height="435" alt="image" src="https://github.com/user-attachments/assets/c947b536-1903-4bae-b550-098c60995800" />  

---  
## 3. Optimal Tilt Angle for Kyiv  
- Calculations show the **average annual optimal tilt ≈ 49.5°**.  
- Monthly optimal angles:  
  - November — 82°, December — 90°, January — 87°, February — 71°,  
  - March — 53°, April — 34°, May — 20°, June — 8°,  
  - July — 11°, August — 28°, September — 46°, October — 64°.  
- Conclusion: **in winter, a vertical panel (90°) is nearly ideal**.  

---  
## 4. Comparison of Three Scenarios  
- Vertical (90°)  
- Classic (45°)  
- Dynamic (daily angle adjustment)  

Vertical panel shows:  
- **Absolute advantage** in January, February, November, December.  
- **Minimal losses** in October and March (<20%).  
- **Largest losses** in April–September (27–62%).  

<img width="1165" height="545" alt="image" src="https://github.com/user-attachments/assets/9c12b3e6-ca40-416a-ba54-dbec9e4c8e27" />  

---  
## 5. Efficiency Ranges  
- Dynamic: **31.7% – 36.5%**  
- Classic (45°): **27% – 31.8%**  
- Vertical (90°): **11.5% – 36.5%**  

> **Efficiency** = cos(AOI), where AOI (Angle of Incidence) is the angle between the sun’s rays and the panel surface.  

---  
## 6. Effect of Tilt in Other Regions of Ukraine  
- Optimal tilt for most Ukrainian cities: **45–50°**.  
- Losses for a vertical panel compared to classic: **19–23%**.  
- Losses compared to dynamic: **28–33%**.  

---  
## 7. Interactive Map of Ukraine  
- Using Python and **folium**, I created a map: clicking on a city shows the optimal tilt and efficiency losses.  

<img width="945" height="637" alt="image" src="https://github.com/user-attachments/assets/f6d79771-90a5-4b75-a36f-81e9be04d145" />  
<img width="971" height="621" alt="image" src="https://github.com/user-attachments/assets/b4142983-198e-45d1-a249-a9fca01d8f55" />  

[🔗 Open interactive map](docs/solar_tilt_ukraine_map.html)
---  
## 8. Global Map (SunCalc.js)  
- Using **Gemini + SunCalc.js**, I built a global map of optimal tilt angles.  
- Results are close to pvlib but simpler to compute.  

Examples:  
- Oslo — vertical panel losses are ~10% compared to classic; vertical panels are a good option for heating during winter.  
- Northern Canada — losses are nearly zero; optimal tilt is above 60°.  
- Colombia — optimal tilt ~12°; vertical panel losses ~80% (making vertical panels unsuitable for such regions).  

<img width="1528" height="738" alt="image" src="https://github.com/user-attachments/assets/83608ac9-7f27-4e07-91e6-842c0d1c804a" />  

🔗 [Open Gemini Map](https://gemini.google.com/share/7263b86410c4)
---  
## 9. Key Insights for Ukraine  
- **45° (classic tilt)** — a compromise: not perfect for any month, but provides stable annual generation.  
- **90° (vertical panels)** — best for winter, easy to maintain, space-saving, maximize output in cold months.  
- **83°** — a compromise to boost winter generation, though harder to install.  
- **Seasonal tilt adjustment** (ideal option):  
  - October–March: 75°  
  - April–September: 25°  
- **Dynamic systems** (daily adjustment) — most efficient, but expensive and complex.  

---  
## 10. Practical Takeaways for Ukraine  
- If **annual generation** is the priority → fixed tilt **45–50°**.  
- If **winter generation** is critical → **90°** or **75°**.  
- Ideal setup → **seasonal tilt adjustment**.  

---  
