# 1. Introduction
# Talent-Pulse-Solutions-Inc
Talent-Pulse-Solutions-Inc is a forward thinking organization dedicated to empowering businesses through strategic workforcemanagement.Asaleader intalent optimization, the company prides itself on fosteringanenvironment whereemployees canthrive.
# 1.1 Overview
Talent-Pulse Solutions Inc. is a workforce optimization organization focused on improving employee retention, engagement, and overall performance through data-driven decision-making. Facing rising attrition rates and inconsistent workforce satisfaction, the company seeks to leverage HR analytics to identify key drivers of turnover across departments, demographics, tenure, and compensation structures. By analyzing factors such as job satisfaction, work-life balance, performance ratings, overtime, promotions, and managerial relationships, Talent-Pulse aims to uncover actionable insights that support strategic workforce planning. Through centralized dashboards and structured data governance, the organization intends to enhance transparency, strengthen retention strategies, and improve long-term organizational effectiveness.
# 1.2 Aim of the project 
- dentify key trends and factors
contributingtoemployeeattrition.
- Analyze workforce demographics by
department, gender, age group, and
educationleveltounderstandpatterns.
- Track attrition trends over time and
compare survey scoreswith employee
turnoverrates.
- Build a comprehensive dashboard to
enableHR teams tomakedata-driven
decisions.
# 1.3 Data Description
This dataset captures employee demographic, compensation, performance, and satisfaction attributes to analyze attrition trends, workforce engagement, and organizational performance.

#### Employee Demographics

- Age: Employee age in years.

- Gender: Employee gender.

- MaritalStatus: Marital status classification.

- Education: Education level (ordinal scale).

- EducationField: Area of academic specialization.

- Over18: Indicator confirming employee is over 18.

- Employment & Organizational Details

- EmployeeNumber: Unique employee identifier.

- EmployeeCount: Count indicator (typically constant = 1).

- Department: Functional department assignment.

- JobRole: Specific role designation.

- JobLevel: Organizational seniority level.

- BusinessTravel: Frequency of work-related travel.

- DistanceFromHome: Distance between home and workplace.

#### Compensation & Benefits

- DailyRate: Daily compensation rate.

- HourlyRate: Hourly pay rate.

- MonthlyIncome: Monthly salary.

- MonthlyRate: Monthly rate metric (cost reference).

- PercentSalaryHike: Most recent salary increment percentage.

- StockOptionLevel: Assigned stock option tier.

#### Performance & Engagement Metrics

- PerformanceRating: Latest performance evaluation score.

- JobInvolvement: Level of engagement in job responsibilities.

- JobSatisfaction: Self-reported job satisfaction score.

- EnvironmentSatisfaction: Workplace environment satisfaction score.

- RelationshipSatisfaction: Satisfaction with workplace relationships.

- WorkLifeBalance: Perceived work-life balance rating.

- TrainingTimesLastYear: Number of training sessions attended.

#### Work History & Tenure

- TotalWorkingYears: Total professional experience in years.

- NumCompaniesWorked: Number of previous employers.

- YearsAtCompany: Tenure at current organization.

- YearsInCurrentRole: Years in current job role.

- YearsSinceLastPromotion: Time since last promotion.

- YearsWithCurrManager: Years under current manager.

- StandardHours: Standard working hours per period.

- OverTime: Overtime work indicator.

#### Attrition Indicator
Attrition: Binary variable indicating whether the employee has left the organization (Yes/No).
# 2. Analysis
## 2.1 Problem Statement
- High attrition rates have been observed,
which could impact productivity and
organizationalperformance.
- Lackof clear understandingof attrition
trends across departments,
demographics,andtenure.
- Difficultyinidentifyingfactorsinfluencing
recentattritionandlowsurveyscores.
- Needforbettervisualizationofworkforce
datatosupportdecision-making.
## 2.2 Key Indicators
#### 2.2.1  Attrition Rate: Total Attrition: Current Employees:
The organisation reports an overall attrition rate of 16.36%, equating to 243 departures out of a total workforce of 1,485 employees. Departmental analysis shows that Sales has the highest attrition rate at approximately 25.8%, followed by HR at 23.5%, while R&D records a lower rate of 16.6% despite contributing the highest absolute number of exits due to its larger headcount. Role-level insights indicate elevated turnover among Sales Executives, Research Scientists, and Laboratory Technicians, highlighting retention risks within revenue-generating and core technical functions. Attrition is heavily concentrated within the first three years of tenure, after which exit rates decline significantly, suggesting early-career vulnerability. The current workforce distribution consists of 835 employees in R&D, 356 in Sales, and 51 in HR, with R&D accounting for the majority of total headcount.

<img src="https://github.com/user-attachments/assets/88fb361f-caf6-482b-b3df-d02de062e519" width="100%" alt="Screenshot 2026-02-25 173536" />

#### 2.2.2 Demographics by Gender, Age Group, and Educational Field:
Higher turnover is observed among employees aged 18–35, particularly within the 27–35 bracket. While male attrition counts are higher, this aligns with workforce composition rather than indicating disproportionate risk. Employees with Life Sciences and Medical educational backgrounds account for the largest share of exits, largely due to their concentration in R&D and technical roles. Younger, technically skilled employees exhibit higher mobility.

<img src="https://github.com/user-attachments/assets/5faecc24-ad82-445c-b75e-5e40fd4ab6ae" width="100%" alt="Screenshot 2026-02-25 173650" />

#### 2.2.3 Survey Score:
There is a clear inverse relationship between job satisfaction scores and attrition. Employees reporting lower satisfaction levels (scores 1–2) demonstrate significantly higher exit rates, particularly in Sales and laboratory-based roles. This indicates that engagement and perceived job quality are materially correlated with turnover outcomes.

<img src="https://github.com/user-attachments/assets/cb476f64-a12f-489b-ad0b-cb028e066f88" width="100%" alt="Screenshot 2026-02-25 173902" />

#### 2.2.4 Recent Attrition:
Recent exits include a Sales Representative and a Research Scientist, both high performers with short tenure (2–3 years) and low job satisfaction scores. Despite receiving competitive salary increases, both individuals left the organization. This pattern suggests attrition drivers are less compensation-related and more closely tied to engagement, role experience, or career development limitations within early tenure stages.

<img src="https://github.com/user-attachments/assets/2509dddc-3565-44d7-a200-bc0b30fb9690" width="100%" alt="Screenshot 2026-02-25 173849" />


#### 2.2.5 Attrition Trend:
Attrition decreases progressively with years in role. The highest exit rates occur within the first two to three years, followed by a marked decline after mid-tenure. Long-tenured employees (10+ years) show minimal attrition. This trend suggests early engagement, onboarding effectiveness, and career progression pathways are critical retention levers.

<img src="https://github.com/user-attachments/assets/eb16c38a-efea-4eaa-aaf8-d906790f55d2" width="100%" alt="Screenshot 2026-02-25 173714" />

# 3. DASHBOARD
The HR Analytics Dashboard highlights an overall attrition rate of 16.36%, with 243 employees leaving out of 1,485, indicating a moderate but strategically important turnover level. Attrition is most concentrated within the R&D and Sales departments, with Sales roles such as Sales Executive and Sales Representative showing notable exits. Demographically, employees aged **27–35** represent both the largest workforce segment and the highest attrition group, suggesting early-to-mid career mobility as a key driver. While gender distribution shows higher overall male representation, attrition appears proportionate across both groups. Educational background analysis shows stronger retention among Life Sciences and Medical fields, though these areas also contribute significantly to exits due to overall workforce size. The attrition trend shows sharp early spikes followed by a sustained decline, indicating possible improvements in retention efforts over time. Survey scores and recent attrition profiles suggest that lower job satisfaction, limited tenure in current roles, and modest salary progression may be influencing voluntary exits, highlighting opportunities to strengthen engagement, career development pathways, and compensation alignment to reduce future turnover.

<img src="https://github.com/user-attachments/assets/cb5d09a7-ebf9-4c60-bd38-8250af572f2f" width="100%" alt="Screenshot 2026-02-25 152835" />
