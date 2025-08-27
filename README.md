# 🚀 DevOps React + Node.js Project

This is a full-stack DevOps project showcasing Dockerized deployment of a React frontend and a Node.js backend, managed via GitHub Actions CI/CD pipeline.

---

## 🛠️ Tech Stack

- **Frontend**: React
- **Backend**: Node.js + Express
- **Containerization**: Docker, Docker Compose
- **CI/CD**: GitHub Actions
- **Deployment**: Localhost / Render

---

## 📁 Folder Structure
.
├── client/               # React frontend
├── server/               # Node.js backend
├── docker-compose.yml    # Compose file to run both together
└── .github/workflows/    # CI/CD pipeline config

---

## 🐳 Docker Usage

### 🔧 Build & Run (Locally)

```bash
docker-compose up --build

	•	React app → http://localhost:3000
	•	Backend API → http://localhost:5001/api

⚙️ GitHub Actions (CI/CD)
	•	Runs docker-compose build on every push to main
	•	You can integrate deployment steps (e.g., to Render or DockerHub)

⸻
curl http://localhost:5001/api
# Output: { "message": "Hello from the backend!" }

🌐 Deployment (Optional)

You can deploy this app on:
	•	Render (Dockerized backend)
	•	Railway / Fly.io
	•	GCP / AWS / Azure

⸻

🙌 Author

Made by [Ananya Tiwari]

