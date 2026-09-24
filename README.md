# TechEXPOr
SIH26134 • INDUSTRY SKILL PLATFORM
# ⚛️ Tech Explorer (SIH26134)

> **Bridging the Gap Between Education & Industry**  
> Live skill demand metrics, job roles, and personalized learning roadmaps powered by a Java backend.
📌 Overview
Tech Explorer is a web-based platform designed to match live technology skill demands with job opportunities and educational paths. It provides data visualizations, skill-matching filters, detailed career roadmaps, and direct links to learning resources.

✨ Features
📊 Live Industry Demand Chart: Real-time data visualization of requested tech skills (Python, Java, LLMs, Cloud, etc.).

🎯 Dynamic Skill Allocation Gauge: Interactive 2D HTML5 canvas donut chart with hover effects and detailed percentages.

💼 Job Role Finder: Search and filter tech roles based on specific skill sets.

📚 Rich Career Details & Roadmaps: Step-by-step career paths, salary insights, and curated learning links (MDN, Harvard Open Courses, NPTEL, YouTube playlists).

☕ Custom Light Java Backend: Standalone Java HTTP server API delivering structured JSON endpoints without requiring heavy frameworks.

🛠️ Tech Stack
Frontend: HTML5, CSS3, Modern Vanilla JavaScript (ES6+), HTML5 Canvas API

Backend: Java (com.sun.net.httpserver.HttpServer)

Data Interchange: RESTful JSON APIs with CORS enabled

📁 Repository Structure
Plaintext
.
├── index.html     # Main homepage containing hero charts, job filter, and insights

├── detail.html    # Detailed page view for individual job roles and learning programs

├── script.js      # Core frontend logic, API fetches, chart animations, and detail rendering

├── style.css      # Design system, styling rules, and layout structures

├── index.java     # Standalone Java backend HTTP server source code

└── index.class    # Compiled Java bytecode

🚀 Getting Started
1. Run the Backend Server
Ensure you have Java JDK 8 or higher installed on your system.

Open your terminal in the project directory.

Compile the Java server (if changes are made):

Bash
javac index.java
Run the Java server:

Bash
java index
The backend will start on http://localhost:8080.

Available API Endpoints
GET /api/hello – Verification endpoint

GET /api/skills – Skill demand metrics

GET /api/jobs – Job roles and required skills

GET /api/programs – Educational programs and durations

2. Launch the Frontend Application
Open index.html directly in any standard browser, or serve it using a local server extension (e.g., Live Server for VS Code).

The page will connect to http://localhost:8080 to dynamically populate skill cards, job opportunities, and learning details.

📄 License
This project was developed for SIH26134 (Team Quantumania). Open for educational and non-commercial usage.


### How to add this to your GitHub project:
1. Create a new file named **`README.md`** in the root directory of your project folder.
2. Paste the Markdown code above into `README.md`.
3. Commit and push the file to your GitHub repository!
