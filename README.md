# Data-Analysis-using-Python
Electric Vehicle Data Analysis Project 🚗🔋

📌 Overview

This project analyzes a dataset of Electric Vehicles (EVs) to uncover meaningful insights, test hypotheses, and provide actionable recommendations for customers and manufacturers.
It leverages Python, Pandas, NumPy, Matplotlib, Seaborn, and SciPy to explore EV attributes such as price, battery capacity, range, energy consumption, and performance.

The project covers data cleaning, exploration, statistical analysis, visualization, and building a recommendation system.

📂 Dataset
  Source: [FEV-data-Excel.xlsx](https://docs.google.com/spreadsheets/d/17I47pSX87vzBwrJGZvNMNdVv_Jg5pHI9/edit?gid=1403427075#gid=1403427075)
  
  The dataset contains features like:

      Car Full Name, Make, Model,Minimal Price (gross) [PLN],Engine Power [KM], Maximum Torque [Nm],Type of Brakes, Drive Type,Battery Capacity [kWh], Range (WLTP) [km],Dimensions, Weight, Seats, Doors
      Tire Size, Max Speed, Boot Capacity,Acceleration 0-100 kph, Charging Power, Energy Consumption

🛠 Tools & Libraries Used
    Python (Pandas, NumPy, Matplotlib, Seaborn, SciPy)

Jupyter Notebook/Google Colab

 -- Statistical Methods (T-tests, Correlation Analysis)
 -- Visualization (Scatter plots, Box plots, KDE plots)

📊 Project Tasks & Highlights
  1. Filter EVs by Customer Requirements
               -- Budget ≤ 350,000 PLN
               -- Range ≥ 400 km
  Grouped by manufacturer and calculated average battery capacity.
  **Insight**: Tesla and Volkswagen lead in affordable long-range EVs.

2. Outlier Detection in Energy Consumption
   -- Used IQR method on Mean_EC column.
  **Result**: No significant statistical outliers; most EVs consume 13–28 kWh/100 km.

3. Correlation Analysis
   -- Examined relationship between Battery Capacity and Range.
   -- Correlation Coefficient: 0.81 → strong positive relationship.
   -- Visualization: Scatter plot with regression line.

4. EV Recommendation System
  --  Built a Python class to recommend Top 3 EVs based on: Budget,Desired Range,Battery Capacity

5. Hypothesis Testing
  --  Compared average Engine Power between Tesla and Audi using two-sample t-test.

**Result**: No statistically significant difference (p-value = 0.106).

📈 Key Insights :
  --  Tesla offers higher range at competitive prices.
  --  Volkswagen ID.3 Pro S achieves 549 km range on 77 kWh — highly efficient.
  --  Hyundai and Kia deliver good range with smaller batteries in budget segment.
  --  Battery capacity correlates strongly with range, but efficiency matters more at higher capacities.
  -- No extreme energy consumption outliers; most EVs are energy-efficient.

✅ Recommendations
  -- Promote Tesla & VW models for long-range customers.
  -- Market budget-friendly efficient models like VW ID.3 Pro S and Kia e-Niro.
  -- Focus on energy-efficient EVs (< 17 kWh/100 km) for eco-conscious buyers.
  -- Manufacturers should improve efficiency over battery size.
  -- Use battery capacity & range as primary marketing points.

        **This project is part of an academic submission and is for educational purposes only.**
