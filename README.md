# Assignment: Capstone Assignment - Section A

**Course:** IIMK's Professional Certificate in Data Science and Artificial Intelligence for Managers  
**Student Name:** Lalit Nayyar  
**Email:** lalitnayyar@gmail.com

---

## 📖 User Guide

### Getting Started
1. **Clone or Download the Project Folder** to your local machine.
2. **Open `amazon_optimised_supply_chain.html`** in any modern web browser to view the interactive report and visuals.
3. **Download and Run the Python Notebook** (`amazon_supply_chain_data_analysis.ipynb`) for hands-on data analysis and to generate your own supply chain visuals.
4. **Add Your Own Visuals:** Export charts from the notebook as PNG files and place them in the `notebook_visuals/` folder to enrich the HTML report.

### Requirements
- Web browser (for HTML report)
- Python 3.8+ (for Jupyter Notebook)
- Kaggle account & API key (for dataset download)
- Required Python packages: pandas, matplotlib, seaborn, plotly, kaggle

---

## ✨ Features & Functionality

### 1. Amazon Optimised Supply Chain HTML Report
- **Professional layout** with Amazon-themed colors and branding
- **Executive Summary** and detailed sections: Market Needs, AI Project Selection, Problem Statement, EDA, ML Model, Data Source, Visual Insights, Market Impact, Business Impact, and more
- **Business-appropriate emojis** and bullet points for clarity
- **References** section with credible sources
- **Section for Python notebook download and sample visuals**

### 2. Python Data Analysis Notebook
- **Automated Kaggle dataset download** (Amazon supply chain data)
- **Exploratory Data Analysis (EDA)**: order trends, fulfillment network, delivery speed, inventory turnover
- **Beautiful, customizable visuals** (line plots, maps, histograms, bar charts)
- **Code blocks for easy extension and experimentation**

### 3. Visuals Integration
- **Notebook-generated charts** can be exported as PNGs and embedded into the HTML report
- **Visual placeholders** included for seamless integration

---

## 🛠️ How to Use

1. **View the HTML Report:**
   - Open `amazon_optimised_supply_chain.html` in your browser for a complete overview.
2. **Analyze Data in Python:**
   - Launch `amazon_supply_chain_data_analysis.ipynb` in Jupyter Notebook or VS Code.
   - Follow the notebook instructions to download the dataset, run EDA, and generate visuals.
3. **Update Visuals:**
   - Save your charts as PNGs (e.g., `order_trends.png`) in the `notebook_visuals/` folder.
   - Refresh the HTML to see your updated visuals.
4. **Customize:**
   - Edit the notebook or HTML sections to tailor the analysis or presentation as needed.

---

## 📑 Detailed Python Notebook Instructions

### 1. `amazon_supply_chain_data_analysis.ipynb`

**Purpose:**
- Analyze Amazon supply chain data, automate Kaggle dataset download, perform EDA, and generate business-ready visuals for your HTML report.

**Step-by-Step Instructions:**
1. **Install Requirements:**
   - Ensure Python 3.8+ is installed.
   - Install required packages: `pip install pandas matplotlib seaborn plotly kaggle`
2. **Kaggle API Setup:**
   - Create a Kaggle account at [kaggle.com](https://www.kaggle.com/).
   - Get your Kaggle API key (`kaggle.json`) from your Kaggle account settings.
   - Place `kaggle.json` in your working directory or configure it as per [Kaggle API docs](https://github.com/Kaggle/kaggle-api#api-credentials).
3. **Download Dataset:**
   - The notebook will run `!kaggle datasets download -d stuti24/amazon-supply-chain-dataset` and unzip the data to a `data/` folder.
4. **Run the Notebook:**
   - Open the notebook in Jupyter or VS Code.
   - Execute all cells sequentially (Cell > Run All).
   - Inspect and modify code blocks as needed for custom analysis.
5. **Key Outputs & Visuals:**
   - Order Volume Trends (line plot)
   - Fulfillment Center Distribution (map)
   - Delivery Speed Distribution (histogram)
   - Inventory Turnover by Product Category (bar plot)
   - All visuals can be saved as PNGs and embedded in your HTML report.

### 2. `netflix_recommendation_engine.ipynb`

**Purpose:**
- Explore and analyze the MovieLens dataset to demonstrate recommendation engine concepts for Netflix.

**Step-by-Step Instructions:**
1. **Install Requirements:**
   - Ensure Python 3.8+ is installed.
   - Install required packages: `pip install pandas matplotlib seaborn kaggle`
2. **Kaggle API Setup:**
   - Create a Kaggle account and set up your API key as described above.
3. **Download Dataset:**
   - The notebook will run `!kaggle datasets download -d grouplens/movielens-20m-dataset --unzip -p ./data` to fetch the MovieLens dataset.
4. **Run the Notebook:**
   - Open in Jupyter or VS Code and execute all cells.
   - Review and modify code for deeper analysis or new recommendation techniques.
5. **Key Outputs & Visuals:**
   - EDA on user/movie/rating distributions
   - Data cleaning and transformation steps
   - Model training and evaluation (if implemented)
   - Visuals: rating histograms, user activity plots, etc.
   - Visuals can be exported as PNGs for presentations or reports.

---

## 📬 Support
If you have questions or need help, please contact: **lalitnayyar@gmail.com**

---

**Enjoy exploring Amazon's supply chain analytics!**
