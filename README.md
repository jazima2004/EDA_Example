# EDA_Example
This project is to showcase my  skills in exploratory data analysis:
---

## 🗂️ **1. Data Loading**

* **Imported necessary libraries**: `pandas`, `numpy`, `seaborn`, `matplotlib` for data manipulation and visualization.
* **Loaded the dataset** from CSV file using `pd.read_csv`.
* **Previewed the data** using `head()` and `tail()` to understand its structure.

---

## 🧼 **2. Data Cleaning**

* **Inspected data types** using `df.dtypes` to distinguish between categorical and numerical features.
* **Checked for missing values** using `df.isnull().sum()` and visualized them with a seaborn heatmap.
* **Dropped rows with missing data** using `df.dropna(inplace=True)` to clean the dataset for analysis.

---

## 🛠️ **3. Feature Engineering**

* **Label encoded the 'type' column** (Movie/TV Show) using `LabelEncoder`, creating a new binary column `show_type`.
* **Extracted duration values**:

  * For movies, extracted minutes from the “duration” column.
  * For TV shows, extracted number of seasons from the “duration” text.
* These steps converted string-based durations into usable numerical data for visualization and correlation.

---

## 📊 **4. Univariate Analysis**

* **Content Ratings**: Identified most common ratings like `TV-MA`, `PG-13`, etc., and plotted a bar chart.
* **Countries**: Plotted top 10 countries producing Netflix content.
* **Content Type**: Bar chart comparing the number of Movies vs TV Shows.
* **Release Year**: Showed top release years to spot trends over time.
* **Directors**: Top 5 directors were visualized to show most frequent contributors.
* **Genres**: Used the `listed_in` column to show most common genres via horizontal bar plot.
* **Durations**: Top 10 durations were visualized for content length overview.

---

## 📝 **5. Text Analysis**

* **Word Cloud**: Generated a word cloud from the `title` column to highlight frequent words used in Netflix titles.

---

## 📈 **6. Bivariate & Distribution Analysis**

* **Movie Duration Histogram**: Showed how movie durations vary, highlighting common length intervals.
* **TV Shows by Seasons**: Bar chart showing how many shows have 1, 2, 3... seasons.

---

## 🔗 **7. Correlation Analysis**

* **Correlation Heatmap**: Displayed relationships between numerical features like `show_type` and durations.

---


