🎬 LIGHTS CAMERA CODE — Movie Portal
🌟 Overview

LIGHTS CAMERA CODE is a modern movie-based web application showcasing detailed film data — trailers, collections, and box-office analytics.
The project provides an interactive experience for fans to explore top-grossing movies, watch trailers, and analyze hit ratios based on budget and revenue.

💡 Features

🎥 Movie Gallery: Displays all movies with posters, release years, and trailers.

💰 Box Office Analyzer: Enter movie budget & collection to see if it’s a Hit, Super Hit, Blockbuster, or Flop.

📊 Top Grossers Carousel: Highlights the biggest box office hits.

🔐 Demo Login Page: Access the main dashboard after signing in with any credentials.

🌗 Dark Cinematic Theme: Sleek, immersive design optimized for all devices.

🛠️ Tech Stack
Layer	Technology Used
Frontend	HTML5, CSS3, JavaScript
Backend	Node.js, Express.js
Database	MongoDB (optional integration)
Version Control	Git & GitHub
Hosting	Vercel / Render / Localhost
🚀 Setup & Run Locally

Follow these steps to set up the project on your system:

# 1️⃣ Clone the repository
git clone https://github.com/kalyan4518/LIGHTS_CAMERA_CODE_A3.git

# 2️⃣ Go to the project folder
cd LIGHTS_CAMERA_CODE_A3

# 3️⃣ Install dependencies
npm install

# 4️⃣ Run the app
npm run dev


The app runs by default on http://localhost:5000/

🧮 Movie Analyzer Logic
Budget (₹ Cr)	Collection (₹ Cr)	Verdict
< Collection × 1.1	Loss	❌ Flop
≥ Budget × 1.2	Average	⚙️ Average
≥ Budget × 1.5	Hit	✅ Hit
≥ Budget × 3	Blockbuster	🌟 Blockbuster
≥ Budget × 5	Industry Hit	🏆 Industry Hit
📂 Folder Structure
LIGHTS_CAMERA_CODE_A3/
│
├── server.js             # Node.js server entry
├── index.html            # Main page
├── login.html            # Demo login screen
├── style.css             # Styling for pages
├── /public               # Static assets (images, videos)
├── /scripts              # JS files
└── README.md             # Project documentation

👨‍💻 Developers
U.VARSHITH VARMA
V.KALYAN VENKAT
S. RITHVIK

🎥 Passionate about Web Development, Design & Indian Cinema

📜 License

This project is open source under the MIT License.
Feel free to use, modify, and build upon it with credit.
