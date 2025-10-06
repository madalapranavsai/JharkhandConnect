# JharkhandConnect

[![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-2.3-green?logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-3.3-teal?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Google AI](https://img.shields.io/badge/GoogleAI-Generative-blueviolet)](https://ai.google/)

**JharkhandConnect** is a web application designed to promote tourism in Jharkhand. It provides a comprehensive platform for tourists to discover the state's attractions, plan trips with an AI-powered travel agent, and connect with local artisans and guides. The application also features a dashboard for strategic governance and analytics of tourism-related data.

---

## Key Features

- **AI Travel Agent:** Chat interface that provides personalized itineraries based on user interests, budget, and travel dates.
- **Discover Jharkhand:** Explore waterfalls, wildlife sanctuaries, temples, and historical sites.
- **Artisan Market:** Marketplace to discover and purchase authentic handicrafts like Sohrai paintings and Dokra art directly from local artisans.
- **Verified Guides and Homestays:** Connect with community-approved and blockchain-verified guides and homestays for a genuine and safe travel experience.
- **Augmented Reality Preview:** Virtually preview artifacts and get a 360° view of destinations using your smartphone.
- **Tourism Dashboard:** Analytics platform for officials to monitor tourism trends, track revenue, and manage safety and sustainability metrics.

---

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript, Tailwind CSS, Chart.js
- **Backend:** Python, Flask
- **AI:** LangChain, Google Generative AI

---

## Setup and Installation

1. **Clone the repository**


git clone https://github.com/madalapranavsai/jharkhandconnect.git
cd jharkhandconnect
python3 -m venv venv
source venv/bin/activate   # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt

Set up environment variables

Create a .env file in the root directory and add your Google API key:

GOOGLE_API_KEY="YOUR_GOOGLE_API_KEY"
Run the application
flask run

File Structure

.
├── app.py                  # Main Flask application
├── dashboard-script.js     # JavaScript for the dashboard
├── dashboard-styles.css    # CSS for the dashboard
├── script.js               # JavaScript for the main website
├── static/
│   ├── images/             # Image assets
│   └── ...
└── templates/
    ├── chat.html           # AI travel agent interface
    ├── dashboard-main.html # Tourism dashboard
    └── index.html          # Main landing page

License

This project is licensed under the MIT License.

⸻

Contact

Project Author: Madala Pranav Sai
GitHub: https://github.com/madalapranavsai
Email: your.email@example.com
