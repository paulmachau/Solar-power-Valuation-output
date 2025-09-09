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

# Data Processing.
This project will include 1 dataset.
* The Raw Data set. Consist of 8761 Rows and 3 columns
* Hours  - Showing the hourly solar generation and Electricity usage in 2020
* Solar_Generation_Kwh - Shows the solar generated on hourly basis in Kwh
* Electricity_usage_kwh - shows the power usage over the whole year 2020
<img width="987" height="525" alt="Screenshot 2025-09-09 2 51 12 PM" src="https://github.com/user-attachments/assets/29a4fd28-9d43-4b76-80c0-fe5782ed4d20" />


# Methodology
* Data Collection: Gather hourly solar generation, electricity usage, and electricity purchase data for the year 2020.

* Data Checks: Ensure data completeness and accuracy. Handle any outliers or missing values.

* Energy Purchase Calculation: Calculate the electricity purchased from the provider based on solar generation, electricity usage, and battery charge levels.

* Excess Solar Electricity Calculation: Calculate excess solar electricity over electricity used, considering the battery charge level cap.
* <img width="938" height="494" alt="Screenshot 2025-09-09 3 16 51 PM" src="https://github.com/user-attachments/assets/9555341d-e347-4743-92a9-c4f618e61008" />


* Monthly Data Analysis: Summarize monthly solar generation, electricity usage, and electricity purchased with and without the battery.
<img width="938" height="381" alt="Screenshot 2025-09-09 3 11 50 PM" src="https://github.com/user-attachments/assets/93fed176-78df-477c-a4d9-934d88f709f7" />

* Scenario Analysis: Project annual savings for 20 years based on different electricity price increase scenarios.

# Modeling
**Scenario 1: Moderate Electricity Tariff Growth**

Annual savings: from USD 1,957 (2022) → USD 4,124 (2041)

NPV: USD 35,800.02

IRR: 15.43%

Payback Period: ~8 years

ROI: ~300%

**Scenario 2: Higher Electricity Tariff Growth**

Annual savings: from USD 1,957 (2022) → USD 6,466 (2041)

NPV: USD 42,031.80

IRR: 16.83%

Payback Period: ~7 years

ROI: ~350%

# Conclusion:
The comprehensive analysis and modeling conducted in this project shed light on the feasibility and potential benefits of integrating solar batteries into the existing solar panel system. 

**Technical Perspective**:
The solar system generates surplus electricity during the day, much of which would otherwise be wasted. The battery allows this excess power to be stored and used in the evening or during cloudy periods, significantly reducing reliance on grid electricity.

**Financial Perspective**:

Under Scenario 1 (moderate tariff growth), the project achieves an NPV of USD 35,800.02, an IRR of 15.43%, and a payback period of 8 years.

Under Scenario 2 (higher tariff growth), the project delivers an NPV of USD 42,031.80, an IRR of 16.83%, and a payback period of 7 years.

Both scenarios exceed the 6% discount rate and deliver an ROI above 300%, proving the project generates substantial long-term value.

# Recommendations:
**Proceed with Battery Integration**

Implement battery storage to capture excess solar generation and reduce grid purchases.

This will improve energy independence and resilience against rising electricity tariffs.

**Prioritize Scenario 2 in Planning**

Given global and local trends of rising energy prices, Scenario 2 is more realistic and should guide investment decisions.

**Plan for Battery Replacement and O&M**

Batteries typically require replacement after 10–12 years depending on usage and degradation.

Allocate a sinking fund for replacement and regular maintenance to sustain system efficiency.

**Conduct Sensitivity Analysis**

Perform additional tests under different assumptions (e.g., slower tariff growth, higher capital cost, or reduced solar output).

This ensures resilience and helps anticipate potential risks.

**Adopt Real-Time Monitoring Systems**

Use smart energy management tools to track battery performance, charging/discharging cycles, and grid usage.
