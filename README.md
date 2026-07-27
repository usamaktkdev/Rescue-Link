# RescueLink 🚨

RescueLink is a lightweight, community-driven emergency assistance application designed for areas where professional emergency services may not always arrive quickly. 

## 📖 About the Project

Many emergency situations occur where professional rescue teams take time to arrive, and communication is difficult due to poor internet connectivity. RescueLink addresses this gap by connecting people with nearby volunteers and improving awareness of local hazards. The application is intentionally designed to remain highly usable and reliable on slow mobile networks and in rural areas[cite: 1].

## ✨ Key Features

* **Community-First SOS:** Request immediate assistance from nearby volunteers using a deliberate slide interaction to prevent accidental activation[cite: 1]. 
* **Unified Volunteer System:** No separate volunteer accounts are needed; any user can easily toggle "Volunteer Mode" to share their skills, equipment, and availability[cite: 1]. 
* **Real-Time Hazard Mapping:** Report dangerous locations (e.g., landslides, flooded roads) with compressed images to alert community members within a 15 km radius[cite: 1].
* **Offline Resilience:** If internet connectivity drops, the app stores essential emergency data locally, continuously retries transmission, and automatically sends the SOS once connectivity returns[cite: 1].
* **Low-Bandwidth Operation:** Prioritizes small data transfers, compressed images, lightweight location updates, and cached custom map data to function efficiently on slow networks[cite: 1].
* **Emergency Contacts Fallback:** Sends standard SMS messages containing emergency details and GPS coordinates to designated contacts, ensuring they receive the alert even without the app installed[cite: 1].

## 🛠️ Tech Stack

* **Mobile Framework:** Flutter & Dart
* **Backend Services:** Supabase / Firebase 
