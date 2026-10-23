# Minor Project: Medicine Recommendation and Infirmary Management

A Streamlit app backed by a MySQL database, plus a Hugging Face (BART) model that suggests medication for a given medical condition.

## Files

- app.py - the Streamlit infirmary management app (patients, products)
- model.py - trains and runs the medication recommendation model
- maintry2working.py - an earlier working version of the app
- csvcreater.py - script that creates the drugs CSV
- drugs_for_common_treatments.csv - the dataset
- templates/ - HTML, CSS and JS files
- requirements.txt - Python packages

## Setup

1. Install the packages: pip install -r requirements.txt
3. Start MySQL and create a database called infirmary.
4. Set your MySQL password: export MYSQL_PASSWORD="your-password"
5. Run the app: streamlit run app.py
