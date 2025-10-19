# Netflix-Data-Analysis
This project is a data-driven analysis of IMDb movie ratings. It leverages Python's data stack—using Pandas to load, clean, and wrangle the large dataset. Key insights are uncovered using Matplotlib and Seaborn to create powerful visualizations of rating trends by genre, correlations, and changes over the years.

## 🚀 Project Overview

The main objective is to perform a full Exploratory Data Analysis (EDA) and answer key questions:
* What is the overall distribution of movie ratings?
* How have average movie ratings changed over the decades?
* Which movie genres (e.g., Action, Drama, Sci-Fi) consistently receive the highest ratings?
* Is there a correlation between a movie's duration (runtime) and its rating?
* What is the relationship between the number of votes a movie gets and its final score?

## 📊 Dataset

This project uses the **IMDb movies extensive dataset** from Kaggle.
* **Source:** [Kaggle Dataset Link](https://www.kaggle.com/datasets/stefanoleone/imdb-movies-extensive-dataset)
* **Note:** The raw `.csv` data file is **not** included in this repository (it's over 1.5GB). It is listed in the `.gitignore` file. To run this project, please download the dataset from the link above and place it in the root directory.

## 🛠️ Tools and Libraries

* **Language:** Python 3.x
* **Libraries:**
    * **Pandas:** For data loading, manipulation, and cleaning.
    * **NumPy:** For numerical operations.
    * **Matplotlib & Seaborn:** For creating all static visualizations.
* **Environment:** Google Colab (Jupyter Notebook)

## 📈 Key Visualizations & Findings



### 1. Distribution of Movie Ratings

* **Finding:** The ratings follow a left-skewed normal distribution, with a clear mean around 5.8 and a median of 6.0.

### 2. Average Rating Over Time

* **Finding:** There appears to be a slight downward trend in average movie ratings from 1960 to the present day.

### 3. Top Genres by Average Rating

* **Finding:** Niche genres like 'Documentary' and 'Biography' consistently score the highest, while 'Horror' scores the lowest among common genres.

## 🏁 How to Run
1.  Clone this repository: `git clone [your-repo-url]`
2.  Download the `IMDb movies.csv` file from the Kaggle link above.
3.  Place the `.csv` file in the cloned project's root folder.
4.  Open the `Movie-Analysis-Notebook.ipynb` in Google Colab or a local Jupyter Notebook instance.
5.  Run all cells sequentially.

 ## Problem statement
Raw movie data, like the IMDb dataset, is vast, messy, and filled with unstructured information. It's impossible to draw any meaningful conclusions from it in its raw state. Key information is often hidden behind inconsistent formatting, missing values, and complex text fields.

This project solves that problem by:

Taming the Chaos: Applying a rigorous cleaning pipeline to handle missing data, convert data types, and standardize information.

Uncovering Hidden Insights: Transforming the raw, cluttered data into clear and actionable insights.
