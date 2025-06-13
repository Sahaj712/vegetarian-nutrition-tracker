# vegetarian-nutrition-tracker
Personal vegetarian diet data with 30-day macro analysis for fat loss and protein tracking.

Project Overview
This project documents and analyzes a 30-day personal vegetarian diet with the goal of achieving fat loss and muscle retention. It is structured as a real-world nutrition case study, focusing on how to consistently meet macro goals—especially protein intake—within the constraints of a vegetarian, egg-free diet.

Using structured daily logs of calories, protein, carbohydrates, and fat, this project applies data analysis techniques to evaluate the consistency, adequacy, and optimization of nutrition across different meals and days. The intention is to translate raw dietary patterns into actionable insights that can inform better meal planning, dietary habits, and future automation tools.

Objectives
Log realistic, home-cooked Indian vegetarian meals over a 30-day period

Ensure daily caloric intake falls between 1500 and 1900 kcal

Achieve a minimum daily protein intake of 90–110 grams

Track food intake across four time segments: morning, afternoon, evening, night

Analyze macro breakdowns per meal and per day

Provide a data-backed foundation for a meal recommendation or personalization system

Dataset Description
The dataset contains one row per meal. Each entry includes:

Column	Description
Date	Date of the meal (YYYY-MM-DD)
Meal Time	Meal segment: Morning, Afternoon, Evening, Night
Food Description	Meal name (e.g., "Tofu Bhurji with Roti", "Dal Palak Rice")
Calories	Estimated caloric value of the meal
Protein (g)	Grams of protein in the meal
Carbs (g)	Grams of carbohydrates
Fat (g)	Grams of fat

The values are based on a combination of food label references, recipe estimates, and verified dietary guidelines.

Current Project Status
Component	Status
Structured meal dataset created	Completed
Daily macro calculation and summary	Completed
Exploratory Data Analysis and visualizations	Completed
GitHub repository and documentation	Completed
Streamlit dashboard (interactive frontend)	In Progress
Cost analysis and meal affordability metrics	Planned
Macro-based meal recommendation engine	Planned

Key Insights
The average daily caloric intake remained within the target range of 1500–1900 kcal.

Protein intake consistently met or exceeded the target range of 90–110g on most days.

The macro split generally averaged between 25–30% protein, 40–50% carbohydrates, and 20–25% fat.

Certain meal combinations proved highly effective in hitting nutrition goals, suggesting potential for a personalized meal template system.

Even on lower-calorie days (1000–1200 kcal), protein intake remained sufficient through the use of yogurt, tofu, and soya granules.

Repository Contents
My_30-Day_Diet_Intake.csv — Curated 30-day food log with macro details

EDA_Notebook.ipynb — Jupyter notebook for trend analysis and macro visualization

README.md — Project overview, purpose, and current progress

Future Work
Build and deploy a Streamlit dashboard for interactive visualizations

Integrate cost and affordability metrics to assess budget alignment

Add functionality to generate macro-balanced meal plans based on user preferences

Expand the dataset to 60+ days and include body metrics (e.g., weight, energy levels)

Collaborate with nutrition professionals for validation and domain alignment
