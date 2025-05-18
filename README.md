# Netflix Recommendation Engine

**Course:** IIMK's Professional Certificate in Data Science and Artificial Intelligence for Managers  
**Student Name:** Lalit Nayyar  
**Email:** lalitnayyar@gmail.com

---

## 📖 User Guide

### Getting Started
1. **Clone or Download the Project Folder** to your local machine.
2. **Open `netflix_recommendation_engine.html`** in any modern web browser to view the interactive report and visuals.
3. **Download and Run the Python Notebook** (`netflix_recommendation_engine.ipynb`) for hands-on data analysis, model building, and to generate your own visuals.
4. **Add Your Own Visuals:** Export charts from the notebook as PNG files and place them in the project folder to enrich the HTML report.

### Requirements
- Web browser (for HTML report)
- Python 3.8+ (for Jupyter Notebook)
- Required Python packages: pandas, numpy, matplotlib, seaborn, scikit-learn, surprise

---

## 🌐 Public Web Access (GitHub Pages)

You can view the Netflix Recommendation Engine HTML report directly on the web:

**Live Web Link:**
https://lalitnayyar.github.io/iimkassignment6/

#### How to Enable/Update GitHub Pages
1. Go to your repository settings: https://github.com/lalitnayyar/iimkassignment6/settings/pages
2. Under **Source**, select the `release-netflix` branch and `/ (root)` folder.
3. Save your changes. GitHub will build and publish your site within a minute.
4. Share the above link for public access to your Netflix Recommendation Engine report!

#### Release Branch
- All Netflix artifacts (`index.html`, `netflix_recommendation_engine.html`, `.ipynb`, and visuals) are available in the `release-netflix` branch.
- The HTML report is now accessible as `index.html` for easy web viewing.

---

## ✨ Features & Functionality

### 1. Netflix Recommendation Engine HTML Report
- **Professional, modern layout** with Netflix-themed colors and branding
- **Executive Summary** and detailed sections: Market Needs, AI Project Selection, Problem Statement, EDA, ML Model, Data Source, Visual Insights, Market Impact, Business Impact, and more
- **Business-appropriate emojis** and bullet points for clarity
- **Download link for the Python notebook** directly in the report
- **Interactive Table of Contents** with links to all major sections and notebook insights
- **Visually distinct cards** for each data insight and model result

### 2. Python Data Analysis Notebook
- **Exploratory Data Analysis (EDA):** User, movie, and rating distributions; summary statistics; genre and temporal trends
- **Collaborative Filtering Model:** SVD-based recommendation, sample predictions, RMSE evaluation
- **Alternative Approaches:** Top-N recommendations, genre-based trends, user activity analysis
- **Beautiful, customizable visuals** (histograms, bar charts, user activity plots, temporal patterns)
- **Code blocks for easy extension and experimentation**

### 3. Visuals Integration
- **Notebook-generated charts** can be exported as PNGs and referenced in the HTML report
- **Visual placeholders** included for seamless integration

---

## 🛠️ How to Use

1. **View the HTML Report:**
   - Open `netflix_recommendation_engine.html` in your browser for a complete overview and interactive navigation.
2. **Analyze Data in Python:**
   - Launch `netflix_recommendation_engine.ipynb` in Jupyter Notebook or compatible environment.
   - Follow the notebook instructions to load the MovieLens dataset, run EDA, build models, and generate visuals.
3. **Update Visuals:**
   - Save your charts as PNGs (e.g., `visual_rating_distribution.png`) in the project folder.
   - Refresh the HTML to see your updated visuals.
4. **Customize:**
   - Edit the notebook or HTML sections to tailor the analysis or presentation as needed.

---

## 🛠️ Troubleshooting

- **HTML Report Not Displaying Properly:**
  - Ensure you are opening the file in a modern web browser (Chrome, Edge, Firefox, Safari).
  - Check that all image/chart files referenced in the HTML are present in the project folder.

- **Notebook Fails to Run:**
  - Make sure all required Python packages are installed (see Requirements above). Use `pip install package_name` as needed.
  - If dataset download fails, check your internet connection or download the MovieLens dataset manually from [GroupLens](https://grouplens.org/datasets/movielens/20m/).

- **Visuals Not Updating in HTML:**
  - After saving new charts from the notebook, ensure the filenames in the HTML match your saved files.
  - Refresh the browser cache (Ctrl+F5) to see updated visuals.

- **Model Results Not as Expected:**
  - Double-check data preprocessing steps in the notebook.
  - Experiment with different model parameters or algorithms.

---

For further questions, contact Lalit Nayyar at lalitnayyar@gmail.com.


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

## 🛠️ Troubleshooting Guide: Netflix Recommendation Engine & scikit-surprise

If you encounter issues while running the collaborative filtering model in the Netflix notebook, refer to the following solutions:

### Common Errors & Solutions

**1. ModuleNotFoundError: No module named 'surprise'**
- This error means the `scikit-surprise` package is not installed.
- Solution: Install it using the command:
  ```bash
  pip install scikit-surprise
  ```

**2. Microsoft Visual C++ 14.0 or greater is required**
- This error occurs during installation of `scikit-surprise` on Windows, as it needs C++ build tools to compile some components.
- Solution:
  1. Download and install [Microsoft C++ Build Tools](https://visualstudio.microsoft.com/visual-cpp-build-tools/).
  2. During installation, select the "Desktop development with C++" workload.
  3. Restart your computer if prompted.
  4. Run the install command again:
     ```bash
     pip install scikit-surprise
     ```

**3. Still Facing Issues?**
- Try updating pip:
  ```bash
  python -m pip install --upgrade pip
  ```
- Ensure you are using a compatible Python version (3.8+ is recommended).

### Alternative Approach (No scikit-surprise Required)
If you cannot install `scikit-surprise`, you can implement a simple collaborative filtering method using only `pandas` and `sklearn`:

```python
import pandas as pd
import numpy as np
from sklearn.metrics.pairwise import cosine_similarity

# Assume ratings is your DataFrame with columns: userId, movieId, rating
user_movie_matrix = ratings.pivot_table(index='userId', columns='movieId', values='rating').fillna(0)
user_similarity = cosine_similarity(user_movie_matrix)
user_similarity_df = pd.DataFrame(user_similarity, index=user_movie_matrix.index, columns=user_movie_matrix.index)

# Example: Find top 5 similar users to user 1
top_similar_users = user_similarity_df.loc[1].sort_values(ascending=False)[1:6]
print("Top 5 users similar to user 1:")
print(top_similar_users)
```

This approach provides basic collaborative filtering functionality without external dependencies.

### General Tips
- Always restart your notebook/kernel after installing new packages.
- If you get persistent errors, consider creating a fresh virtual environment.
- For further help, check [scikit-surprise documentation](https://surprise.readthedocs.io/en/stable/) or contact the course support.

---

---

## 📬 Support
If you have questions or need help, please contact: **lalitnayyar@gmail.com**

---

**Enjoy exploring Amazon's supply chain analytics!**
