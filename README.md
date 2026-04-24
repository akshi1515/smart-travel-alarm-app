# Smart Travel Alarm 🚀

A real-time location-based alert system that notifies users when they are near their destination.

## 📌 Overview
This app helps users avoid missing their stops by automatically triggering an alarm based on their live location.

## ⚙️ Tech Stack
- Frontend: Expo 
- Backend: n8n (Workflow Automation)
- Database: Supabase
- API: OSRM (Distance Calculation)
- Notifications: ntfy

## 🔥 Features
- Start/Stop tracking
- Real-time location updates
- Distance-based alert system
- Automatic alarm notification
- Snooze option

## 🧠 How It Works
1. App sends location to n8n webhook  
2. Data stored in Supabase  
3. Distance calculated using OSRM API  
4. If near destination → alarm triggered  

## 🔗 Backend Workflow
The core logic of this project is handled using n8n automation.
### 🔄 Process Flow:
1. Webhook receives live location from the app  
2. Data is stored and managed in Supabase database  
3. OSRM API calculates real-time distance to destination  
4. When user is near destination, an alert is triggered via ntfy notification system  

👉 Backend repository:  
https://github.com/your-username/smart-travel-alarm-backend

## 📱 APK
Download APK here:
https://drive.google.com/file/d/1Jne0fLKVHs6TZeq8-tLYPjj3Z0DDiQlf/view?usp=drive_link

### 📥 Installation:
1. Download APK  
2. Enable "Install from unknown sources"  
3. Install and open app  

## 👩‍💻 Author
Vrunda Champaneria
