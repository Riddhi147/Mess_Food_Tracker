# Mess_Food_Tracker
Mess Food Tracker is an app designed to track daily meals in institutions, analyse the consumption patterns. It allows a user to enter data on a day-to-day basis, generates summaries and dietary suggestions, takes multi-day pattern analysis to identify imbalances such as excessive oily or sugary food intake and insufficient nutritious meals.
# Problem Statement
Students often eat irregular, repetitive, or unhealthy meals
No simple way to track daily food habits
Existing apps are:
                   Too medical
                   Too complex
                   Require heavy onboarding

# Solution
This application provides a simple and intuitive interface to:
                   1. Record daily food intake
                   2. Analyze multi-day consumption patterns
                   3. Generate institutional-grade dietary recommendations
The system works offline using local storage and performs deterministic analysis to ensure reliability and explainability.

## Features
Daily food logging per calendar day  
Minimum 5-day tracking requirement for insights  
Summary of food consumption patterns  
Dietary recommendations based on analysis  
Offline-first using AsyncStorage  
Clean, institution-appropriate UI  
Optional AI (Gemini) for enhancing recommendation wording  

# Tech Stack
Frontend: Expo (React Native), TypeScript  
Navigation: Expo Router  
Storage: AsyncStorage  
Analysis: Rule-based dietary pattern analysis  
                   
# How to run the project
1. Download the zip and extract to a folder
2. Open folder in termnal
3. Run the following commands:
                                      1. npm install   
                                      2. npx expo start
4. Scan the QR using Expo Go app

