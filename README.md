# ⚽ FIFA World Cup Data Analysis (1930–2022)

## 📌 Overview
This project performs an exploratory data analysis (EDA) on historical FIFA World Cup data spanning from 1930 to 2022.  
By combining multiple datasets related to matches, tournaments, and FIFA rankings, the project aims to uncover trends, patterns, and insights about team performances and match outcomes across different World Cup editions.

The analysis is implemented in Python using popular data analysis and visualization libraries.

---

## 🎯 Objectives
- Analyze historical FIFA World Cup match data
- Identify dominant teams and performance trends
- Study goal-scoring patterns across tournaments
- Explore the relationship between FIFA rankings and match results
- Visualize insights using statistical plots and charts

---

## 📊 Datasets Used
This project uses the following three datasets:

1. **matches_1930_2022.csv**
   - Contains match-level data from FIFA World Cups (1930–2022)
   - Includes:
     - Home and away teams
     - Match scores and penalties
     - Expected goals (xG)
     - Venue, attendance, and officials
     - Tournament rounds

2. **world_cup.csv**
   - Contains tournament-level information
   - Includes:
     - World Cup year
     - Host country
     - Winning team
     - Runners-up and third-place teams
     - Number of teams and matches

3. **fifa_ranking_2022-10-06.csv**
   - Contains FIFA team rankings
   - Includes:
     - Country rankings
     - Ranking points
     - Confederations
   - Used to analyze the impact of rankings on match outcomes

---

## 🛠️ Tools & Technologies
- Python 3
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 📈 Analysis Performed
- Data cleaning and preprocessing
- Handling missing and inconsistent values
- Exploratory Data Analysis (EDA)
- Team-wise and tournament-wise performance analysis
- Goal distribution and scoring trend analysis
- Correlation analysis using FIFA rankings
- Data visualization using plots and charts

---

## 📂 Project Structure
├── FIFAWC.ipynb
├── matches_1930_2022.csv
├── world_cup.csv
├── fifa_ranking_2022-10-06.csv
└── README.md

---

## ▶️ How to Run the Project
1. Clone the repository:
git clone https://github.com/your-username/fifa-world-cup-analysis.git


2. Install required libraries:
pip install numpy pandas matplotlib


3. Open the notebook:
jupyter notebook FIFAWC.ipynb



---

## 📌 Key Insights
- Certain teams have consistently dominated World Cup history
- Goal-scoring trends vary significantly across eras
- FIFA rankings show a measurable relationship with match outcomes
- Visualization helps reveal long-term historical patterns

(Detailed explanations and results are available inside the notebook.)

---

## 🚀 Future Scope
- Add advanced visualizations using Seaborn or Plotly
- Apply machine learning models for match outcome prediction
- Perform era-wise comparison of World Cups
- Extend the analysis with post-2022 data

---

## 👤 Author
Samyak Gaikwad  
Data Analysis | Machine Learning | Artificial Intelligence