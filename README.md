# U.S. Medical Insurance Cost Analysis

# 📊 Overview

This project provides a detailed exploratory analysis of a real-world dataset containing medical insurance information for individuals in the United States. The goal is to uncover trends and patterns in insurance charges based on factors like age, gender, region, BMI, smoking status, and number of children.

This analysis was implemented using core Python concepts only — no external libraries except csv and pprint — showcasing strong use of lists, dictionaries, loops, and file handling.

# 📂 Project Structure

├── README.md                      # Project documentation

├── insurance.csv                  # Dataset

├── usmedicalinsurance.ipynb        # Jupyter Notebook for full analysis

# 🔍 Data Description

The dataset consists of 1,338 records with the following columns:

age: Age of the insured individual

sex: Gender (male/female)

bmi: Body Mass Index (BMI)

children: Number of dependents

smoker: Whether the individual is a smoker (yes/no)

region: Geographic region (southwest, southeast, northwest, northeast)

charges: Medical insurance cost (USD)

# ⚙️ Features

The notebook analyzes:

✅ Average age, BMI, and insurance charges

✅ Charges comparison: Smokers vs. Non-smokers

✅ Charges segmented by region, gender, children, and age group

✅ BMI vs. Charges correlation (basic method)

✅ Highest and lowest charges

✅ Smoking ratio in the dataset

# 🚀 Getting Started

Clone the repo:

git clone https://github.com/KaushalChandrasekar/us-medical-insurance-analysis.git

Open usmedicalinsurance.ipynb in Jupyter Notebook or run it via VSCode/JupyterLab.

Ensure insurance.csv is in the same directory.

Run all cells to view the analysis report.

# ✅ Why This Project?

This project showcases:

📌 Real-world data analysis using basic Python

📌 Clean, modular code design via class methods

📌 Data storytelling without dependencies

# 🔓 License

This project is released under the MIT License.

# 💡 Future Enhancements

Export summary reports to CSV or JSON

Add charts using matplotlib or seaborn

Predict charges using regression models

⭐ Star this repo if you found it useful — contributions welcome!
