# python-data-analytics-project
# Job Market Data Analysis Project

## Project Overview
This project utilizes Python to perform a data-driven analysis of global job market trends. The primary objective is to identify high-demand skills, analyze salary distribution structures, and determine optimal technical skills based on the intersection of market demand and compensation metrics.

---

## Project Structure

### PART 1: EXPLORATORY DATA ANALYSIS
* **Methodology:** Initialization of data science libraries (Pandas, Seaborn, Matplotlib), programmatic ingestion of the dataset from the Hugging Face Hub, and dataframe schema inspection.
* **Objective:** Assess data types, baseline dimensions, and structural properties prior to executing processing pipelines.

### PART 2: PROJECT SKILL DEMAND
* **Methodology:** Parsing and cleaning nested skill structures, executing data aggregations to calculate frequency distributions, and generating visual representations of technology requirements.
* **Objective:** Identify the core competencies and technical stacks currently prioritized by hiring organizations.

### PART 3: SALARY ANALYSIS
* **Methodology:** Normalization of compensation data points, removal of anomalous records, and statistical plotting of salary spreads across distinct data-related roles.
* **Objective:** Establish clear industry compensation benchmarks and evaluate earnings variance across different positions.

### PART 4: OPTIMAL SKILLS ANALYSIS
* **Methodology:** Cross-referencing technical skill frequency percentages with respective median salaries to model a strategic demand-versus-compensation matrix.
* **Objective:** Categorize optimal skills that yield high market visibility alongside premium financial returns.

---

## Technical Stack
* **Language:** Python
* **Environment:** Google Colab
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Datasets

---
Note: The source execution environment can be viewed directly via Google Colab:
https://colab.research.google.com/drive/185DDtezxhR9lVeyDE9-TWCtri5dHBZ5K?usp=sharing
