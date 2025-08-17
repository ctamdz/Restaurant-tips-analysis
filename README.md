# Restaurant Tips Analysis

## Project Description
This project analyzes tipping behavior using the **Restaurant Tips dataset**.  
It explores how factors such as gender, smoking status, day of the week, meal time, and party size influence the amount of tips given.  
The project demonstrates how to perform exploratory data analysis (EDA) and create visualizations using Python.

## Dataset Description
- **Source**: [Tips Dataset (CSV)](https://raw.githubusercontent.com/RusAbk/sca_datasets/main/tips.csv)  
- **Origin**: The dataset contains information from **244 restaurant bills**, collected in the US in 1987.  
- **Access**: The dataset can be directly downloaded from the provided GitHub link above.

### Dataset Columns
- `total_bill`: Total bill amount (in USD)  
- `tip`: Tip amount (in USD)  
- `sex`: Gender of the bill payer (Male/Female)  
- `smoker`: Indicates if the party included smokers (Yes/No)  
- `day`: Day of the week (Thur, Fri, Sat, Sun)  
- `time`: Meal time (Lunch or Dinner)  
- `size`: Number of people in the party  

## Main Goals
- Identify **tipping patterns** across customer demographics and dining conditions  
- Compare tipping behaviors by **gender, smoking status, weekday vs. weekend, and meal time**  
- Visualize the results with **histograms, boxplots, and composition plots**  
- Practice statistical analysis and develop insights from real-world data  

## Results Summary
- **Overall Distribution**: Most tips fall between **$1–4**, with a peak around **$2–3**.  
- **Gender**: Men tend to tip slightly higher than women, though the difference is small.  
- **Smoker vs. Non-Smoker**: Smokers show greater variability, with both very low and very high tips.  
- **Weekday vs. Weekend**: Tips are higher on weekends, with more frequent large tips.  
- **Lunch vs. Dinner**: Dinner tips are generally higher and more variable than lunch tips.  
- **Outliers**: High-value tips (up to $10) mostly occur during **dinner and weekends**.  

 Detailed visualizations and step-by-step analysis are available in the file .ipynb above 
