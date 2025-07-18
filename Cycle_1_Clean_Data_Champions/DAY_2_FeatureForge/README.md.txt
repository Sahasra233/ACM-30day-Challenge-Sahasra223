# Day 02 – Feature Forge + Regression 🛠️📉

## ✅ Tasks Completed:
- Loaded raw burnout dataset (`medical_raw_dataset.csv`)
- Encoded categorical variables:
  - Ordinal: JobSatisfaction, WorkLifeBalanceScore, CareerGrowthScore
  - One-Hot: Gender, Country, JobRole, Department, etc.
- Normalized numerical features using StandardScaler
- Selected features based on correlation and mutual information
- Created 2 interaction features:
  - stress_work = StressLevel × WorkHoursPerWeek
  - stress_sleep = StressLevel × SleepHours
- Trained 3 models: Linear, Ridge, and Lasso Regression
- Evaluated each model using MSE and R²
- Identified Ridge Regression as the best-performing model
