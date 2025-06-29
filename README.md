# Titanic-Crash-Analysis

## 📌 Table of Contents
1.	Project Objective
2.	Dataset Details
3.	Tools Used
4.	Data Cleaning
5.	Data Transformation
6.	Exploratory Analysis
7.	Key Insights with Implications
8.	Visualizations
9.	Observations
10.	Recommendations

## 🎯 Project Objective
To analyze the Titanic passenger dataset and develop an interactive dashboard that helps uncover critical patterns in survival outcomes based on demographic, class, Fare, and boarding information. The final dashboard aims to support historical safety assessments and demonstrate data storytelling.

## 📁 Dataset Details
•	Total Records: 1,309 passengers
•	Source: Titanic public dataset (based on real passenger data)
•	Key Fields:
o	Passenger Class (Pclass)
o	Gender
o	Age Category (Children, Young Adult, Adult, Elderly)
o	Embarkation Port (Cherbourg, Queenstown, Southampton)
o	Survival Status (Survived/Not Survived)

## 🛠 Tools Used
•	Power BI – For data visualization and dashboard development
•	Excel / Power Query – For data preparation and transformation
•	DAX (Power BI) – For calculated metrics and KPIs
•	GitHub – Portfolio documentation

## 🧹 Data Cleaning
•	Missing Values: Addressed nulls in age and embarked columns
•	Categorization: Created age categories from continuous age values
•	Standardization: Cleaned text fields for uniformity
•	Deduplication: Removed duplicate entries based on unique identifiers

## 🔄 Data Transformation
•	Age Categorization: Classified into Children, Young Adult, Adult, Elderly
•	Class Labels: Converted numeric Pclass to human-readable classes
•	Calculated Columns: Survival Rates, Total Deaths, Survivors by Group
•	Aggregated Tables: Grouped by Gender, Class, Port for comparison

## 🔍 Exploratory Analysis
•	Univariate: Distribution of passengers by class, age, and port
•	Bivariate: Cross-tab between gender and survival, class and survival
•	Multivariate: Gender-Class-Port-Survival intersections to detect biases
•	KPI tracking: Total passengers, survivors, and overall survival rate

## 💡 Key Insights with Implications
### 1. Overall Survival Rate: 38.20%
•	Implication: Majority did not survive; signals serious capacity and response failure.
•	Impact: Highlights the need for policy reform and rescue planning in maritime travel.

### 2. Survival by Gender
- Females: 72.75%
-	Males: 19.10%
-Implication: Clear gender bias in survival, due to the “women and children first” protocol.
-	Impact: While saving lives, this also points to the importance of ensuring balanced emergency protocols that prioritize vulnerability over societal norms.

### 3. Survival by Age Group
-	Children: 49.22% (highest)
-	Elderly: 32.20% (lowest)
-	Implication: Children had preferential rescue access; elderly had lowest odds, indicating physical vulnerability and reduced mobility in emergencies.
-	Impact: Validates the need for support mechanisms for the elderly in evacuation drills.

### 4. Survival by Passenger Class
-	First Class: 61.92%
-	Second Class: 42.96%
-	Third Class: 25.53%
-	Implication: Classism significantly affected survival, with lower class passengers having limited access to lifeboats and exits.
-	Impact: Reinforces modern regulations that prohibit class-based evacuation prioritization.

### 5. Port of Embarkation Influence
-	Cherbourg: 55.56% (highest survival)
-	Southampton: 33.41% (lowest survival)
-	Implication: Demographics by port affected outcomes; Cherbourg had more First-Class passengers.
-	Impact: Evacuation preparedness must consider onboard demographics, not just locations.
The fare distribution among passenger classes reveals a strong link between economic status and survival outcomes:
-	First Class:
-	Total Fare: $28.3K
-	Survival Rate: 61.92%
-	Second Class:
-	Total Fare: $9.4K
-	Survival Rate: 42.96%
-	Third Class:
-	Total Fare: $5.9K
-	Survival Rate: 25.53%

### 🔍 Key Insight:
Passengers who paid higher fares—mainly First Class—were more likely to survive. This suggests that economic status influenced survival, possibly due to better cabin placement and quicker access to lifeboats.
📌 Implication:
The data underscores class-based disparities during the disaster, where wealthier passengers had an unintentional advantage. This reinforces the modern necessity for equal safety measures and evacuation access for all passengers, regardless of fare class.

### 📊 Visualizations

![](Dash7.png)

Dashboard features:
•	Bar Charts: Age category survival, class survival, port survival
•	Pie/Donut Charts: Gender and age-based survival shares
•	Tabular View: Class-gender survival matrix with totals and rates
•	KPI Cards: Quick facts on total passengers, survivors, survival rate
The visuals are interactive and slicer-controlled by gender, class, port, and age category.

📌 Observations
1.	Gender had the most decisive effect on survival, especially in First Class.
2.	Passenger class, correlated with safety access, those in Third Class were most vulnerable.
3.	Age disparities were present—younger passengers (Children, young adult) had better survival chances than elderly.
4.	Geographic bias: Passengers from Cherbourg fared better due to wealth distribution.
5.	Third-class males were the least likely to survive, at a rate of 15.21%.

### ✅ Recommendations
1.	Equity in Lifeboat Access:
Remove class-based barriers to safety and ensure uniform emergency access.
2.	Support Protocols for Vulnerable Groups:
Prioritize passengers based on mobility, age, and medical conditions, not social norms.
3.	Emergency Communication Channels:
Create multilingual and visible alert systems for lower decks and third-class areas.
4.	Training & Simulation:
Use historical failure data for training modern maritime and aviation staff.
5.	Data-Driven Safety Policies:
Future policy designs must rely on survival data patterns, not assumptions.
🎯 This case study exemplifies the power of data visualization, storytelling, and insight-driven recommendations in using historical datasets to influence modern safety planning.
