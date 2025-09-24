# Smart India Hackathon Workshop
# Date: 24-9-2025
## Register Number:25018161
## Name:PRIYADHARSHINI V
## Problem Title
SIH 25010: Smart Crop Advisory System for Small and Marginal Farmers
## Problem Description
A majority of small and marginal farmers in India rely on traditional knowledge, local shopkeepers, or guesswork for crop selection, pest control, and fertilizer use. They lack access to personalized, real-time advisory services that account for soil type, weather conditions, and crop history. This often leads to poor yield, excessive input costs, and environmental degradation due to overuse of chemicals. Language barriers, low digital literacy, and absence of localized tools further limit their access to modern agri-tech resources.

Impact / Why this problem needs to be solved

Helping small farmers make informed decisions can significantly increase productivity, reduce costs, and improve livelihoods. It also contributes to sustainable farming practices, food security, and environmental conservation. A smart advisory solution can empower farmers with scientific insights in their native language and reduce dependency on unreliable third-party advice.

Expected Outcomes

• A multilingual, AI-based mobile app or chatbot that provides real-time, location-specific crop advisory.
• Soil health recommendations and fertilizer guidance.
• Weather-based alerts and predictive insights.
• Pest/disease detection via image uploads.
• Market price tracking.
• Voice support for low-literate users.
• Feedback and usage data collection for continuous improvement.

Relevant Stakeholders / Beneficiaries

• Small and marginal farmers
• Agricultural extension officers
• Government agriculture departments
• NGOs and cooperatives
• Agri-tech startups

Supporting Data

• 86% of Indian farmers are small or marginal (NABARD Report, 2022).
• Studies show ICT-based advisories can increase crop yield by 20–30%.

## Problem Creater's Organization
Government of Punjab

## Theme
Agriculture, FoodTech & Rural Development

## Proposed Solution
We propose a Smart Crop Advisory System powered by AI, IoT, and Cloud Computing.

Key Features:

-Crop Recommendation Engine: Suggests suitable crops based on soil, climate, and market trends.
-Fertilizer Guidance: AI-driven recommendations based on soil nutrient status.
-Pest/Disease Diagnosis: Farmers upload crop images → CNN model detects diseases → advisory given.
-Weather Forecast Integration: Short-term and seasonal prediction for irrigation, sowing, and harvesting.
-Market Price Monitoring: Live mandi prices and forecasts.
-Voice & Multilingual Support: Local language voice assistant for inclusivity.
-Offline Functionality: SMS and USSD-based fallback for low-connectivity regions.

## Technical Approach
System Architecture

-Frontend:
--Cross-platform mobile app (Flutter/React Native).
--Multilingual UI + voice interface.

-Backend:
--RESTful APIs (FastAPI/Django).
--Cloud-based microservices (AWS/GCP/Azure).
--Message queues (RabbitMQ/Kafka) for handling real-time data streams.

-Database:
--PostgreSQL with PostGIS (geo-tagging).
--NoSQL (MongoDB) for image and unstructured data.

-AI/ML Modules:
--CNN for pest/disease detection (trained on agricultural datasets).
--Random Forest / XGBoost for crop & fertilizer recommendations.
--LSTM/ARIMA for weather trend predictions.

-IoT Integration (Optional in Pilot):
--Soil moisture sensors, pH sensors with GSM/LoRaWAN connectivity.

-External APIs & Data Sources:
--IMD Weather API, ISRO satellite data, Government Agri DB, Agmarknet for mandi prices.

![alt text](<agri flowchart.png>)
## Feasibility and Viability
-Feasibility:
--Mobile-first solution (works on low-end smartphones).
--Uses existing government & open APIs.
--Offline fallback ensures adoption in rural areas.

-Challenges & Mitigation:
--Internet connectivity → SMS/USSD advisory.
--Language diversity → incremental rollout with regional languages.
--Data accuracy → expert validation and feedback loop.

-Viability:
--Aligns with Digital India & Smart Farming Missions.
--Potential partnerships with Krishi Vigyan Kendras (KVKs), NGOs, and Agri-tech startups.
## Impact and Benefits
--Social: Farmers gain access to reliable, localized advisory.
--Economic: Increased yield (20–30%), reduced input costs.
--Environmental: Reduction in overuse of fertilizers and pesticides.
--Scalability: Can scale to multiple states with minimal changes.

## Research and References
--NABARD Report (2022):(https://www.nabard.org)
--Research Paper: ICT-Based Agricultural Advisory Services and Farmers’ Productivity in India (ScienceDirect, 2021): https://www.sciencedirect.com/science/article/pii/S2210670721000253