# Smart City Hackathon: Problems & Solutions

This document contains four unique software solution ideas tailored for the iikhaiN 2025 Hackathon. The concepts are designed to be innovative, impactful, and feasible within a 12-hour coding sprint. They directly address real-world problems in the Philippines, aligning with the "Smart City" theme.

---

### 1. The Problem: Urban Flooding & Reactive Disaster Response

**Background:** The Philippines is extremely vulnerable to typhoons and urban flooding. Current solutions often provide delayed information, lack street-level accuracy, and fail to guide citizens to safety effectively. Evacuation centers can become overcrowded without real-time capacity management.

**Software Solution: Project AGOS** (Alert, Guide, Operate, System)

`AGOS` means "flow" in Filipino. It's a community-driven, predictive flood alert and smart evacuation system.

- **Unique Angle:** Instead of just showing static flood maps, AGOS uses a combination of weather API data and **real-time crowdsourced reports** to predict which specific streets are likely to flood. It then provides dynamic safe routes to the nearest **verified and available** evacuation centers.

- **Key Features (Hackathon MVP):**
    - **Live Flood Map:** An interactive map where users can report flood levels ("Ankle-deep," "Waist-deep," "Not Passable") with photos and timestamps. These reports appear instantly for all users.
    - **Predictive Alerts:** A simple algorithm that notifies users if their current location or saved home address is at high risk of flooding in the next 1-3 hours based on weather forecasts and report density.
    - **Smart Evacuation Router:** A feature that finds a route to the nearest evacuation center, dynamically avoiding streets that are reported as flooded. It would show mock data for which centers have available space.
    - **LGU Dashboard:** A simple dashboard view for local government units (LGUs) to see a live map of citizen reports, helping them allocate resources more effectively.

- **Tech Stack & APIs:**
    - **Frontend:** Progressive Web App (PWA) using React/Vue for mobile-first accessibility.
    - **Backend/DB:** Firebase or Supabase for real-time database and user reports.
    - **APIs:** Google Maps API (for maps, routing), OpenWeatherMap API (for weather data).

---

### 2. The Problem: Inefficient Public Transport & Traffic Congestion

**Background:** Metro Manila's traffic is a major economic and social issue. A significant portion of commuters relies on Public Utility Vehicles (PUVs) like jeepneys and UV Express vans, which have no formal tracking system, making commute times unpredictable.

**Software Solution: PARA** (Public-transport Analytics & Real-time Assistant)

`PARA` means "to stop" in the context of Filipino commuting. It's a crowdsourced tracking and analytics platform for PUVs.

- **Unique Angle:** It bypasses the need for expensive GPS hardware on every PUV. Instead, it empowers **passengers and drivers** to broadcast their vehicle's location using their own smartphones. It also introduces a "commuter density" heatmap to help drivers and passengers make smarter decisions.

- **Key Features (Hackathon MVP):**
    - **Crowdsourced Trip Tracking:** A simple "Start Trip" button allows a passenger or driver to anonymously share the PUV's location in real-time along its designated route.
    - **Live PUV Map:** A map showing the real-time locations of tracked PUVs, allowing commuters to see how far the next ride is.
    - **Predictive Arrival Time:** Calculates an estimated time of arrival (ETA) for the next PUV at a user's stop based on the speed and location of currently tracked vehicles.
    - **Commuter Heatmap:** Users can report they are waiting at a specific location, creating a heatmap that shows drivers where passenger demand is high and shows commuters where competition for rides is stiff.

- **Tech Stack & APIs:**
    - **Frontend:** PWA (React/Vue) or React Native for a lightweight mobile experience.
    - **Backend/DB:** Firebase or Supabase for handling high-frequency real-time location updates.
    - **APIs:** Google Maps API (for routes and map visualization).

---

### 3. The Problem: Food Waste from Businesses & Urban Hunger

**Background:** Restaurants, cafes, and bakeries throw away significant amounts of unsold food daily, while many urban communities face food insecurity. There's a gap in connecting this surplus food to people who need it.

**Software Solution: HAPAG** (Harvesting Abundance for People And Growth)

`HAPAG` means "dining table" in Filipino, symbolizing a shared meal. It's a mobile-first marketplace for rescuing surplus food.

- **Unique Angle:** It uses a "Surprise Bag" model, making it extremely easy for businesses to participate. Instead of listing individual items, they sell a mixed bag of their surplus food at a heavy discount. It also integrates a direct-to-charity donation feature.

- **Key Features (Hackathon MVP):**
    - **Business Listing:** A simple form for a food establishment to post a "HAPAG Bag," setting a price, quantity, and a pickup window (e.g., "Today, 8 PM - 9 PM").
    - **Consumer Discovery:** A map and list view for users to find and purchase these surprise bags nearby.
    - **Reservation & Mock Payment:** Users can reserve a bag and go through a simulated payment process.
    - **"Feed Forward" Donation:** An option for a user to purchase a bag and donate it directly to a partnered local NGO, who can then claim the food.

- **Tech Stack & APIs:**
    - **Frontend:** Web App using React/Vue + Tailwind CSS for a polished UI.
    - **Backend:** Node.js + Express.
    - **APIs:** Google Maps API (for discovery), a payment gateway like Stripe (in test mode).

---

### 4. The Problem: Disconnected Citizens & Local Government Inefficiency

**Background:** Reporting local, non-emergency issues like potholes, broken streetlights, or uncollected garbage is often a bureaucratic and frustrating process. There is little transparency, and citizens feel unheard.

**Software Solution: BantayBayan** (Community Watch)

`BantayBayan` is a Filipino term for a neighborhood watch. It's a gamified civic issue reporting and transparency platform.

- **Unique Angle:** It gamifies citizen engagement by awarding users points and badges for reporting issues. Crucially, it provides a **public transparency dashboard** that shows the status of all reports and tracks the performance of the local government unit (e.g., average time to resolve an issue), creating social pressure for accountability.

- **Key Features (Hackathon MVP):**
    - **Simple Issue Reporting:** A form to report an issue with a category (e.g., "Waste," "Infrastructure"), a photo, and an automatically tagged location.
    - **Public Transparency Map:** A map that displays all reported issues and their current status ("Submitted," "In Progress," "Resolved"). Users can filter by barangay or issue type.
    - **Gamified User Profiles:** Users have profiles that show their "Civic Score" based on the number and quality of their reports.
    - **Mock LGU Portal:** A simple interface where someone playing the role of a government official can log in and update the status of a reported issue, which is then reflected on the public map.

- **Tech Stack & APIs:**
    - **Frontend:** Web App using React/Vue.
    - **Backend/DB:** Firebase or Supabase for easy data management and authentication.
    - **APIs:** Google Maps API (for location tagging and map view).