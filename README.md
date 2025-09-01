
# Parikshakai 📘  
*A Data Processing and Analysis Project*  

## 📌 Project Overview  
Parikshakai is a notebook-based project aimed at **data cleaning, preprocessing, and annotation** for further analysis. The workflow includes collecting raw data, applying structured preprocessing techniques, and generating a cleaned dataset suitable for annotation and downstream tasks such as classification or visualization.  

The project demonstrates a **complete pipeline** – from raw dataset preparation to a usable annotated dataset.  

---

## ⚙️ Approach  

1. **Data Collection**  
   - Collected domain-specific raw data (minimum 50 samples).  
   - Stored data in a structured format (CSV/JSON).  

2. **Data Cleaning**  
   - Removed irrelevant characters, special symbols, and missing values.  
   - Normalized text (lowercasing, trimming whitespaces, standard formatting).  
   - Ensured dataset consistency.  

3. **Data Annotation**  
   - Defined 2–3 domain-specific labels (e.g., `Skill Tag`, `Experience Level`, `Question Type`).  
   - Wrote an annotation script for semi-automatic/manual tagging of cleaned samples.  
   - Saved annotated dataset in CSV for future ML tasks.  

4. **Final Output**  
   - `cleaned_data.csv` – structured dataset.  
   - `annotated_samples.csv` – labeled dataset ready for ML experiments.  

---

## 🛠️ Tools & Libraries  

- **Python** – Core programming language.  
- **Jupyter Notebook** – Interactive environment for coding and analysis.  
- **Pandas** – Data manipulation and cleaning.  
- **NumPy** – Efficient numerical operations.  
- **BeautifulSoup / Requests** *(if web scraping involved)* – Data collection from the web.  
- **CSV/JSON modules** – For input-output operations.  

---

## 🚀 Key Features  

- End-to-end pipeline from raw data → cleaned data → annotated dataset.  
- Modular approach (data collection, preprocessing, annotation separated).  
- Human-readable variable naming for better code understanding.  
- Annotation system designed to be flexible and adaptable to any domain.  

---

## 🔧 Challenges Faced  

1. **Data Quality Issues**  
   - Raw samples often contained noise, incomplete text, and inconsistent formatting.  
   - Solution: Implemented multiple cleaning functions (lowercasing, punctuation removal, whitespace trimming).  

2. **Annotation Ambiguity**  
   - Deciding correct labels for certain samples was tricky.  
   - Solution: Defined strict annotation guidelines to maintain consistency.  

3. **File Handling in Jupyter**  
   - Encountered issues when saving outputs due to incorrect paths.  
   - Solution: Used absolute paths (`/mnt/data/...`) to ensure files are written correctly.  





