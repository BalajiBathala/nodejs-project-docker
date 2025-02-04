# nodejs-project-dockerr

Overview:
This repository contains a simple Node.js application deployed using Docker. The app runs an HTTP server and serves a response when accessed.
📦 nodejs-project-dockerr  
├── 📜 index.js           # Main Node.js application  
├── 📜 package.json       # Project metadata and dependencies  
├── 📜 package-lock.json  # Lockfile for dependencies  
├── 📜 Dockerfile         # Docker configuration  
└── 📜 README.md          # Project documentation  

Features
* Lightweight Docker image (<250MB)
* Uses Alpine-based Node.js image
* Runs on port 80 inside the container
* Works seamlessly with Docker Hub & AWS
Getting Started
1. Clone the Repository
  git clone https://github.com/BalajiBathala/nodejs-project-dockerr.git
  cd nodejs-project-dockerr
2. Build the Docker Image
  docker build -t my-node-app .
3. Run the Container
   docker run -d -p 80:80 --name node-container my-node-app
4. Test the Application
   Open your browser and visit:http://localhost

