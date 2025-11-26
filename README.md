# Mental-Health-Dashboard
The Mental Health Dashboard provides a clear and insightful view of emotional well-being by analyzing stress, anxiety, mood, sleep, social media usage, and physical activity. It helps identify behavior patterns, highlights high-risk areas, and offers data-driven insights for healthier lifestyle decisions.

📊 Mental Health Dashboard — README.md
🧠 Overview

The Mental Health Dashboard is an interactive Power BI solution designed to analyze emotional well-being using behavioral, lifestyle, and demographic data. It integrates machine learning predictions, visual analytics, and DAX-driven insights to provide a complete picture of an individual's mental state.
This dashboard transforms complex mental health data into meaningful patterns that help users understand stress, anxiety, mood, sleep, physical activity, and social media usage.

🌟 Key Features

Dynamic Time-Based Greeting powered by DAX

User-level mental health profiling (Sleep, Stress, Mood, Media Usage, Activity)

Year-over-Year Anxiety Trends

Stress Distribution by Gender

Platform Usage by Gender & Time Spent

Combined Stress-Sleep-Activity Visualization

Machine Learning Predictions (Actual vs Predicted Reach)

Clean UI inspired by modern health-tech dashboards

Fully interactive slicers and filters

🔍 Core Insights

⚠️ Stress Levels are significantly higher among males in the dataset.

📈 Anxiety levels are rising from 2024 to 2025, indicating increased mental strain.

📱 High Social Media Usage correlates with higher anxiety and neutral mood scores.

💤 Healthy Sleep often appears alongside moderate mood stability.

🏃‍♂️ Low physical activity contributes to elevated stress indicators.

🎯 The ML model demonstrates very high accuracy, with Predicted Reach closely matching Actual Reach.

🤖 Machine Learning Model

A simple yet powerful XGBoost Classifier model was trained to analyze and predict behavioral patterns.

Model Capabilities

Predicts mental health states based on input features

High accuracy with minimal error margin

Integrated into dashboard as a performance comparison table

Features Used

age

screen time

social media time

stress level

anxiety level

mood level

physical activity

sleep hours

📁 Project Structure
Mental-Health-Analysis/
│
├── mental_health_social_media_dataset.csv
├── ML_Model/
│   ├── xgb_grid_model.joblib
│   ├── preprocessing.py
│   ├── model_training.py
│
├── PowerBI/
│   ├── Mental Health Dashboard.pbix
│
├── README.md
└── assets/
    ├── dashboard_preview.png


🛠 Tech Stack

Power BI — Data visualization & DAX calculations

Python — ML model building (XGBoost, Pandas, Scikit-learn)

Machine Learning — Classification model

DAX — Custom calculated columns + greeting measure

🚀 Future Enhancements

Mental Health Risk Score (composite model)

Real-time user input analysis

Integration with mobile dashboard

Deep learning model for behavior prediction

Personalized stress-reduction recommendations

🤝 Contributing

Contributions are welcome!
Feel free to open issues, suggest improvements, or submit pull requests.
