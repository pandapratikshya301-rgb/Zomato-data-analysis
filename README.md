#Bangalore Zomato Restaurant Data Analysis

A complete exploratory data analysis project on Zomato restaurant data focused on understanding customer preferences, cuisine trends, pricing behavior, and factors affecting restaurant ratings using Python.
This project was developed as part of my learning and practical exposure to real-world data analysis workflows including data cleaning, visualization, insight extraction, and business recommendation generation.

## Project Objective

The objective of this project is to perform exploratory data analysis on restaurant data and extract meaningful insights related to:
- Restaurant ratings
- Popular cuisines
- Restaurant pricing
- Customer reviews
- Location trends

The project also aims to provide business recommendations based on the analysis.

## Dataset

Source: https://www.kaggle.com/datasets/bhanupratapbiswas/zomato

The dataset includes information such as:
- Restaurant names
- Ratings
- Votes
- Cost for two people
- Cuisines
- Locations
- Online ordering availability
- Table booking availability
- Customer reviews

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- WordCloud
- Jupyter Notebook

# Steps Performed in the Project

## 1. Data Cleaning and Preprocessing

- Removed unnecessary columns
- Handled missing values
- Cleaned text-based columns
- Converted ratings into numerical format
- Processed pricing-related fields
- Removed duplicate entries

## 2. Exploratory Data Analysis

The following analyses were performed:

- Rating distribution analysis
- Cuisine popularity analysis
- Location-based restaurant analysis
- Price vs rating comparison
- Online order analysis
- Table booking analysis
- Customer review analysis using WordCloud

# Visualizations

## Cuisine Popularity Analysis
<img width="1243" height="641" alt="Screenshot 2026-05-04 152319" src="https://github.com/user-attachments/assets/d296db63-2266-4257-b1e4-2a7a7209cfe8" />

## Ratings Distribution
<img width="931" height="583" alt="Screenshot 2026-05-04 152622" src="https://github.com/user-attachments/assets/5b56389a-cb8c-4229-8947-2ea126b2fee1" />

## Price vs Rating Analysis
<img width="228" height="282" alt="Screenshot 2026-05-04 152937" src="https://github.com/user-attachments/assets/140211a7-8a62-4bd0-9f29-f0332677d6d6" />

## Restaurant Location Heatmap
<img width="1231" height="676" alt="Screenshot 2026-05-04 153231" src="https://github.com/user-attachments/assets/daf1a19b-331e-4d53-9880-e82d086e6813" />

## Customer Review WordCloud
<img width="983" height="532" alt="Screenshot 2026-05-04 163213" src="https://github.com/user-attachments/assets/5ee9e8c9-263c-465e-a8d1-538eeda3e81e" />


## Key Insights
1. Certain cuisines consistently receive higher ratings compared to others.
2. Restaurants located in high-density urban areas attract more customer engagement.
3. Mid-range restaurants often perform competitively against premium restaurants.
4. Positive customer sentiment strongly correlates with higher ratings.
5. Restaurants offering online ordering tend to receive better customer interaction.

# Business Recommendations
Based on the analysis, the following recommendations can be made:
1.AI-Driven "Skill-Match" Partnership Engine
2."Data-to-Portfolio" Content Pipeline
3.Sentiment-Driven Content Improvement
4.Industry Capstone Sponsorships
5.Gamified "Code-Streak" Engagement

# Project Highlights
✔ Performed complete data cleaning and preprocessing
✔ Conducted exploratory data analysis on restaurant trends
✔ Built multiple visualizations for better insight interpretation
✔ Generated business-oriented recommendations from the dataset
✔ Applied review text analysis using WordCloud visualization

zomato-data-analysis/
│
├── data/
│   └── zomato.csv
│
├── images/
│   ├── cuisine_chart.png
│   ├── heatmap.png
│   ├── price_vs_rating.png
│   ├── rating_distribution.png
|   └── wordcloud.png
│
├── notebook/
│   └── Zomato.ipynb
│
├── report/
│   └── Zomato_Report.pdf
│
├── README.md
├── requirements.txt
└── .gitignore

# How to Run the Project

Follow the steps below to run this project on your system.

---

## 1. Clone the Repository

```bash
git clone https://github.com/yourusername/zomato-data-analysis.git
```
---

## 2. Navigate to the Project Folder

```bash
cd zomato-data-analysis
```

---

## 3. Install Required Libraries

Make sure Python is installed on your system.

Install all dependencies using:

```bash
pip install -r requirements.txt
``` 
---

## 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook file:

```text
notebook/Zomato.ipynb
```
Run all cells sequentially to reproduce the analysis and visualizations.

# Future Improvements

- Build a restaurant recommendation system
- Perform sentiment analysis on customer reviews
- Develop an interactive dashboard using Streamlit or Power BI
- Apply machine learning models for rating prediction

---

# Learning Outcome

Through this project, I gained practical experience in:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Data visualization
- Insight extraction
- Business understanding from datasets
- Working with real-world restaurant data

This project helped me improve my understanding of how data analysis can support decision-making in the food and restaurant industry.

---

# Author

Pratikshya Panda
B.Tech Student | Data Analysis Enthusiast

---

# License
This project is created for educational and learning purposes.
