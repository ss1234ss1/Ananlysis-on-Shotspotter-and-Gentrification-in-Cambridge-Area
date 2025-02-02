#  Analyzing the Impact of ShotSpotter on Housing Prices and Public Safety in Cambridge, MA

##  Overview
This project investigates the socioeconomic and public safety impacts of **ShotSpotter**, a gunshot detection system, in **Cambridge, MA**. The study focuses on whether **ShotSpotter deployments correlate with rising housing prices, demographic shifts, and gentrification**. Using data-driven insights, the research supports advocacy efforts by **The Black Response**, which seeks to end the ShotSpotter contract in Cambridge.

###  **Why Study ShotSpotter?**
- **Public Safety Concerns**: Investigate the accuracy and effectiveness of ShotSpotter in detecting gun violence.
- **Gentrification & Displacement**: Examine the relationship between ShotSpotter deployments and rising housing costs.
- **Surveillance & Community Impact**: Assess whether ShotSpotter disproportionately targets marginalized communities.

---

## Data and Preprocessing
### **Datasets Used**
- **BridgeStat Crime Reports (2013-2024)**: Gun violence incidents & ShotSpotter alerts.
- **Cambridge Property Dataset (2016-2024)**: Housing prices, property value changes.
- **City Council Reports (2013-2024)**: Analysis of public discourse on ShotSpotter.

### **Data Preprocessing**
- **PDF-to-CSV conversion** of Bridgestat data.
- **Keyword-based extraction** for identifying gunshot incidents.
- **Data Cleaning**: Addressed missing values and inconsistencies.
- **Merging datasets** for housing price & ShotSpotter correlation analysis.

---

##  Methodology
### **1️⃣ Correlation Analysis**
- **OLS Regression**: Examined ShotSpotter impact on housing prices.
- **T-tests**: Compared housing values in neighborhoods with vs. without ShotSpotter.

### **2️⃣ Data Visualization**
- **ArcGIS Mapping**: Visualized ShotSpotter deployment vs. housing price trends.
- **Time-Series Analysis**: Tracked housing price fluctuations pre- and post-ShotSpotter deployment.
- **Neighborhood-Level Comparison**: Analyzed demographic shifts.

### **3️⃣ Public Rhetoric & Policy Analysis**
- **City Council Meeting Reports (2013-2024)**
- **Sentiment Analysis**: Tracked how city officials and the public view ShotSpotter over time.

---

##  Results and Evaluation
| **Key Findings**                         | **Insights** |
|--------------------------------|--------------------------------------|
| **Housing Prices & Gentrification** | ShotSpotter areas saw price increases, suggesting potential displacement effects. |
| **ShotSpotter Accuracy Issues** | Claimed 97% accuracy vs. actual 55.8% detection rate. |
| **Community Impact** | Concerns about over-surveillance and racial bias in deployments. |
| **City Council Rhetoric Shift** | Increased opposition to ShotSpotter in recent years. |



##  Future Research Directions
- **Expand Analysis**: Obtain additional crime & demographic data.
- **Improve Spatial Accuracy**: Overlay ShotSpotter locations with census block-level data.
- **Policy Implications**: Develop data-driven arguments for ending ShotSpotter in Cambridge.

---

##  Acknowledgments
This project was conducted in collaboration with **The Black Response**, an advocacy organization in Cambridge, MA, committed to addressing systemic inequalities in policing and public safety. We also worked closely with a **Boston University Spark!** team as part of the **DS 539 Capstone Class**, leveraging data science methodologies to analyze ShotSpotter's impact. We appreciate the guidance and support from our instructors, project mentors, and external partners throughout this research.


