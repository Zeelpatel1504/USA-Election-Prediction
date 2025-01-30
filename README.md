# README - Online Social Network Analysis (OSNA) Final Project

## Project Title: Electoral and Demographic Analysis of Georgia's 13th Congressional District (GA-13)

### Course: CS579 - Online Social Network Analysis (Fall 2024)
### Team Members:
- **Khizar Baig Mohammed** | A20544254 | kmohammed3@hawk.iit.edu
- **Patel Zeel Rakshitkumar** | A20556822 | zpatel15@hawk.iit.edu
- **Abrar Hussain** | A20552446 | ahussain18@hawk.iit.edu
- **Ruchika Rajodiya** | A20562246 | rrajodiya@hawk.iit.edu

---

## 1. Introduction
This project investigates the demographic and electoral patterns in Georgia's 13th Congressional District (GA-13), a suburban district with a diverse population and evolving political landscape. By leveraging data-driven methodologies, we analyze the relationships between socioeconomic indicators and voting behavior, comparing GA-13 with similar districts across the U.S.

### **1.1 Objectives**
- Conduct a demographic and socioeconomic analysis of GA-13.
- Identify key factors influencing voter behavior.
- Utilize machine learning techniques to compare GA-13 with other districts.
- Implement spatial and statistical analyses to model electoral outcomes.

---

## 2. Project Approach
The research is structured into **nine** systematic phases:

### **2.1 Data Acquisition**
- **Sources:**
  - American Community Survey (ACS) (U.S. Census Bureau)
  - OpenElections Project
  - Redistricting Data Hub (shapefiles)
- **Tools:**
  - Python (`requests`, `pandas`, `geopandas`)
  - Census Bureau API

### **2.2 Data Integration and Preprocessing**
- **Merging datasets** using district codes.
- **Standardizing formats** across sources.
- **Handling missing values** and ensuring geospatial consistency.
- **Tools Used:** `pandas`, `geopandas`, `os`

### **2.3 Exploratory Data Analysis (EDA)**
- **Techniques:**
  - Statistical correlations (Pearson, Spearman)
  - Heatmaps, histograms, scatter plots
  - Geospatial visualizations
- **Libraries:** `matplotlib`, `seaborn`, `scikit-learn`

### **2.4 Feature Selection and Cleaning**
- Identifying the most relevant features for voter behavior prediction.
- Handling outliers and normalizing numerical values.
- Feature engineering to enhance model performance.

### **2.5 Dimensionality Reduction**
- **Principal Component Analysis (PCA)** to reduce dataset complexity.
- **Variance Thresholding** to exclude redundant features.
- **Tools:** `scikit-learn`

### **2.6 Spatial Analysis**
- Mapping GA-13 boundaries and election results.
- Overlaying demographic data with precinct-level electoral outcomes.
- **Libraries Used:** `geopandas`, `matplotlib`

### **2.7 Predictive Modeling**
- **Techniques:**
  - Clustering similar districts using `k-means`.
  - Predicting party preference via `logistic regression`.
- **Evaluation Metrics:**
  - Accuracy, Precision, Recall, F1-score
- **Libraries:** `scikit-learn`

### **2.8 Comparative Analysis**
- Using Euclidean distance metrics to compare GA-13 to similar districts.
- Standardizing data using MinMax Scaling.
- **Tools:** `pandas`, `numpy`

### **2.9 Documentation and Reproducibility**
- Jupyter Notebooks with annotated code.
- Git version control for tracking changes.
- Detailed step-by-step process documentation.

---

## 3. Data Sources
### **3.1 American Community Survey (ACS) - U.S. Census Bureau**
- **Usage:** Extracting demographic indicators such as age, race, income, and education.
- **Access Method:** API requests using Python.
- **Challenges:** Data alignment with electoral datasets.

### **3.2 Redistricting Data Hub**
- **Usage:** Acquiring shapefiles for congressional and precinct boundaries.
- **Processing:** Used `geopandas` to merge spatial data with census information.

### **3.3 OpenElections Project**
- **Usage:** Gathering precinct-level voting data.
- **Integration Challenges:** Standardizing identifiers across datasets.

---

## 4. Key Findings
- **GA-13 has a strong Democratic alignment**, with increasing minority voter participation.
- **Median household income and education levels** significantly influence voting patterns.
- **Housing ownership rates and economic disparities** also play a role in electoral trends.
- **Similar districts:** Congressional Districts 4 (GA), 6 (TX), and 10 (FL) based on clustering analysis.

---

## 5. Technologies Used
- **Programming Languages:** Python
- **Libraries:** `pandas`, `geopandas`, `scikit-learn`, `matplotlib`, `seaborn`
- **Tools:** Jupyter Notebooks, GitHub, Census Bureau API

---

## 6. Running the Project
### **6.1 Prerequisites**
- Python 3.x installed
- Jupyter Notebook installed
- Required Python packages installed:
  ```bash
  pip install -r requirements.txt
  ```

### **6.2 Execution Steps**
1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```bash
   cd osna-final-project
   ```
3. Run data processing scripts:
   ```bash
   python data_preprocessing.py
   ```
4. Execute the Jupyter Notebook for analysis:
   ```bash
   jupyter notebook analysis.ipynb
   ```

---

## 7. Future Work
- Expanding analysis to include **social media sentiment analysis** on voter behavior.
- Enhancing the predictive model with **deep learning techniques**.
- Investigating the impact of **redistricting on electoral outcomes**.
- Incorporating **time-series analysis** to track shifts over multiple election cycles.

---

## 8. Contact
For any questions or collaboration opportunities, please reach out to the team via the emails provided above.

---




