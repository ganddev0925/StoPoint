# 📍 StoPoint: The Ultimate User Guide

Welcome to **StoPoint**, your local-first, privacy-focused visit tracker. Designed for busy routines and complex schedules, StoPoint automatically logs where you went, how long you stayed, and your expenses. This guide walks you through setting up the app, adding your essential locations, and exporting professional reports—all without ever sending your sensitive data to a cloud server.

---

### ⚙️ Step 0: Setup & Permissions (Why We Need Location)
For StoPoint to automatically log your visits while your hands are full, it needs specific permissions to run in the background.

*   **Location Access:** When prompted, select **“Allow all the time.”** This ensures StoPoint detects your arrivals and exits even when your phone is locked or in your pocket.
*   **Physical Activity Permission:** To optimize battery life and accuracy, StoPoint requires access to your physical activity. This allows the app to know when you are moving versus stationary (**Smart Silence**), preventing "GPS drift" from logging fake visits while you are sitting still.
*   **Battery Optimization:** Go to your phone’s *Settings > Apps > StoPoint > Battery* and select **“Unrestricted”**. This prevents Android from "killing" the app while it's waiting for you to arrive.
*   **Tracking after phone restart or power off/on:** StoPoint is built for reliability. It will resume tracking automatically after your phone reboots, even before you unlock your device.

---

### 🆓 Why StoPoint is Free
To keep StoPoint 100% free and without intrusive ads, we don't use paid services like Google Places Autocomplete. This allows us to provide advanced features like OCR receipt scanning and smart reminders at no cost to you. By using the methods below to add your places, you help keep the app independent and free for everyone!

---

### 🏠 1. How to Add a New Place
Your Home Screen is your “Mission Control.” Here is how to set up your first location (like a clinic, school, or gym) so StoPoint can start tracking it automatically.

1.  Tap the **Floating Action Button (+)** or the **Add Location** icon in the search bar.
2.  **Locate the Address:**
    *   **At the Site (Best Option):** Just go to the place and tap **"Pick This Spot"**. StoPoint will lock on to your GPS coordinates and handle the rest!
    *   **Pan the Map:** Manually scroll and zoom the map to find your destination. The pin stays centered as you move, allowing you to position it exactly where you want it.
    *   **Exact Address Search:** Enter the full street address in the search bar. StoPoint will find the exact match for you.
3.  **Adjust the Radius:** Set the boundary around the location.
    *   *Tip:* If your new place overlaps with an existing one (e.g., a Coffee Shop inside a Mall), tap **Smart Fit**. StoPoint will prioritize logging the smaller radius so you get credited for the exact shop, not just the general area.
4.  **Save your location.**

**Understanding “Geofencing”**
StoPoint uses a sophisticated dual-zone system to prevent accidental logs if you are just driving by:
*   **Outer Zone:** Detects when you pull into the parking lot and "wakes up" the tracking sensors.
*   **Inner Zone (Dwell Time):** The visit officially “starts” only after you have stayed for your set Dwell Time (default is 15 minutes).

---

### 🔔 2. Setting Up Reminders & Smart Alerts
Never forget to log a copay or therapy cost again.

*   **Payment Reminders:** Toggle this on for specific places. When StoPoint detects you leaving the location, it will send a notification reminding you to “Settle Up” or log an expense.
*   **Smart Silence:** Tired of notifications while driving? StoPoint now detects when you are in a vehicle. It will silently log your arrival in the background, but **won't chime** until the Dwell Timer confirms you've actually parked and stayed.
*   **Smart Reminders:** StoPoint learns your routine. If you visit a specific clinic every Tuesday morning, the app will send a gentle, proactive nudge on those days to keep you prepared.

---

### 🔍 3. Finding & Categorizing Your Places
As your list of saved locations grows, finding them is easy using the Category Rail at the top of your screen:

*   **Live Tracking Hero:** When a visit is in progress, a "Live Tracking" card appears at the top of your dashboard. Tapping this gives you instant access to that location's options and history.
*   **Smart Categories:** StoPoint automatically groups your places (e.g., Work, Gym, Food, Medical) using predictive, on-device logic based on the names you enter.
*   **Favourites:** Pin your most visited spots for one-tap access.
*   **Fuzzy Search:** If you misspell a clinic’s name in the search bar, our forgiving search engine will still find the closest match.

---

### 📜 4. Tracking & Editing Your Visits
Tap any saved place or map marker to open the **Place Options** menu. From here, you can select **View History** to see detailed logs, or **Navigate** to launch your GPS.

*   **Adaptive Layout:** On tablets and foldable devices, StoPoint uses an **Adaptive Layout**, allowing you to keep your list of places visible on the left while managing options or history on the right.
*   **Skeptical Exit Logic:** To prevent "WiFi Jumps" (where a weak signal makes it look like you left a building), StoPoint now uses a 2-minute verification period. It will double-check your GPS before officially closing a visit, significantly reducing false "exit-and-re-entry" logs.
*   **Reopen & Resume:** If you briefly step out of a zone (e.g., to grab something from your car) and return within **10 minutes**, StoPoint will automatically resume your existing visit instead of creating a "Double Ding" (two separate logs). This ensures your visit history remains clean and continuous.
*   **Manual Entry & Edits:** Forgot your phone or had GPS turned off? You can easily manually log a missed visit or edit the start/end times of an existing one.
*   **Notes & Attachments:** Add context to your logs. You can type detailed notes, attach photos, or link PDF reports (like medical summaries or receipts) directly to a specific visit.

---

### 🤖 5. Scanning Receipts & Logging Costs
Stop typing out expenses manually. StoPoint features a powerful, on-device document scanner.

1.  Open a logged visit and tap the **Scan Receipt** icon.
2.  Take a photo of your receipt or invoice.
3.  Our smart **OCR (Optical Character Recognition)** will scan the document and automatically extract the Total Cost for you.

*   **Privacy Note:** All AI scanning happens directly on your phone’s processor. No images are uploaded to the cloud.

---

### 📊 6. Exporting Reports for Claims & Expenses
When it is time to submit logs for work, insurance, or tax purposes, StoPoint has you covered.

1.  Navigate to your **History** tab.
2.  Filter your visits by date range, category, or specific notes.
3.  **Choose your export format:**
    *   **CSV Export:** Best for importing into Excel or Google Sheets (mileage and cost tracking).
    *   **PDF Report:** Generates a clean, professional document containing your visit logs, durations, and notes.

---

### 🚗 7. Android Auto Integration
StoPoint goes where you go!
*   **In-Car View:** View your nearby places and recent visits directly on your car's dashboard.
*   **Easy Navigation:** On your phone, simply tap a place and select **Navigate** from the Options sheet. On Android Auto, tapping a location launches navigation directly for driver safety.
*   **Smart Silence:** Your car's head unit remains clutter-free as driving-related arrival chimes are suppressed automatically.

---

### 🛠️ 8. App Maintenance & Troubleshooting FAQ
Modern Android versions are very aggressive about saving battery, which can sometimes interfere with automatic tracking.

*   **Safety First:** Accidentally deleting a place or disabling tracking while you are mid-visit is protected. StoPoint requires a secondary confirmation via a safety dialog before any location is permanently removed or tracking is stopped, ensuring you don't lose an active log by mistake.
*   **Why are my visits not being logged?** The most common cause is Battery Optimization. **Fix:** Set StoPoint to **“Unrestricted”** in your phone's battery settings.
*   **Radio Discipline (NEW):** To maximize battery life, StoPoint uses "Recency-First" logic. If another app (like Maps) recently got a GPS fix, we "piggyback" off that data instead of waking up the GPS radio ourselves.
*   **Why is there a delay in logging when I arrive?** To save your battery, Android doesn’t check your location every second. Typically, there is a 2–3 minute delay. If you're driving, **Smart Silence** will also keep the app quiet until you've stayed for your Dwell Time.
*   **What is “Self-Healing”?** Android occasionally “pauses” background apps. StoPoint’s Self-Healing feature runs a 24-hour check to gently wake up your geofences and ensure tracking remains reliable.
*   **WiFi Tip:** Keep your WiFi turned on! Geofencing uses nearby WiFi signals to pinpoint your location much faster than GPS alone.

---

### 💾 9. Data & Backups (StoPoint Vault)
Because StoPoint is offline-only, you own your data. To keep your history safe when switching phones:

*   **Google Cloud Backup:** For maximum privacy, we've strictly **disabled** Google's Auto-Backup for Apps. No data is ever synced to Google's servers.
*   **Device-to-Device Migration:** We have enabled **Device-to-Device transfer**. If you migrate to a new phone via direct cable or local WiFi during setup, your visits and settings will automatically move to your new device.
*   **Create Vault:** Go to **Settings > Automation & Data**. You can create a **"StoPoint Vault" (.spv)** which bundles your places, visits, app settings, and optionally your photo attachments into one secure file. This is the most reliable way to save your logs for the long term.
*   **Restore:** On your new device, use **"Restore from Vault"** to pick up right where you left off. Everything, including your preferred theme and tracking accuracy, will be restored.
*   **Privacy Guarantee:** StoPoint is a 100% local app. Your location, activity, visit history, and receipts are stored strictly on your device. We never see it, and it never goes to a server.
