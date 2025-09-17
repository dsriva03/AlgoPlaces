# 🧠 AlgoPlaces

## A Smarter Way to Master Algorithms

AlgoPlaces is an AI-assisted web platform built to help developers and students build strong algorithmic thinking through interactive problem-solving. With personalized strategies, curated problem sets, and AI-driven insights, it’s your intelligent sidekick for interview prep and beyond.

---

## ✨ Key Capabilities

- **Custom AI Strategy Breakdown**  
  Receive clear, tailored explanations for any algorithmic problem you input—step-by-step.

- **Smart Practice Suggestions**  
  Get personalized practice problem recommendations to sharpen your skills.

- **Interview Relevance Scoring**  
  See how likely a problem is to appear in coding interviews based on frequency and topic trends.

- **Learning History & Progress**  
  Your past sessions are saved so you can track growth and revisit strategies.

- **Secure Google Sign-In**  
  Login and manage your sessions securely using Google OAuth.

- **Fast, Clean UI**  
  Built with Tailwind CSS for a modern and responsive user experience.

- **Real-Time AI Feedback**  
  Submit a problem and receive instant suggestions and guidance from OpenAI-powered models.

---

## 🧰 Tech Stack

### Frontend

- React 18 (with Hooks)
- React Router
- Tailwind CSS
- Webpack
- Google OAuth

### Backend

- Node.js + Express.js
- MongoDB + Mongoose
- OpenAI API Integration
- JWT Authentication
- CORS

### Dev Tools

- Webpack Dev Server
- Nodemon
- PostCSS + Babel

---

## 🔧 Requirements

Ensure you have the following installed:

- Node.js (v14+)
- npm (v6+)
- MongoDB (Atlas or local)
- OpenAI API Key
- Google OAuth Credentials

---

## 🛠️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/JoshuaHirakawa/AlgoPlaces.git
cd AlgoPlaces
```
### 2. Install Dependencies

```bash
npm install
```
### 3. Configure Environment Variables

Create a `.env` file in the root directory and add:

```env
OPENAI_API_KEY=your_openai_key
GOOGLE_CLIENT_ID=your_client_id
GOOGLE_CLIENT_SECRET=your_client_secret
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```

---

### 4. Start the App

#### Recommended (one command):

```bash
npm run dev:colored
```

- Frontend: [http://localhost:8080](http://localhost:8080)  
- Backend API: [http://localhost:3000](http://localhost:3000)

#### Alternative Options:

- Full stack dev mode:

```bash
npm run dev:full
```

- Run in two terminals:

**Terminal 1 (Backend):**

```bash
npm run server
```

**Terminal 2 (Frontend):**

```bash
npm run client
```

---

### Production Build

```bash
npm run build
```

---

## 🚦 How to Use

1. Sign in with your Google account  
2. Submit any algorithmic problem  
3. Get a personalized, step-by-step AI strategy  
4. Practice recommended problems  
5. Track your learning history  
6. Explore interview prep tools

---

## 🗂️ File Structure

```
AlgoPlaces/
├── src/                   # React frontend
│   ├── components/        # UI components
│   ├── assets/            # Static images
│   ├── styles/            # Tailwind and custom CSS
│   └── index.js           # App entry point
├── server/                # Express backend
│   ├── controllers/       # API logic
│   ├── models/            # Mongoose schemas
│   ├── routes/            # Route definitions
│   └── server.js          # App server
├── .env.example
├── package.json
├── tailwind.config.js
├── webpack.config.js
└── README.md
```

---

## 📡 API Endpoints

| Method | Endpoint         | Description                     |
|--------|------------------|---------------------------------|
| POST   | /api/strategy     | Generate AI strategy            |
| GET    | /api/history      | Retrieve user session history   |
| POST   | /api/history      | Save a new problem session      |
| PUT    | /api/history      | Update an existing session      |

---

## 🤝 Contributions

We welcome your ideas and improvements!

1. Fork this repo  
2. Create a feature branch  
3. Commit your changes  
4. Push the branch  
5. Open a pull request 🚀

---

## 📜 License

Licensed under the MIT License. See `LICENSE` for full details.

---

## 👥 Built With Love By

- Aditi Srivastava – Full-Stack Developer  
- Joshua Hirakawa – Full-Stack Developer  
- Amrita Bahadur – Full-Stack Developer  
- Winston Ludlam – Full-Stack Developer

---

## 🙌 Special Thanks

- OpenAI (for GPT-4 integration)  
- Google OAuth  
- MongoDB  
- The amazing React + Node.js open-source communities

---

## 📬 Support

- Check the **Issues** tab  
- Open a new issue with details  
- Reach out to the dev team directly
