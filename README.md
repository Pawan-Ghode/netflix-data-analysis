# Netflix Data Analysis 📊

## 📌 Overview
This project performs **Exploratory Data Analysis (EDA)** on the Netflix dataset to uncover patterns in content distribution, top genres, country trends, and yearly growth.

## 📂 Dataset
- **Source:** [Netflix Movies and TV Shows - Kaggle](https://www.kaggle.com/shivamb/netflix-shows)
- **Size:** 8,807 rows × 12 columns
- **Features:**
  - type (Movie/TV Show)
  - title
  - director
  - cast
  - country
  - date_added
  - release_year
  - rating
  - duration
  - listed_in (Genres)
  - description

## 🛠 Methodology
1. **Data Cleaning**
   - Removed duplicates
   - Filled or dropped missing values
   - Standardized date formats
2. **Exploratory Data Analysis (EDA)**
   - Distribution of Movies vs TV Shows
   - Top content-producing countries
   - Rating distribution
   - Yearly trends in content addition
   - Most popular genres
3. **Insights & Recommendations**
   - Summarized in the **PDF report** (`Netflix_EDA_Report.pdf`)

## 📊 Key Insights
- Movies make up ~70% of Netflix content.
- United States produces the highest number of titles.
- 2019 had the most new content added.
- Popular genres: International Movies, Documentaries, Drama.

## 💻 Tools & Technologies
- Python (Pandas, NumPy)
- Matplotlib, Seaborn
- Google Colab
- GitHub for version control

## 📁 Project Structure
netflix-data-analysis/
│── Netflix_EDA.ipynb          # Jupyter Notebook
│── Netflix_EDA_Report.pdf     # PDF report with graphs & insights
│── README.md                  # Project documentation

## 🚀 How to Run
1. Clone this repo:
   git clone https://github.com/Pawan-Ghode/netflix-data-analysis.git
2. Install dependencies:
   pip install pandas matplotlib seaborn
3. Open `Netflix_EDA.ipynb` in Jupyter or Google Colab.
4. Run all cells.

## ✍ Author
Your Name – Pawan Ghode
