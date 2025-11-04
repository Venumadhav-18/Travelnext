🧭 TravelNest – Homestays & Local Guide Services
🌍 Project Overview

TravelNest is a React-based front-end web application designed to help users discover and book homestays, flights, airport transfers, and local tours.
It provides a one-stop platform for travelers to plan their trips conveniently and explore destinations with comfort and ease.

This project was developed as part of the Front-End Development SDP Review at KL University, demonstrating the use of React, Vite, Git, and Netlify for modern web application development and deployment.

💡 Features

✅ Explore Homestays across major Indian cities
✅ Book Flights and Airport Transfers easily
✅ Discover Local Tours & Activities
✅ Responsive and modern UI with glowing theme
✅ Persistent data using LocalStorage
✅ Continuous Deployment using Netlify + GitHub

🧱 Tech Stack
Category	Technology
Frontend Framework	React (Vite)
Styling	CSS3, Responsive Design
State Management	React Hooks, Context API
Version Control	Git & GitHub
Deployment	Netlify (Continuous Integration)
⚙️ Installation & Setup

To run this project locally:

# Clone the repository
git clone https://github.com/Venumadhav-18/Travelnext.git

# Go into the project folder
cd Travelnext

# Install dependencies
npm install

# Start the development server
npm run dev


Then open 👉 http://localhost:5173 in your browser.

🚀 Deployment

This project is live and hosted on Netlify via continuous deployment from GitHub.
Visit the live site here:
🔗 https://travelnest-react.netlify.app

🧩 Project Structure
travelnest/
├─ public/               # Static assets and images
├─ src/
│  ├─ components/        # Reusable UI components
│  ├─ pages/             # Individual React pages (Home, Homestays, Guide, Contact)
│  ├─ context/           # Global Context (state management)
│  ├─ App.jsx            # Root app component
│  ├─ main.jsx           # Entry point for React
│  └─ styles.css         # Custom styling
├─ package.json
└─ vite.config.js

🧠 Challenges Faced

Git submodule issue in src/ folder during deployment
🔹 Resolved by removing nested .git folder and re-adding src as a normal directory

Netlify build error during first deployment
🔹 Fixed by reconfiguring Git integration and triggering a fresh deploy

🏆 Outcome

This project demonstrates:

Modern front-end development using React

Proper component design & routing

Version control using GitHub

Successful CI/CD deployment on Netlify

👨‍💻 Developed by

Venu madhav reddy
B.Tech CSE, KL University
