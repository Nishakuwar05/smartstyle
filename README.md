:

🛍️ SmartStyle — AI-Powered Fashion Recommender
SmartStyle is a fashion assistant web app that helps users find ideal dresses based on their body shape, color, height, and weight. It features user login, camera-based detection (via OpenCV), and intelligent outfit suggestions.

🌟 Features
User login & registration with secure authentication

Optional camera snapshot for body shape detection

Manual form input: height, weight, skin tone, and body shape

AI logic using CSV + simple ML or rule-based recommendations

Clean UI built with HTML/CSS, powered by Flask and MySQL


📂 Project Structure
css
Copy
Edit
smartstyle/
├── backend/
│   ├── app.py                ← Main server file
│   ├── model/                ← ML models (shape_detector.pkl)
│   └── data/                 ← CSV datasets
├── frontend/
│   ├── templates/            ← Flask HTML templates
│   └── static/css/           ← Styling files
├── README.md
└── requirements.txt


 Tech Stack
Layer	Technology
UI / Frontend	HTML, CSS, Bootstrap (optional)
Backend	Python (Flask)
Database	MySQL
AI / ML	OpenCV (camera), scikit‑learn or rule logic
Data Handling	pandas, CSV
