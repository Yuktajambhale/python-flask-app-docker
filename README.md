# 🐍 Python Flask App (Dockerized)

A simple Flask web application built with Python and containerized using Docker.  
This project demonstrates how to easily build, run, and deploy a Flask app inside a Docker container.

---

## 📦 Features
- ✅ Lightweight Flask web server  
- ✅ Dockerized for easy deployment  
- ✅ Simple and beginner-friendly structure  
- ✅ Ready to run locally or in any container platform  

---

## 📁 Project Structure
python-flask-app-docker/
│
├── app.py # Main Flask application
├── Dockerfile # Docker build instructions
├── requirements.txt # Python dependencies
└── README.md # Project documentation


---

## ⚙️ Technologies Used
| Tool / Tech | Description |
|-------------|------------|
| 🐍 Python 3.9 | Programming language |
| 🌐 Flask     | Lightweight web framework |
| 🐳 Docker    | Containerization platform |

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone  https://github.com/Yuktajambhale/python-flask-app-docker.git
cd python-flask-app-docker
2️⃣ Build the Docker Image
docker build -t yukta27989/python-flask:0.0.2.RELEASE .

3️⃣ Run the Docker Container
docker run -d -p 8000:8000 --name flaskapp yukta27989/python-flask:0.0.2.RELEASE

4️⃣ Open the App in Browser

Open this URL:
👉 http://localhost:8000

You should see:

Hello from Flask in Docker!

🐳 Docker Hub Repository

You can find the Docker image here:
🔗 Docker Hub - yukta27989/python-flask

Pull the image directly:

docker pull yukta27989/python-flask:0.0.2.RELEASE

🐙 GitHub Repository

🔗 GitHub - Yuktajambhale/python-flask-app-docker

👩‍💻 Author

Yukta Jambhale
💡 Python | Flask | Docker Enthusiast
