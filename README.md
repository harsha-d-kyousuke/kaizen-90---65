Kaizen Mission Tracker — 90 → 65 Transformation
📌 Overview
The Kaizen Mission Tracker is a fully self-contained HTML, CSS, and JavaScript web app designed to help you complete a 90-day transformation challenge — from 90 kg to 65 kg — using a gamified, mission-based approach.

You get:

Daily protocols for Morning, Strength, Nutrition, and Evening.

Progress tracking with XP, streaks, and ranks.

Profile customization with your own photo.

Dark/Light mode toggle.

Data auto-saving in localStorage.

Weight logging and JSON export.

🚀 Features
Daily Missions: Each day has structured tasks across four categories:

Morning Protocol

Strength Session

Nutrition Protocol

Evening Protocol

Three Phases:

Foundation (Day 1–30)

Acceleration (Day 31–60)

Final Cut (Day 61–90)

Gamification:

Earn XP for completing daily tasks.

Level up from Recruit → Warrior → Veteran → Kaizen Master.

Maintain streaks for consistent performance.

Progress Tracking:

Weight logs with timestamps.

Progress bar for daily task completion.

Motivational quotes that change as you advance.

Customization:

Upload your own profile image.

Switch between dark and light themes.

Offline Support:

All progress is stored locally in the browser (localStorage).

Data Export:

Export your logs and stats as a .json file anytime.

📂 File Structure
bash
Copy
Edit
kaizen_mission_tracker.html   # Standalone HTML file with embedded CSS & JS
No external JS files needed — only an internet connection for Google Fonts.

🛠 How to Use
Open the App
Simply open kaizen_mission_tracker.html in your browser.

Set Up Your Profile

Click UPLOAD PHOTO to set your profile picture.

Your weight starts at 90 kg, target 65 kg.

Navigate Days

Use ← PREV DAY / NEXT DAY → buttons to browse your 90-day plan.

Each day shows specific tasks for each protocol.

Mark Tasks Complete

Tick checkboxes as you finish tasks.

When all tasks are complete, you earn 100 XP for that day.

Track Weight

Enter your current weight in the input box and click LOG WEIGHT.

Logs are stored and can be exported.

Toggle Theme

Click 🌙 DARK/LIGHT to switch themes.

Export Progress

Click EXPORT DATA to download your stats and logs.

💾 Data Storage
Local Storage Keys:

kaizenMissionData: Stores all user progress, logs, profile image.

kaizenTheme: Stores current theme preference.

All changes are auto-saved every 30 seconds.

📊 Ranks & XP
Rank	XP Required
Recruit	0–1999
Warrior	2000–3999
Veteran	4000–6999
Kaizen Master	7000+

🖼 Adding Your Picture
Click UPLOAD PHOTO and select an image.

Your picture will be saved locally and persist between sessions.

🌐 Browser Compatibility
Works on any modern browser (Chrome, Edge, Firefox, Safari).

Requires JavaScript enabled.

Designed to be mobile responsive.

📜 License
This project is personal-use only, but you are free to customize and adapt it for your own transformation journey.

