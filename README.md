# 🎬 Netflix Dataset Analysis

**AICTE VOIS Internship Project | October 2025**

This project was developed as part of the **AICTE VOIS (Vodafone Intelligent Solutions) Internship**, focusing on **data analytics and visualization** using real-world datasets.
The analysis explores the Netflix Movies and TV Shows dataset to uncover insights about content distribution, genre preferences, country contributions, and release trends.

---

### 📁 Dataset Information

The dataset contains the following columns:

| Column Name  | Description                             |
| ------------ | --------------------------------------- |
| Show_Id      | Unique ID for each show                 |
| Category     | Type of content (Movie / TV Show)       |
| Title        | Title of the show                       |
| Director     | Director of the show                    |
| Cast         | Lead actors                             |
| Country      | Country of origin                       |
| Release_Date | Date when released on Netflix           |
| Rating       | Audience rating (e.g., PG, R, TV-MA)    |
| Duration     | Duration (minutes or number of seasons) |
| Type         | Genre or show type                      |
| Description  | Short summary or plot                   |

---

### 🎯 Project Objectives

* Analyze the **distribution between Movies and TV Shows**
* Identify **genre trends** across Netflix’s global catalog
* Explore **country-wise production patterns**
* Visualize **content growth trends over time**

---

### 🧩 Tools & Technologies

| Tool           | Purpose                     |
| -------------- | --------------------------- |
| **Python**     | Data analysis and scripting |
| **Pandas**     | Data manipulation           |
| **Matplotlib** | Visualization               |
| **Seaborn**    | Advanced data visualization |

Install dependencies:

```bash
pip install pandas matplotlib seaborn
```

---

### 🚀 How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/<your-username>/Netflix-Data-Analysis.git
   cd Netflix-Data-Analysis
   ```

2. Open the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

3. Run all cells in `Netflix_Analysis.ipynb`

---

### 📊 Visual Analysis

#### 1️⃣ Movies vs TV Shows

Bar chart comparing total counts of Movies and TV Shows.

#### 2️⃣ Genre Trends

Keyword-based analysis from show descriptions to determine top genres.

#### 3️⃣ Country Analysis

Top 10 countries producing Netflix titles.

#### 4️⃣ Time Trend Analysis

Year-wise trend showing growth in Netflix releases over time.

---

### ⚙️ Optional Data Cleaning

To ensure accurate results:

```python
df.drop_duplicates(inplace=True)
df.fillna("Unknown", inplace=True)
```

---

### 📈 Key Insights

* Netflix features **more Movies than TV Shows**.
* **Drama** and **Comedy** dominate the content library.
* **United States** and **India** are leading content producers.
* Significant content growth observed **after 2015**, reflecting Netflix’s global expansion.

---

