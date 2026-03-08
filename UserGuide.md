# 📍 StoPoint: The Ultimate User Guide

Welcome to **StoPoint**, your local-first, privacy-focused visit tracker. Designed for busy routines and complex schedules, StoPoint automatically logs where you went, how long you stayed, and your expenses. 

This guide walks you through setting up the app, adding your essential locations, and exporting professional reports—all without ever sending your sensitive data to a cloud server.

---

## ⚙️ Step 0: Setup & Permissions (Why We Need Location)
For StoPoint to automatically log your visits while your hands are full, it needs permission to run in the background.

* **Location Access:** When prompted, select **"Allow all the time."** This ensures StoPoint detects your arrivals and exits even when your phone is locked or in your pocket.
* **Your Privacy Guarantee:** StoPoint is a 100% local app. Your location data, visit history, and receipts are stored strictly on your device's internal database. We never see it, and it never goes to a server.

---

## 🏠 1. How to Add a New Place
Your Home Screen is your "Mission Control." Here is how to set up your first location (like a clinic, school, or gym) so StoPoint can start tracking it automatically.

1.  Tap the **Floating Action Button (+)** or the **Add Location** icon in the search bar.
2.  **Locate the Address:** Use the built-in search to find the address, or use **Manual Pin** by long-pressing and dragging the map to drop a pin exactly where you want it.
3.  **Adjust the Radius:** Set the boundary around the location. 
    * *Tip:* If your new place overlaps with an existing one (e.g., a Coffee Shop inside a Mall), tap **Smart Fit**. StoPoint will prioritize logging the **smaller radius** so you get credited for the exact shop, not just the general area.
4.  **Save** your location. 

### **Understanding "Titanium Geofencing"**
StoPoint uses a sophisticated dual-zone system to prevent accidental logs if you are just driving by:
* **Outer Zone:** Detects when you pull into the parking lot.
* **Inner Zone (Dwell Time):** The visit officially "starts" only after you have stayed for your set Dwell Time (default is 15 minutes). 

---

## 🔔 2. Setting Up Reminders
Never forget to log a copay or therapy cost again.

* **Payment Reminders:** Toggle this on for specific places. When StoPoint detects you leaving the location, it will send a notification reminding you to "Settle Up" or log an expense.
* **Smart Reminders:** StoPoint learns your routine. If you visit a specific clinic every Tuesday morning, the app will send a gentle, proactive nudge on those days to keep you prepared.

---

## 🔍 3. Finding & Categorizing Your Places
As your list of saved locations grows, finding them is easy using the **Category Rail** at the top of your screen:

* **Smart Categories:** StoPoint automatically groups your places (e.g., Work, Gym, Food, Medical) using predictive, on-device logic based on the names you enter.
* **Favourites:** Pin your most visited spots for one-tap access.
* **Fuzzy Search:** If you misspell a clinic's name in the search bar, our forgiving search engine will still find the closest match.

---

## 📜 4. Tracking & Editing Your Visits
Tap any saved place to view its complete visit history.

* **Manual Entry & Edits:** Forgot your phone or had GPS turned off? You can easily manually log a missed visit or edit the start/end times of an existing one.
* **Notes & Attachments:** Add context to your logs. You can type detailed notes, attach photos, or link PDF reports (like medical summaries or receipts) directly to a specific visit.

---

## 🤖 5. Scanning Receipts & Logging Costs
Stop typing out expenses manually. StoPoint features a powerful, on-device document scanner.

1.  Open a logged visit and tap the **Scan Receipt** icon.
2.  Take a photo of your receipt or invoice.
3.  Our smart OCR (Optical Character Recognition) will scan the document and automatically extract the **Total Cost** for you.

> **Privacy Note:** All AI scanning happens directly on your phone's processor. No images are uploaded to the cloud.

---

## 📊 6. Exporting Reports for Claims & Expenses
When it is time to submit logs for work, insurance, or tax purposes, StoPoint has you covered.

1.  Navigate to your History and filter your visits by date range or specific notes.
2.  Choose your export format:
    * **CSV Export:** Best for importing into Excel or Google Sheets.
    * **PDF Report:** Generates a clean, professional, and branded document containing your visit logs, durations, and notes.

---

## 🛠️ 7. App Maintenance & Troubleshooting FAQ
Modern Android versions are very aggressive about saving battery, which can sometimes interfere with automatic tracking. If you're experiencing issues, check these settings:

### **Why are my visits not being logged?**
The most common cause is **Battery Optimization**. Android may be "killing" the app in the background.
* **Fix:** Go to your phone's **Settings > Apps > StoPoint > Battery**. Select **"Unrestricted"**. This ensures the system doesn't pause StoPoint while you're on the move.

### **Why is there a delay in logging when I arrive?**
To save your battery, Android doesn't check your location every second.
* **The 2-Minute Rule:** There is typically a 2–3 minute delay between you entering a zone and the app triggering a log. If the device has been stationary for a long time (e.g., in your bag), this can occasionally take up to 6 minutes.
* **WiFi Tip:** Keep your **WiFi turned on** (even if not connected to a network). Geofencing uses nearby WiFi signals to pinpoint your location much faster and more accurately than GPS alone.

### **What is "Self-Healing"?**
Android occasionally "pauses" all background apps. StoPoint's **Self-Healing** feature runs a 24-hour background check to gently wake up your geofences and ensure they are ready to track your next trip.

### **The "Zombie Visit" (My visit didn't end when I left)**
If you leave a building with a very weak GPS signal, the app might not realize you've exited the zone immediately. 
* **Fix:** The app will usually auto-close once it regains a solid signal. If not, you can always manually end the visit in the History tab.

---

## 💾 8. Data & Backups
Because StoPoint is offline-only, **you own your data**. 
* **Backup:** Go to Settings to export your entire database to a JSON file.
* **Restore:** If you get a new phone, simply import your backup file to pick up right where you left off.

---
