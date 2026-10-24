# 🏙️ SmartCity One

> **"One City. One App. Better Public Services."**  
> *An AI-Powered Smart City Services & Infrastructure Coordination Platform*

**Founder / Presenter:** P. Chaithanya Raj  
**Domain:** Smart City Infrastructure • AI Triage • Location Intelligence • Rapid Civic Routing

---

## 🚀 Overview & Vision

Modern quick-commerce apps (like Blinkit and Zomato) proved that live location routing, clear status tracking, and instant partner alerts can eliminate coordination delays. **SmartCity One** brings that same real-time digital coordination to municipal public services—connecting **Citizens**, **Municipal Officers**, and **Nearest Qualified Field Workers** in a single transparent platform.

---

## 📱 Complete 14-Screen Interactive UI Architecture

This repository contains the complete, animated 14-screen web application matching the **SmartCity One UI Presentation Board**:

1. **Splash Screen (Language Selection):** Animated smart-city skyline with instant switching between **English**, **తెలుగు (Telugu)**, and **हिन्दी (Hindi)**.
2. **Login / Registration:** Role-based authentication switcher (**Citizen**, **Officer**, **Worker**) plus Google & Phone OTP quick demo sign-in.
3. **Citizen Home Dashboard:** Live Vijayawada weather & AQI banner, 6 rapid-action service cards, and active ticket tracker.
4. **Report an Issue (Step 1 - Details):** 6 civic categories (*Pothole, Garbage, Drainage, Streetlight, Water Supply, Others*), multilingual voice input simulator, and **AI Priority & Duplicate Detection**.
5. **Select Location (Step 2 - GPS / Map):** Interactive Vijayawada street map with tap-to-move pin, `Use Current Location` GPS lock (`16.5062, 80.6480`), and EXIF location consistency verification.
6. **Add Photos / Videos (Step 3 - Media):** Camera/gallery photo and video attachments with live thumbnail previews, file size validation, and removal controls.
7. **Submission Success (Step 4 - Ticket ID):** Animated confirmation with unique ticket generation (e.g., `SC202507210001`).
8. **Track My Reports:** Filterable ticket queue (*All, Pending, In Progress, Resolved*) with thumbnails and timestamps.
9. **Report Details & Timeline:** 5-stage live vertical resolution timeline (*Submitted → Assigned to Department → In Progress → Pending Verification → Resolved*), photo evidence gallery, and **Citizen Feedback & Star Rating**.
10. **Nearby Public Services Finder:** Interactive map and directory for *Hospitals, Police Stations, Fire Stations, Accessible Public Toilets, and Cyclone/Flood Shelters* with verification metadata.
11. **City Alerts & Disaster Hub:** Categorized *Water, Traffic, Electricity, and Weather* advisories with clear `DEMO DATA — NOT AN OFFICIAL WARNING` governance labels and waterlogging/blocked-road reporting.
12. **Municipal Officer Dashboard:** Live KPI counters (*24 New Reports, 18 In Progress, 120 Total Reports, 12 Resolved*), department & nearby worker dispatch modal, Event-Service approval tab, and SLA/Audit trail tab.
13. **Field Worker App (`My Tasks`):** Assigned, In-Progress, and Completed task queues with distance routing, before-and-after repair photo upload, and officer verification submission.
14. **Event Service Request:** Organizer request workflow for *Temporary Toilets, Waste Bins, Drinking Water, and Traffic Support*.

---

## 🛠️ Quick Start & GitHub Pages Deployment

### Run Locally
No build step or external server required! Simply open `index.html` in any modern desktop or mobile browser.

### Push to GitHub & Publish Live via GitHub Pages
```bash
git init
git add index.html README.md LICENSE .gitignore push-to-github.sh
git commit -m "feat: SmartCity One 14-screen animated smart city platform"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/SmartCity-One.git
git push -u origin main
```
Then open **Settings → Pages** in your GitHub repository, choose **Deploy from a branch (`main` / `root`)**, and click **Save**.

---

## ⚠️ Prototype Governance & Honest Technical Scope
- **Browser Prototype:** Uses in-memory/browser state for live hackathon demonstration.
- **Human-in-the-Loop AI:** AI suggestions assist municipal officers with categorization, duplicate detection, and priority triage; AI never independently issues emergency warnings or approves legal permits.
- **Simulated Alerts:** All city and weather alerts are visibly labeled `DEMO DATA — NOT AN OFFICIAL WARNING`.
