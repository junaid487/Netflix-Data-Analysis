# Netflix Content Strategy: Exploratory Data Analysis 🎬

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data_Manipulation-150458.svg)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-444444.svg)

## Project Overview
This project performs an in-depth **Exploratory Data Analysis (EDA)** on the Netflix titles dataset. The goal is to understand how Netflix has evolved its library over the years, which markets it dominates, and how it segments its content for different audience demographics.

## Key Business Questions Answered
* **Content Mix:** What is the ratio between Movies and TV Shows?
* **Global Footprint:** Which countries are the top producers of Netflix content?
* **Audience Targeting:** Does Netflix prioritize Kids, Teens, or Adult content?
* **Growth Trends:** How has the rate of content addition changed since 2015?
* **Genre Analysis:** What are the most popular genres across different regions?

## Technical Workflow
1. **Data Cleaning:** Handled missing values in critical columns (`director`, `cast`, `country`) and standardized date formats.
2. **Feature Engineering:** Extracted `Year`, `Month`, and `Weekday` from release dates to analyze scheduling patterns.
3. **Data Transformation:** Used advanced "Explosion" techniques to handle multi-valued columns (e.g., titles with multiple genres or countries) for granular analysis.
4. **Visualization:** Utilized `Seaborn` and `Matplotlib` to create intuitive, publication-quality charts.

## Sample Insights
* **Adult-Oriented:** A significant majority of Netflix's library is geared toward mature audiences.
* **USA & India Lead:** The United States and India remain the primary content hubs, though international "Originals" are growing rapidly.
* **The "Friday" Effect:** Most content is added on Fridays, likely to capture weekend viewership.

## Repository Structure
* `Netflix.ipynb`: The main technical notebook containing cleaning, analysis, and visualizations.
* `netflix.csv`: The raw dataset used for the analysis.

## Requirements
```bash
pip install pandas matplotlib seaborn numpy
