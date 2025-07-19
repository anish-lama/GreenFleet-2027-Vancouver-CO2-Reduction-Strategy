# GreenFleet-2027-Vancouver-CO2-Reduction-Strategy
Helping City of Vancouver make data driven decision to achieve 20% CO2 reduction by 2027

## 🚗 Problem Overview

The **City of Vancouver** aims to reduce **CO₂ fleet emissions by 20% by 2027**. The baseline (2024) fleet consists of 1,200 units, including light-duty vehicles, heavy trucks, and heavy equipment across all departments.

---

## 💬 Business/Stakeholder Questions

1. How is the fleet distributed and utilized across departments and equipment types?  
2. What patterns emerge in downtime and labor costs across categories?  
3. Are there operational efficiency trends that can guide decisions?  
4. Which departments should cut fleet services to meet the 20% CO₂ target?

> 🔴 **Note:** The city is prioritizing cuts from light-duty and heavy truck categories only.

---

## ✅ Methodology

- [**VancouverFleetAnalysis-DataCleaning.ipynb**](Notebooks/VancouverFleetAnalysis-DataCleaning.ipynb)  
  Applied MCAR statistical methods to clean data with >30% missing values, minimizing bias.

- [**VancouverFleetAnalysis-EDA.ipynb**](Notebooks/VancouverFleetAnalysis-EDA.ipynb)  
  Conducted exploratory data analysis to uncover usage, inefficiency, and emission patterns.

- [**VancouverFleetAnalysis-MergingCO2Data.ipynb**](Notebooks/VancouverFleetAnalysis-MergingCO2Data.ipynb)  
  Researched and integrated secondary CO₂ emission data using interpolation and ensured clean merges with original records.

- [**VancouverFleetAnalysis-RemovalPrioritization.ipynb**](Notebooks/VancouverFleetAnalysis-RemovalPrioritization.ipynb)  
  Built a scoring-based prioritization framework to recommend vehicle removals that meet the 20% CO₂ reduction target.  
  Simulated stakeholder constraints to guide a balanced and feasible reduction strategy.

---

## 🔍 Key Insights

- Identified departments operating the **most inefficient vehicles**, enabling targeted fleet reviews.
- Found **no correlation between vehicle age and inefficiency**, challenging assumptions around older fleets.
- Detected vehicles with **zero utilization**, representing immediate opportunities for decommissioning.
- Uncovered **category-based underutilization** patterns (e.g., certain types consistently underused).
- Confirmed **no correlation between age and utilization**, highlighting the need to assess actual usage data.
- Flagged **older vehicles with consistently low usage**, reinforcing prioritization based on operational data rather than age alone.
- Developed a **priority ranking of vehicles** using a weighted scoring model combining emissions and inefficiency indicators.
- Achieved a **20% projected CO₂ reduction** while minimizing operational disruption, identifying departments with the highest-impact cuts.

---
## 🛠️ Tools & Technologies

- **Notebook Platform:** Google Colab  
- **Languages/Tools:** Python (`pandas`, `numpy`, `matplotlib`) and Excel
