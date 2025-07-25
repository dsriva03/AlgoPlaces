🧠 AlgoPlaces

A Smarter Way to Master Algorithms

AlgoPlaces is an AI-assisted web platform built to help developers and students build strong algorithmic thinking through interactive problem-solving. With personalized strategies, curated problem sets, and AI-driven insights, it’s your intelligent sidekick for interview prep and beyond.

⸻

✨ Key Capabilities
	•	Custom AI Strategy Breakdown
Receive clear, tailored explanations for any algorithmic problem you input—step-by-step.
	•	Smart Practice Suggestions
Get personalized practice problem recommendations to sharpen your skills.
	•	Interview Relevance Scoring
See how likely a problem is to appear in coding interviews based on frequency and topic trends.
	•	Learning History & Progress
Your past sessions are saved so you can track growth and revisit strategies.
	•	Secure Google Sign-In
Login and manage your sessions securely using Google OAuth.
	•	Fast, Clean UI
Built with Tailwind CSS for a modern and responsive user experience.
	•	Real-Time AI Feedback
Submit a problem and receive instant suggestions and guidance from OpenAI-powered models.

⸻

🎥 Demo Preview

AI Strategy Generator	Practice & Progress
	


⸻

🧰 Tech Stack

Frontend
	•	React 18 (Hooks, functional components)
	•	React Router (Routing)
	•	Tailwind CSS (Design system)
	•	Webpack (Bundling)
	•	Google OAuth (Auth)

Backend
	•	Node.js + Express.js
	•	MongoDB + Mongoose
	•	OpenAI API Integration
	•	JWT Auth
	•	CORS Setup

Developer Tools
	•	Webpack Dev Server (Frontend hot reload)
	•	Nodemon (Backend auto-restart)
	•	PostCSS + Babel (JS + CSS compatibility)

⸻

🔧 Requirements

Before you begin, ensure you have:
	•	Node.js (v14+)
	•	npm (v6+)
	•	A MongoDB cluster or local instance
	•	OpenAI API key
	•	Google OAuth credentials

⸻

🛠️ Getting Started

1. Clone the Repository

git clone https://github.com/JoshuaHirakawa/AlgoPlaces.git
cd AlgoPlaces

2. Install Project Dependencies

npm install

3. Set Up Environment Variables

Create a .env file at the root level:

OPENAI_API_KEY=your_openai_key
GOOGLE_CLIENT_ID=your_client_id
GOOGLE_CLIENT_SECRET=your_client_secret
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret

4. Launch the App

One-Step Dev Environment

npm run dev:colored

	•	Frontend: http://localhost:8080
	•	Backend API: http://localhost:3000

Alternate Commands
	•	Full dev mode: npm run dev:full
	•	Separate terminals:
	•	Terminal 1: npm run server
	•	Terminal 2: npm run client

Production Build

npm run build


⸻

🚦 How to Use
	1.	Sign in with Google
	2.	Submit any algorithmic question
	3.	View a personalized, step-by-step strategy
	4.	Practice similar problems with curated suggestions
	5.	Track your progress with saved history
	6.	Use interview tags to prep smartly

⸻

🗂️ File Structure

AlgoPlaces/
├── src/                  # React frontend
│   ├── components/       # UI components (Dashboard, LoginPage, Strategy, etc.)
│   ├── assets/           # Images and static assets
│   ├── styles/           # Tailwind + custom CSS
│   └── index.js          # Frontend entry point
├── server/               # Node backend
│   ├── controllers/      # Logic for handling routes
│   ├── models/           # Mongoose schemas
│   ├── routes/           # API endpoints
│   └── server.js         # App entry
├── .env.example
├── webpack.config.js
├── tailwind.config.js
├── package.json
└── README.md


⸻

📡 API Endpoints

Method	Endpoint	Description
POST	/api/strategy	Generate strategy from user query
GET	/api/history	Fetch saved session history
POST	/api/history	Save a new session
PUT	/api/history	Update an existing session


⸻

🤝 Contributions

We’d love your input! To contribute:
	1.	Fork the repo
	2.	Create a feature branch
	3.	Commit and push your changes
	4.	Submit a pull request
	5.	Wait for review and merge 🚀

⸻

📜 License

This project is distributed under the MIT License.

⸻

👥 Built With Love By
	•	Aditi Srivastava – Full-Stack Developer
	•	Joshua Hirakawa – Full-Stack Developer
	•	Amrita Bahadur – Full-Stack Developer
	•	Winston Ludlam – Full-Stack Developer

⸻

🙌 Special Thanks
	•	OpenAI for GPT model access
	•	Google for OAuth support
	•	MongoDB for database tools
	•	The open-source community that makes this work possible

⸻

📬 Support

Having issues?
	•	Check existing GitHub issues
	•	Open a new one if needed
	•	Or reach out directly through the project team

⸻