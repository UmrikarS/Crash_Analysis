## Abstract

Road safety in New Zealand remains a persistent issue. This master’s thesis addresses the problem of high-severity crash location identification and crash prediction in Auckland, using ten years of crash data (2015–2025) publicly available from the NZTA Crash Analysis System (CAS).  

Using a positivist, quantitative research design implemented through a Microsoft Fabric Medallion Architecture (Bronze–Silver–Gold), this research comprises four analytical streams:

- Geospatial hotspot analysis  
- Machine learning severity prediction  
- Temporal trend analysis  
- Vulnerable user risk profiling  

### Key Findings

- **Geospatial Analysis:**  
  The Getis-Ord Gi* analysis identified **36 statistically significant high-convergence cells** across the SH1/Southern Motorway corridor, with the Grafton–CBD zone reaching a **99.9% confidence level**.

- **Machine Learning Model:**  
  An **XGBoost classifier** trained on 111,657 crash records achieved:
  - ROC-AUC: **0.7175**
  - Recall: **0.638**  
  SHAP analysis revealed that **lighting conditions** and **vulnerable user involvement** were the strongest predictors of crash severity.

- **Temporal Trends:**  
  A significant association between **holiday periods and crash severity** was found using a chi-square test:  
  - χ² = 10.09  
  - p = 0.018  
  **Labour Weekend** recorded the highest severity rate at **6.3%**.

- **Vulnerable Road Users:**  
  Crashes involving pedestrians, cyclists, or motorcyclists were **8.95 times more likely** to result in fatal or serious injury compared to vehicle-only crashes:
  - 23.7% vs 2.6% severe rate

### Recommendations

Twelve evidence-informed recommendations are proposed, including:

- Targeted lighting improvements  
- Specialised infrastructure for vulnerable users  
- Labour Weekend enforcement campaigns  
- Machine learning–guided patrol routing  

These interventions are estimated to deliver a **combined annual benefit**.

### Limitations and Reflections

The study acknowledges several limitations and considerations:

- Absence of crash hour data in the public dataset  
- Ethical and cultural responsibilities under **Te Tiriti o Waitangi** in data stewardship  
- Adaptation of standard machine learning practices to the New Zealand transport context  
