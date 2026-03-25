# Global Sugar Consumption Dataset & Analysis

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue.svg" alt="Python Version">
  <img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License">
</p>

## 📌 Overview
Welcome to the **Global Sugar Consumption Dataset Analysis**, a rich and insightful technical collection exploring sugar consumption trends across countries from 1960 to 2023. This project aims to facilitate meaningful visualizations, uncover patterns in sugar intake, economic factors, and correlate them with health outcomes worldwide. 

## 🎯 What Problem This Solves
This analysis addresses the growing global health concerns surrounding dietary habits by identifying direct correlations between sugar intake and rising metrics like obesity and diabetes. By analyzing historical trends across different regions and economic brackets, the project provides data-driven evidence that can empower policymakers, health organizations, and researchers to design targeted public health interventions and dietary regulations.

## 📊 Dataset Description
The dataset provided (`Sugar_consumption.xlsx`) includes the following vital metrics and columns:
- **Demographics & Geography**: Country, ISO Code, Continent, Region, Population, Urbanization Rate (%).
- **Economic Indicators**: GDP Per Capita (in USD), Average Retail Price of Sugar Per Kg.
- **Consumption Metrics**: Per Capita Sugar Consumption, Total Sugar Consumption, Processed Food Consumption, Average Daily Sugar Intake.
- **Sugar Sources**: Percentages of sugar sourced from Sugarcane, Beet, High-Fructose Corn Syrup (HFCS), and Other sources.
- **Health Indicators**: Diabetes Prevalence (%), Obesity Rate (%).
- **Trade & Production**: Sugar Imports, Exports, and Sugarcane Production Yield.

## 🚀 Key Features of Analysis
- Visualizes temporal trends in sugar consumption by country or region.
- Explores correlations between sugar intake, health outcomes (e.g., diabetes, obesity), and economic factors (e.g., GDP per capita).
- Analyzes the influence of urbanization and processed food consumption on sugar intake.
- Investigates global sugar trade dynamics.

## ⚙️ Requirements
To run the included analysis and explore the Jupyter Notebook, you need the following dependencies installed. You can install all requirements through the accompanying `requirements.txt`:

```bash
pip install -r requirements.txt
```

**Main Libraries used:**
- `pandas` - For reading Excel data and dataset manipulation.
- `numpy` - For numerical operations.
- `matplotlib` & `seaborn` - For clear and insightful data visualizations.
- `openpyxl` - Required for reading `.xlsx` files.
- `jupyter` - To run the analysis notebook.

## 🛠️ Usage & Getting Started
To get started and run the analysis locally on your machine:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/niraj987/Sugar-Consumption-Analysis.git
   cd Sugar-Consumption-Analysis
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch the analysis notebook:**
   ```bash
   jupyter notebook " SugarConsumption_Dataset.ipynb"
   ```

## 📝 Example Output
The repository contains both data visualizations through HTML dashboard exports (`index.html`, `index2.html`) and an interactive Jupyter Notebook. Ensure your environment covers the requirements above before reproducing the charts!

## 📜 License
This dataset and analysis scripts are licensed under the MIT License. Use it freely for your personal, academic, or professional data science projects.

## 📬 Contact
For questions or suggestions, please feel free to open an issue or contact the maintainer directly at **Kumarniraj11045@gmail.com**.
