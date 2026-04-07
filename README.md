BridgeFi
Closing the Loop Between Applicant Effort & Recruiter Response

-A dual-sided AI platform that bridges skill gaps, predicts ghosting, and improves hiring transparency.

Not another resume parser. Not another tracker.
Two sides. One intelligent system.
Why BridgeFi?

Every job application has two silent problems:

❌ Candidates don’t know why they’re rejected
❌ Recruiters unintentionally ghost applicants

 BridgeFi solves both — simultaneously.

What BridgeFi Does:

-For Applicants
Detects skill gaps vs job description
Generates mini-projects to improve skills
Predicts ghosting probability
Tracks all applications in one dashboard
Auto-generates follow-up emails

-For Recruiters
Manage candidate pipeline
Track ghosting behavior
Score candidates on:
Skill level
Learning ability
Improve employer brand transparency

How It Works

Resume + Job Description(JD) → AI Analysis → Skill Gap Detection → Smart Insights → Better Hiring Decisions

Core Workflow
Upload Resume + Job Description
Extract & classify skills
Analyze JD requirements
Compare both sides
Generate:
Match score
Skill gaps

Recommendations
 Tech Stack
Layer	Technology
Backend	Python + Flask
Database	SQLite (SQLAlchemy)
Frontend	HTML + CSS + Vanilla JS
AI Engine	Anthropic Claude
Charts	Chart.js
Deployment	Render / Railway / Vercel

 Quick Start
-Clone Repository
git clone https://github.com/your-username/bridgefi.git
cd bridgefi

-Install Dependencies
pip install -r requirements.txt
3️⃣ Run the App
python app.py

Open: http://localhost:5000

Environment Setup (Optional)
cp .env.example .env

Add:

ANTHROPIC_API_KEY=your_api_key
SECRET_KEY=random_string
 No API key? No problem — mock AI still works.

🌐 Deployment
🟢 Render
Connect GitHub repo
Add environment variables
Deploy
🟣 Railway
railway login
railway init
railway up

 AI Capabilities

Powered by Claude Sonnet 4, BridgeFi can:

Extract structured skills from JDs
Identify hidden job expectations
Generate real-world mini projects
Provide match scoring + reasoning

📊 Ghosting Prediction Engine

BridgeFi uses a smart heuristic model based on:

Days since applying (sigmoid curve)
Company type (FAANG bias)
Department trends
Application timing

Result: Probability of getting ghosted

📁 Project Structure
bridgefi/
│
├── app.py              # Main Flask app
├── requirements.txt
├── Procfile
├── .env.example
│
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── applicant.html
│   ├── recruiter.html
│   └── analyzer.html
│
└── static/
    ├── css/style.css
    └── js/main.js


✅ Dual-sided platform (rare)
✅ Solves real pain: ghosting + skill gap
✅ AI + analytics + automation combined
✅ Works without API key (demo-ready)
✅ Clean, deployable full-stack system

Team
Rishi Raj (24BCE10149)
Arnab Kumar (24BCE11017)
Swastik Sinha (24BEY10075)
Abhilash Singh (24BCE10706)

🎓 VIT Bhopal — CSE / AI / Automation

“BridgeFi doesn’t just match candidates to jobs — it explains why they don’t match and shows them how to fix it.”

📄 License

MIT License
