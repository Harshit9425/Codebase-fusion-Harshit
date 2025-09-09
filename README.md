<<<<<<< HEAD logo

A collaborative, real-time code editor where users can seamlessly code together. It provides a platform for multiple users to enter a room, share a unique room ID, and collaborate on code simultaneously.

GitHub contributors GitHub Repo stars GitHub issues GitHub pull requests GitHub License Visitors

🔮 Features
💻 Real-time collaboration on code editing across multiple files
📁 Create, open, edit, save, delete, and organize files and folders
💾 Option to download the entire codebase as a zip file
🚀 Unique room generation with room ID for collaboration
🌍 Comprehensive language support for versatile programming
🌈 Syntax highlighting for various file types with auto-language detection
🚀 Code Execution: Users can execute the code directly within the collaboration environment
⏱️ Instant updates and synchronization of code changes across all files and folders
📣 Notifications for user join and leave events
👥 User presence list with online/offline status indicators
💬 Real-time group chatting functionality
🎩 Real-time tooltip displaying users currently editing
💡 Auto suggestion based on programming language
🔠 Option to change font size and font family
🎨 Multiple themes for personalized coding experience
🎨 Collaborative Drawing: Enable users to draw and sketch collaboratively in real-time
🤖 Copilot: An AI-powered assistant that generates code, allowing you to insert, copy, or replace content seamlessly within your files.
🚀 Live Preview
You can view the live preview of the project here.

💻 Tech Stack
React TypeScript React Router Tailwind CSS NodeJS ExpressJS Socket io Git GitHub Vercel Docker

⚙️ Installation
Method 1: Manual Installation
Fork this repository: Click the Fork button located in the top-right corner of this page.

Clone the repository:

git clone https://github.com/<your-username>/Code-Sync.git
Create .env file: Inside the client and server directories create .env and set:

Frontend:

VITE_BACKEND_URL=<your_server_url>
Backend:

PORT=3000
Install dependencies:

npm install     # Run in both client and server directories
Start the servers: Frontend:

cd client
npm run dev
Backend:

cd server
npm run dev
Access the application:

http://localhost:5173/
🎥 Need help with the setup?
👉 Watch this video for a step-by-step guide.

Method 2: Docker Installation
Install Docker Desktop:

Download and install Docker Desktop from Docker’s official website.
Verify installation:
docker --version
Pull Docker Images:

# Pull Backend Image
docker pull sahilatahar/code-sync-server:latest

# Pull Frontend Image
docker pull sahilatahar/code-sync-client:latest
Run Docker Containers:

# Run Backend Container (Port 3000)
docker run -d -p 3000:3000 --name code-sync-server sahilatahar/code-sync-server:latest

# Run Frontend Container (Port 5173)
docker run -d -p 5173:5173 --name code-sync-client sahilatahar/code-sync-client:latest
Access the application:

http://localhost:5173/
🔮 Features for Next Release
Admin Permission: Implement an admin permission system to manage user access levels and control over certain platform features.
🤝 Contribute
We welcome contributions to make Code Sync even better! Follow the contribution guidelines to get started.

🌟 Support Us
If you find this helpful or valuable, please consider 🌟 starring the repository. It helps us gain visibility and encourages further development.

🧾 License
This project is licensed under the MIT License.

🌟 Appreciation for Resources
Special thanks to:

EMKC for providing the Piston API:

Piston Repository
Piston Docs
Tldraw contributors:

Tldraw Repository
Tldraw Documentation
Pollinations AI:

Pollinations Repository
Pollinations Docs
✍️ About Developer
Sahil Atahar
Sahil Atahar


======= <<<<<<< HEAD # React + TypeScript + Vite ======= <<<<<<< HEAD # React + Vite >>>>>>> 99fcdb8aaf8e5cb2aad2b23093ac94df9a40acdf
This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

@vitejs/plugin-react uses Babel for Fast Refresh
@vitejs/plugin-react-swc uses SWC for Fast Refresh
Expanding the ESLint configuration
<<<<<<< HEAD If you are developing a production application, we recommend updating the configuration to enable type-aware lint rules:

export default tseslint.config({
  extends: [
    // Remove ...tseslint.configs.recommended and replace with this
    ...tseslint.configs.recommendedTypeChecked,
    // Alternatively, use this for stricter rules
    ...tseslint.configs.strictTypeChecked,
    // Optionally, add this for stylistic rules
    ...tseslint.configs.stylisticTypeChecked,
  ],
  languageOptions: {
    // other options...
    parserOptions: {
      project: ['./tsconfig.node.json', './tsconfig.app.json'],
      tsconfigRootDir: import.meta.dirname,
    },
  },
})
You can also install eslint-plugin-react-x and eslint-plugin-react-dom for React-specific lint rules:

// eslint.config.js
import reactX from 'eslint-plugin-react-x'
import reactDom from 'eslint-plugin-react-dom'

export default tseslint.config({
  plugins: {
    // Add the react-x and react-dom plugins
    'react-x': reactX,
    'react-dom': reactDom,
  },
  rules: {
    // other rules...
    // Enable its recommended typescript rules
    ...reactX.configs['recommended-typescript'].rules,
    ...reactDom.configs.recommended.rules,
  },
})
======= If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the TS template for information on how to integrate TypeScript and typescript-eslint in your project.
CodeFusionX
This repo is of CodeFusionX - an Online IDE with videocalling and live chat feature with real-tile syncing and file management

cea73941f9df55dbc5b008ebaa817eb385f6d591 99fcdb8aaf8e5cb2aad2b23093ac94df9a40acdf 69f87acd5fceac901ff12f180853552741d48c73
