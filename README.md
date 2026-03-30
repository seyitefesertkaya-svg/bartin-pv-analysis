#  Photovoltaic Power Plant Feasibility Analysis (Port Application)

This project presents a comprehensive technical and economic feasibility analysis of a photovoltaic (PV) power plant designed for port self-consumption.

---

##  Project Overview

This study evaluates the feasibility of installing a PV system for Bartın Port to reduce grid dependency and energy costs.

- Solar data obtained from NASA POWER database
- System designed for self-consumption
- Includes both technical and financial analysis

---

##  Data Sources

- NASA POWER (GHI solar radiation data)
- Bartın Port feasibility report (2011 consumption data)
- Canadian Solar TOPBiHiKu7 (630 Wp) panel specifications

---

##  Methodology

### Solar Analysis
- GHI → POA conversion applied
- System orientation: South-facing, 30° tilt

### System Design
- Panel power: 630 Wp
- Performance ratio: 0.80

### Energy Modeling
- Specific yield: **1279 kWh/kWp·year**
- Installed capacity determined based on consumption

---

##  Key Results

- Installed Capacity: **2.3 MWp**
- Annual Energy Production: **2.94 GWh/year**
- Annual Consumption (reference): **~2.92 GWh/year (KKO 70%)**
- Number of Panels: **~3624 panels**

---

##  Economic Analysis

- CAPEX: **≈ 68.91 million TL**
- Annual Savings: **≈ 12.80 million TL/year**
- OPEX: **≈ 1.03 million TL/year**
- EBITDA: **≈ 11.76 million TL/year**
- EBIT: **≈ 4.87 million TL/year**

- Electricity Price: **4.35 TL/kWh**
- Project Lifetime: **12 years**
- Discount Rate: **10%**

---

##  Key Insight

The system is capable of covering a significant portion of the port's electricity demand and provides strong economic returns under the reference scenario.

---

##  Technologies Used

- Python
- MATLAB
- LaTeX

---

##  Project Structure


bartin-pv-analysis/
│── report.pdf
│── report.tex
│── figures/
│── data/


---

##  Visual Results

- Monthly GHI vs POA comparison  
- Monthly PV energy production  
- Consumption vs production comparison  
- Discounted cash flow analysis  

(All figures are included in the report)

---

##  How to Use

1. Clone the repository:

git clone https://github.com/seyitefesertkaya-svg/bartin-pv-analysis.git


2. Open the report:

report.pdf


---

##  Future Improvements

- Integration of real-time consumption data  
- Battery storage optimization  
- Advanced financial modeling  

---

##  Author

**Seyit Efe Sertkaya**  
Physics Engineering Student  
Istanbul Technical University  

---

##  Report

Full technical report available here:  
👉 report.pdf
