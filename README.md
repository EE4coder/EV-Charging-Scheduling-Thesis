# Smart EV Charging Scheduling with Seasonal Uncertainty and PV Integration 
**Optimizing Grid-to-Vehicle (G2V) and Vehicle-to-Grid (V2G) operations using Differential Evolution** 

This repository contains the thesis and supporting materials for our Bachelor of Technology project on optimizing Electric Vehicle (EV) charging schedules under seasonal variations, integrating Grid-to-Vehicle (G2V), Vehicle-to-Grid (V2G), and Photovoltaic (PV) systems.

## 📄 Thesis Abstract
The project proposes a Differential Evolution (DE)-based optimization model to minimize EV charging costs while accounting for seasonal uncertainties (summer, monsoon, winter) and driving patterns.
## 📌 **Key contributions:** 
- Minimizes EV charging costs by **35%** through seasonal-aware scheduling  
- Integrates **PV systems** with dynamic tariff analysis  
- Uses **Differential Evolution (DE)** for multi-objective optimization 

## 🏛️ **Academic Context**  
- **Institution**: Institute of Engineering & Management, Kolkata  
- **Degree**: B.Tech in Electrical Engineering (2025)  
- **Supervisor**: Prof. Dr. Sourav Das  
- **Publications**:  
  - 📄 Springer LNEE Conference Paper (IEMRE 2024)
  - *"Optimal Scheduling of Plugin Electric Vehicles Considering Seasonal Uncertainty"*  
  - 📝 IEEE Journal Paper (Under Review)
  - *"Electric Aircraft Charging: Current Status and Challenges"* 

## 📂 Repository Contents
- **7th-Semester**: Conference papers, technical reports  
- **8th-Semester**: Full thesis, defense slides, datasets  
- **MATLAB-Code**: Optimization algorithms (view-only)  
- **Datasets**: Seasonal driving cycles, solar irradiance data (downloadable)  

## 🔍 Key Findings
| Season  | PV Utilization | Grid Load Reduction | Cost Savings |
|---------|----------------|---------------------|--------------|
| Summer  | 60-80%         | 40-50%              | 20-35%       |
| Monsoon | 30-50%         | 20-30%              | 15-25%       |
| Winter  | 20-40%         | 10-20%              | 10-15%       |

## **Highlight**: 
- 🌞 **Summer Optimization** | 75% PV utilization 
    - **S$120/day** savings for a 50-EV station. 
- 🌧️ **Monsoon Adaptation** | 30-50% grid load reduction 
    - Predictive scheduling improves reliability despite cloud cover. 
- ❄️ **Winter Strategy** | Max V2G profit (-3.5168$/vehicle)
    - Hybrid PV-grid charging still achieves **15% cost savings**.
From the thesis, the performance of Electric Vehicles (EVs) in Vehicle-to-Grid (V2G) mode varies significantly across seasons, both with and without Photovoltaic (PV) integration. Here's a summary of the findings:

### 🔌 **Without PV Integration:**
- **Winter** exhibits the **highest V2G participation** due to reduced driving distances and lower battery efficiency in cold weather. This results in more energy being available for discharge back to the grid.
  - **Cost comparison (Table 4.3):**  
    - **HBC (High Battery Capacity) EVs:** Winter (-3.5168 S$) > Monsoon (-1.2108 S$) > Summer (-1.3511 S$).  
    - **LBC (Low Battery Capacity) EVs:** Still shows higher V2G activity in winter (1.366 S$) compared to other seasons, though less pronounced than HBC.

### ⚡**With PV Integration:**
- **Summer** shows the **highest V2G discharge (17.59% for HBC, 16.98% for LBC)** despite strong PV availability. This is because surplus solar energy is stored in EV batteries and later discharged to the grid during peak demand.
- **Monsoon** has moderate V2G activity (10.84% for HBC, 12.53% for LBC) due to intermittent solar generation.
- **Winter** has the **lowest V2G discharge (9.08% for HBC, 11.34% for LBC)** because of reduced driving needs and battery conservation.

### 🏆Conclusion:
- **Highest V2G without PV:** **Winter** (cold weather reduces driving, increasing battery availability).  
- **Highest V2G with PV:** **Summer** (surplus solar energy enables more grid discharge).  

This seasonal analysis highlights how PV integration shifts optimal V2G participation from winter to summer, emphasizing the role of renewable energy in EV-grid interactions.

## 🛠️ **Technical Implementation**  
**Tools & Methods**:  
- 🌀 **Algorithms**: Differential Evolution, Normal Distribution Modeling  
- 💻 **Software**: MATLAB R2023a, Simulink  
- 📊 **Data Sources**: Renewables.ninja, Real-world driving cycles  

## 📜 Documentation
- 📁 [7th-Semester]
- <a href=https://github.com/EE4coder/EV-Charging-Scheduling-Thesis/blob/main/Documentations(encripted)/report(Sem-7).pdf>🧮Report </a> *(View-only)*
- 🔒 [Research Paper](https://github.com/EE4coder/EV-Charging-Scheduling-Thesis/blob/main/Documentations(encripted)/research%20paper(encrypted).pdf) *(View-only)*
- 🔒 [Conference Presentation](https://github.com/EE4coder/EV-Charging-Scheduling-Thesis/blob/main/Documentations(encripted)/IEMRE(encrypted).pdf).*(View-only)*
- <a href=https://github.com/EE4coder/EV-Charging-Scheduling-Thesis/blob/main/Documentations(encripted)/Group-11(Sem-7).pptx>🧮Presentation </a>
- 📁[8th-Semester]
- 🔒 [Final Thesis](https://github.com/EE4coder/EV-Charging-Scheduling-Thesis/blob/main/Documentations(encripted)/FINAL_THESIS_FULL_mine(encrypted).pdf) *(View-only)*
- <a href=https://github.com/EE4coder/EV-Charging-Scheduling-Thesis/blob/main/Documentations(encripted)/Group%2011(Sem-8).pptx>🧮Presentation </a>
- 📁 [MATLAB Code Overview] 
- 🔒 [Summer](https://github.com/EE4coder/EV-Charging-Scheduling-Thesis/blob/main/MatlabCode(encripted)/EV_summer_hbc.pdf) *(View-only)*  
- 🔒 [SummerPV](https://github.com/EE4coder/EV-Charging-Scheduling-Thesis/blob/main/MatlabCode(encripted)/EV_summerPV_hbc.pdf) *(View-only)*
- 🔒 [Monsoon](https://github.com/EE4coder/EV-Charging-Scheduling-Thesis/blob/main/MatlabCode(encripted)/EV_monsoon_hbc.pdf) *(View-only)*
- 🔒 [MonsoonPV](https://github.com/EE4coder/EV-Charging-Scheduling-Thesis/blob/main/MatlabCode(encripted)/EV_monsoonPV_hbc.pdf) *(View-only)*
- 🔒 [Winter](https://github.com/EE4coder/EV-Charging-Scheduling-Thesis/blob/main/MatlabCode(encripted)/EV_winter_hbc.pdf) *(View-only)*
- 🔒 [WinterPV](https://github.com/EE4coder/EV-Charging-Scheduling-Thesis/blob/main/MatlabCode(encripted)/EV_winterPV_hbc.pdf) *(View-only)*
- 📊 <a href=https://github.com/EE4coder/EV-Charging-Scheduling-Thesis/blob/main/MatlabCode(encripted)/Output-demo.pdf>🧮Output Demo </a>
  

## ⚠️ Usage Notes
Freely downloadable for research replication:
- **PDF**:
- <a href=https://github.com/EE4coder/EV-Charging-Scheduling-Thesis/blob/main/Documentations(encripted)/Analysis%20of%20Solar%20Photovoltaic%20Power%20Generation%20Data%20for%2023.5350%C2%B0N%2C%2087.3380%C2%B0E.pdf>Analysis of Solar Voltaic Power Generation Data </a> 
- **Excel Files**: 
- <a href=https://github.com/EE4coder/EV-Charging-Scheduling-Thesis/blob/main/Datasets/seasonal%20tariff.xlsx>📊Dynamic Tariff Dataset  </a>
- <a href=https://github.com/EE4coder/EV-Charging-Scheduling-Thesis/blob/main/Datasets/renewable.ninja_raw_data(durgapur).csv>📊Solar Irradiation(23.533440° N,87.321930° E)</a>
- <a href=https://github.com/EE4coder/EV-Charging-Scheduling-Thesis/blob/main/Datasets/Monthly%20Solar%20Power%20Generation%20Trend%20in%202019(1).csv>📊Monthly Solar Power Generation Trends </a>
- <a href=https://github.com/EE4coder/EV-Charging-Scheduling-Thesis/blob/main/Datasets/Summer_PV.xlsx>🌞Summer with PV </a>
- <a href=https://github.com/EE4coder/EV-Charging-Scheduling-Thesis/blob/main/Datasets/Monsoon_PV.xlsx>🌧️Monsoon with PV </a>
- <a href=https://github.com/EE4coder/EV-Charging-Scheduling-Thesis/blob/main/Datasets/Winter_PV.xlsx>❄️Winter with PV </a>

## 📝 How to Cite
```bibtex
@article{Das S, Modi S, Bera S and Dutta R, 2024. Optimal Scheduling of Plugin Electric Vehicles Considering Seasonal Uncertainty. IEMRE 2024, Springer)

  title={Optimal Scheduling of Plugin Electric Vehicles Considering Seasonal Uncertainty},
  author={Das, Sourav and Bera, Soumyadeep and Modi, Shruti and Dutta, Rupali},
  booktitle={International Conference on Energy Management},
  year={2024},
  publisher={Springer}
}
