#  NGINX Reverse Proxy + Docker Compose Assignment

This project demonstrates a Docker-based microservice setup using **NGINX as a reverse proxy**, serving two backend services (Golang and Python Flask) over a **single entry point** using **Docker Compose**.

---
firstly configured the fikes in folders and wrote the dockerfiles and bilit image 
Project Structure

.
├── docker-compose.yml
├── nginx/
│ ├── nginx.conf
│ └── Dockerfile
├── service_1/ # Golang Service
│ ├── Dockerfile
│ ├── main.go
│ └── go.mod
├── service_2/ # Python Flask Service
│ ├── Dockerfile
│ ├── app.py
│ └── requirements.txt
└── README.me

## ✅ How to Run

1. Clone or download the repository  
2. In the root folder, run:

```bash
docker-compose up --build
Open the browser and test:

http://127.0.0.1:8080/service1/

http://127.0.0.2.:8080/service2/
the docker image which i bulit
![image](https://github.com/user-attachments/assets/47b927b3-122b-4702-941e-4aafe33a3df5)
everything is working good
wrote docker files and deployed through docker
