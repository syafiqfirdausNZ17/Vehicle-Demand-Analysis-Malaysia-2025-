# 🚗 Vehicle Demand Analysis & Forecasting Report  
## Malaysia Automotive Market Intelligence (2025)

---

# 1. Introduction

The Malaysian automotive industry is undergoing structural shifts driven by evolving consumer preferences, regional demand concentration, and early-stage electric vehicle (EV) adoption.

This project develops a **full Market Intelligence & Forecasting System** using vehicle registration data from Department Of Statistics Malaysia to:

- Analyze historical demand patterns
- Identify high-performing brands and vehicle segments
- Forecast future market behavior
- Generate AI-driven strategic recommendations

Unlike traditional dashboards, this project integrates:

- Descriptive analytics  
- Predictive modeling  
- Forecast validation  
- Prescriptive business insights  

The outcome is a **decision-support framework** suitable for automotive distributors, manufacturers, and strategy teams.

---

# 2. Data Overview & Preparation

## 2.1 Dataset Description

The dataset contains vehicle registration records across Malaysia, including:

- Registration Month
- Maker (Brand)
- Model
- Vehicle Type (SUV, Sedan, etc.)
- Colour
- EV vs Non-EV
- State (Geographic location)

Each row represents a vehicle registration event.

---

## 2.2 Data Cleaning & Transformation

Data engineering steps performed:

- Date parsing and time-series formatting
- Aggregation into monthly demand counts
- Grouping by maker, model, type, colour, and state
- Preparation for forecasting models

This ensured consistency and time-series compatibility.

---

# 3. Descriptive Market Analysis (What Is Happening?)

---

## 3.1 Overall Market Trend

### Objective:
To understand total vehicle registration trends over time.

![total vehicle registration trends over time](Charts/Total_Vehicle_Registration_Over_Time.png)

### Key Insights:
- Identify growth or contraction periods
- Detect seasonality patterns
- Establish baseline demand behavior

Business Interpretation:
This defines overall market momentum and macro demand conditions.

---

## 3.2 Brand / Maker Analysis

### Objective:
To determine brand dominance and competitive landscape.

![Maker Monthly Trend](Charts/Market_Share_By_Maker.png)
![Top Makers by Total Registrations](Charts/Top_5_Maker_Vehicle_Demand_Trend.png) 


### Key Insights:
- Market share concentration
- Leading and emerging brands
- Brand performance volatility

Business Interpretation:
Helps distributors prioritize partnerships and production allocation.

---

## 3.3 Model-Level Demand Analysis

### Objective:
To identify high-performing vehicle models.

![Top Models by Registration](Charts/Top_20_Car_Models_Demand.png)


### Key Insights:
- Best-selling models
- Stable vs trending models
- Model lifecycle signals

Business Interpretation:
Supports inventory stocking and marketing focus decisions.

---

## 3.4 Vehicle Type Analysis

### Objective:
To analyze demand by vehicle segment.

![Vehicle Type Distribution](Charts/Total_Vehicle_Registration_By_Type.png)
![Monthly Trend by Type](Charts/Vehicle_Type_Demand_Recent_Month.png)  

### Key Insights:
- SUV vs Sedan dominance
- Segment growth patterns
- Consumer preference shift

Business Interpretation:
Guides product development and segment expansion strategy.

---

## 3.5 Electric Vehicle (EV) Analysis

### Objective:
To assess EV adoption trajectory.

![ EV vs Non-EV Trend](Charts/EV_Adoption_Trend.png)

### Key Insights:
- EV growth rate
- Market penetration trend
- Transition stage of electrification

Business Interpretation:
Determines readiness for EV infrastructure investment and strategy.

---

## 3.6 Colour Preference Analysis

### Objective:
To understand consumer aesthetic preferences.

![Most Popular Vehicle Colours](Charts/Vehicle_Colour_Market_Composition.png)  


### Key Insights:
- Dominant colour categories
- Stability of colour preference
- Emerging shifts

Business Interpretation:
Optimizes manufacturing mix and dealership stock composition.

---

## 3.7 Geographic (State-Level) Analysis

### Objective:
To analyze regional demand concentration.

![Demand by State](Charts/Top_States_By_Vehicle_Demand.png) 
![State Monthly Trend](Charts/State_Market_Share.png)

### Key Insights:
- High-demand regions
- Regional disparities
- Potential expansion markets

Business Interpretation:
Supports dealership expansion and regional marketing allocation.

---

# 4. Predictive Analytics (What Will Happen?)

Time-series forecasting models were applied to project future demand.

---

## 4.1 Total Market Forecast

![Forecasted Total Vehicle Demand](Charts/Market_Demand_Forecast.png)
![Forecasted Total Vehicle Growth Demand](Charts/Vehicle_Market_Growth_Forecast.png)

Insights:
- Projected growth trajectory
- Confidence intervals
- Expected market size

Business Impact:
Supports production planning and capacity forecasting.

---

## 4.2 Forecast: Top Makers

![Maker-Level Forecasts](Charts/Top_5_Makers_Demand_Forecast.png)

Insights:
- Future brand dominance
- Competitive shifts
- Brand-specific growth expectations

Business Impact:
Strategic supplier and partnership decisions.

---

## 4.3 Forecast: Top Models

![Model Forecast Results](Charts/Top_20_Car_Models_Demand_Forecast.png)

Insights:
- Future best-selling models
- Model demand stability
- High-growth model identification

Business Impact:
Inventory prioritization and pricing strategy.

---

## 4.4 Forecast: Vehicle Type

![Segment-Level Forecast](Charts/Vehicle_Type_Demand_Forecast.png)

Insights:
- SUV growth sustainability
- Sedan recovery potential
- Emerging segment patterns

Business Impact:
Long-term product mix strategy.

---

## 4.5 Forecast: Colour Preference

![Colour Demand Forecast](Charts/Colour_Preference_Forecast.png)

Insights:
- Stability of dominant colours
- Emerging preference signals

Business Impact:
Manufacturing color allocation planning.

---

## 4.6 Forecast: State Demand

![State-Level Forecast](Charts/State_Demand_Forecast.png)

Insights:
- Future regional hotspots
- Growth states vs stagnant states

Business Impact:
Expansion roadmap and dealership placement.

---

# 5. Model Validation & Reliability

To ensure forecast credibility:

- Train-test split backtesting
- MAPE (Mean Absolute Percentage Error)
- Reliability scoring
- Confidence intervals

![Forecast vs Actual (Backtest)](Charts/Forecast_With_Confidence_Interval.png)

Result:
MAE  : 261.95
RMSE : 324.03
MAPE : 20.64%

Forecast performance is measurable and quantifiable, not speculative.

This enhances decision confidence.

---

# 6. AI-Driven Market Intelligence Engine

Forecast outputs were translated into strategic signals.

Components include:

- Opportunity scoring by state
- Segment growth ranking
- High-demand model identification
- EV readiness assessment

![Opportunity scoring by state](Charts/Malaysia_Market_Opportunity_Map.png)

This transforms analysis into **actionable recommendations**.

---

# 7. Strategic Business Recommendations

Based on full analysis:

### 1. Geographic Expansion
Focus expansion in high-growth states identified in forecast.

### 2. Segment Prioritization
Increase SUV allocation if growth trend persists.

### 3. Model Stocking Strategy
Prioritize top forecasted models for inventory efficiency.

### 4. EV Strategic Planning
Gradually increase EV portfolio in states with rising adoption.

### 5. Colour Optimization
Align stock composition with dominant consumer preferences.

---

# 8. Conclusion

This project demonstrates the integration of:

- Data engineering
- Market analytics
- Forecast modeling
- Business strategy translation

It moves from:

Raw Data → Insights → Forecast → Strategy

The framework can be extended into a live dashboard or automated decision-support system.

---

# 9. Tools & Technologies

- Python
- Pandas
- Matplotlib / Seaborn
- Time-Series Forecasting Models
- Statistical Validation Techniques

---

# Author

Syafiq Firdaus  
Data Science | Market Intelligence | AI Forecasting
