# Solar Energy and Battery Integration Feasibility Analysis.


# Business Overview:

In a world where sustainable energy solutions are becoming increasingly important, businesses and individuals are exploring ways to harness solar energy and reduce reliance on conventional electricity sources. Solar panels are a popular choice for generating clean energy, but the intermittent nature of sunlight requires effective energy storage solutions to ensure consistent power supply. This feasibility analysis project aims to assess the financial viability of integrating battery systems with existing solar panels, taking into account varying electricity prices and potential savings.

# Problem Statement:

The main challenge addressed by this project is to determine whether installing battery systems alongside solar panels is financially viable in the long term. The project seeks to answer questions such as:

* What are the potential energy savings from using stored solar energy during non-sunny hours?
* How do different electricity price increase scenarios impact the financial returns of the investment?
* Can the initial cost of battery installation be justified by the expected energy savings over the years?

# Objective:
The objective of this project is to provide businesses and individuals with actionable insights into the financial viability of adopting battery systems to complement their solar energy generation efforts. By quantifying potential energy savings and considering different electricity price scenarios, stakeholders can make informed decisions about the adoption of sustainable energy solutions while contributing to environmental conservation and cost reduction.


# Methodology
* Data Collection: Gather hourly solar generation, electricity usage, and electricity purchase data for the year 2020.

* Data Checks: Ensure data completeness and accuracy. Handle any outliers or missing values.

* Energy Purchase Calculation: Calculate the electricity purchased from the provider based on solar generation, electricity usage, and battery charge levels.

* Excess Solar Electricity Calculation: Calculate excess solar electricity over electricity used, considering the battery charge level cap.

* Monthly Data Analysis: Summarize monthly solar generation, electricity usage, and electricity purchased with and without the battery.

* Scenario Analysis: Project annual savings for 20 years based on different electricity price increase scenarios.

* NPV and IRR Calculation: Calculate NPV and IRR for both scenarios.

* Visualization: Create visualizations for hourly, monthly, and annual energy metrics.

# Data Processing.
This project will include 1 dataset.
* The Raw Data set. Consist of 8761 Rows and 3 columns
* Hours  - Showing the hourly solar generation and Electricity usage in 2020
* Solar_Generation_Kwh - Shows the solar generated on hourly basis in Kwh
* Electricity_usage_kwh - shows the power usage over the whole year 2020

# Modeling
In the  project, the primary focus was on financial analysis and feasibility calculations rather than complex machine learning or statistical modeling. Therefore, traditional statistical or machine learning models were not used. Instead, the analysis involved calculations, projections, and financial metrics to assess the viability of integrating solar batteries.

## The project utilized various calculations and methodologies to achieve its objectives, such as:



### Data Preprocessing and Checks:

* Ensured data completeness and correctness for analysis.
  
### Energy Calculations:

* Calculated electricity purchase, excess solar electricity, and related metrics for each hour in 2020.
  
### Scenario Analysis:
Projected annual savings for 20 years (2022-2041) under Scenario 1 and Scenario 2.
* Scenario 1: Savings range from 1957.37 (2022) to 4123.89 (2041).
* Scenario 2: Savings range from 1957.37 (2022) to 6465.98 (2041).
  
### Net Present Value (NPV) Calculation:
Calculated NPV for both scenarios:
* Scenario 1: Total NPV - 35800.02
* Scenario 2: Total NPV - 42031.80
  
### Internal Rate of Return (IRR) Calculation:
Calculated IRR for both scenarios:
* Scenario 1: IRR - 0.1543
* Scenario 2: IRR - 0.1683
  
### Data Visualization:
* Created monthly charts showing solar generation, electricity usage, and electricity purchased for each scenario.

# Conclusion:
The comprehensive analysis and modeling conducted in this project shed light on the feasibility and potential benefits of integrating solar batteries into the existing solar panel system. By thoroughly processing the provided data, we were able to project energy consumption, solar generation, and electricity purchase patterns. This information served as the foundation for exploring two distinct scenarios with varying electricity price increase assumptions.

# Recommendations:
Based on the results and insights gathered from the project, the following recommendations can be made:

* Scenario Comparison: 
Both scenarios were evaluated for their annual savings, Net Present Value (NPV), and Internal Rate of Return (IRR). Scenario 2 demonstrated slightly higher annual savings, a higher NPV, and a marginally better IRR. Therefore, stakeholders should consider Scenario 2 as the more financially attractive option.

* Long-Term Perspective:
The projections for 20 years indicated that the benefits of integrating solar batteries extend into the future. This makes the investment in solar batteries a sound long-term decision, especially considering rising electricity prices.

* Risk Mitigation:
Stakeholders should be aware of the assumptions made in the scenarios, particularly regarding electricity price increases. As electricity prices are subject to market dynamics, a sensitivity analysis could provide insights into potential variations in the results.

* Flexibility and Adaptability:
  As technology and energy markets evolve, it's recommended that stakeholders continuously monitor the developments in the renewable energy sector. This will ensure that the chosen solution remains aligned with industry trends and future energy needs.

* Monitoring and Optimization: 
Implementing the chosen scenario should be accompanied by real-time monitoring of system performance. Regular optimization and maintenance of the solar battery system can ensure that the projected benefits are realized and maximized.
