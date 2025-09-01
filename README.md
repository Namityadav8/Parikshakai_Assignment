##Data Science Text Corpus Generation
This repository contains the code and data for a small-scale project that creates a text corpus related to the Data Science domain. The project demonstrates an end-to-end pipeline for data collection, cleaning, and annotation, resulting in a structured dataset ready for use in NLP tasks.

🚀 Project Pipeline
The project is executed in three main steps, each handled by a dedicated Python script:

Data Scraping (scraper.py)
This script is responsible for collecting raw text snippets from various online sources, such as job boards and data science blogs. It fetches HTML content, extracts text paragraphs, and saves the initial dataset to a CSV file.

Data Cleaning (cleaner.py)
The second script processes the raw, messy data. It performs several crucial cleaning steps, including removing HTML tags, normalizing case, eliminating special characters, and deduplicating entries. The cleaned output is saved as a separate CSV file.

Data Annotation (annotator.py)
The final step involves enriching the cleaned data with meaningful labels. This script uses a simple rule-based approach to tag each text sample with a category, skill, and difficulty level. The final, annotated dataset is saved in both CSV and JSON formats.

📦 Deliverables
scraper.py: Python script for web scraping.

cleaner.py: Python script for data cleaning.

annotator.py: Python script for data annotation.

raw_text_samples.csv: The initial dataset with unprocessed text.

cleaned_samples.csv: The normalized dataset after cleaning.

annotated_samples.csv: The final dataset with assigned labels.

annotated_samples.json: The final dataset in JSON format.

🏷️ Annotation Labels
The following labels are used to annotate the dataset:

category:

Job Description

Interview Question

Blog/Article

skill_tag:

python

sql

machine learning

nlp

statistics

difficulty:

Beginner

Intermediate

Advanced

▶️ How to Run
Clone this repository.

Install the required libraries from requirements.txt:

pip install -r requirements.txt

Run the scripts in order:

python scraper.py
python cleaner.py
python annotator.py

✍️ Author
[Your Name Here]
