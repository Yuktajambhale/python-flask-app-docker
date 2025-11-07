# 🐍 Python Flask App (Dockerized)

A simple **Flask web application** built with **Python** and containerized using **Docker**.  
This project demonstrates how to easily **build**, **run**, and **deploy** a Flask app inside a Docker container.

---

## 📦 Features
✅ Lightweight Flask web server  
✅ Dockerized for easy deployment  
✅ Simple and beginner-friendly structure  
✅ Ready to run locally or in any container platform  

---

## 📁 Project Structure
python-flask-app-docker/
│
├── app.py # Main Flask application
├── Dockerfile # Docker build instructions
├── requirements.txt # Python dependencies
└── README.md # Project documentation

yaml
Copy code

---

## ⚙️ Technologies Used

| Tool / Tech | Description |
|--------------|-------------|
| 🐍 **Python 3.9** | Programming language |
| 🌐 **Flask** | Lightweight web framework |
| 🐳 **Docker** | Containerization platform |

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Yuktajambhale/python-flask-app-docker.git
cd python-flask-app-docker
2️⃣ Build the Docker Image
bash
Copy code
docker build -t yukta27989/python-flask:0.0.1.RELEASE .
3️⃣ Run the Docker Container
bash
Copy code
docker run -d -p 5000:5000 --name flaskapp yukta27989/python-flask:0.0.1.RELEASE
4️⃣ Open the App in Browser
👉 http://localhost:5000

You should see:

Hello from Flask in Docker! 🚀

🐳 Docker Hub Repository
You can find the Docker image here:
🔗 Docker Hub - yukta27989/python-flask

To pull the image directly:

bash
Copy code
docker pull yukta27989/python-flask:0.0.1.RELEASE
🐙 GitHub Repository
🔗 GitHub - Yuktajambhale/python-flask-app-docker

👩‍💻 Author
Yukta Jambhale
Yukta Jambhale
💡 Python | Flask | Docker Enthusiast
