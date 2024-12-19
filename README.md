# 🌲 Optimizing Visitor Experiences in National Parks (NPS_Dataset)

📋 Overview

This project focuses on enhancing visitor experiences across U.S. National Parks by leveraging real-time data from the National Park Service (NPS) APIs. By analyzing visitor behavior, park facilities, and accessibility features, we aim to provide actionable insights to improve park management and ensure a seamless experience for millions of visitors annually.

🔍 Problem Statement

Objective:  
To predict and optimize visitor experience metrics based on real-time park data.  

Effective predictions can:  

Guide resource allocation (e.g., campsites, visitor centers).  
Improve accessibility and visitor satisfaction.  
Highlight areas needing improvement to maximize engagement.

📊 Dataset Description

Data Source: National Park Service (NPS) APIs  
Size: Over 50,000 records processed  

Key Features:

Park Details: Name, location, activities, and facilities.  
Accessibility: Features like ramps, restrooms, and other accommodations.  
Visitor Behavior: Campsite usage, park designation, and activity patterns.  
Real-Time Insights: Data fetched dynamically using API requests.  

🤖 AI/ML Techniques

Model Used:  
H2O Deep Learning Model  
Accuracy: Achieved 85% prediction accuracy.  
Feature Importance: Identified top 10 influential factors using SHAP values, such as:  
Park states  
Accessibility classifications  
Activity types and visitor services  

⚙️ Technologies Used

Languages: R  
Tools: RStudio, H2O Deep Learning, ggplot2  
APIs: National Park Service (NPS) APIs  

📌 Future Enhancements

Incorporate seasonal and weather data to predict park demand dynamically.  
Expand analysis to include visitor reviews and sentiment data.  
Develop an interactive dashboard for real-time monitoring.  
