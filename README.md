# Docker Notes App

## Student Information
- **Name:** Faylon, Mae Angela
- **Student ID:** 24-075
- **Course:** BSIT 3 - PYTHON
- **Activity:** Docker Hands-on Lab

## Project Description
This repository contains a full-stack containerized web application integrating a React/Vite frontend, a .NET Web API backend, and a PostgreSQL database. Docker Compose is utilized to orchestrate and manage all services within independent, isolated environments.

## Technologies Used
- React & Vite
- .NET Web API
- PostgreSQL
- Docker & Docker Compose

## Project Structure
docker-lab/
├── api/
├── web/
├── screenshots/
│   ├── terminal-output.png
│   └── browser-app.png
├── docker-compose.yml
├── .env
├── .gitignore
└── README.md

## How to Run & Setup Instructions
Prerequisites: Ensure that Docker Desktop and Git are installed and running on your system.

1. **Clone the repository**: Download the project source code from GitHub to your local machine.
   ```bash
   git clone https://github.com/maeangela12/IPT102-Docker-Hands-on-Lab.git


Build and launch the application: Compile the container images from scratch and spin up all services in detached mode using Docker Compose.

docker compose up --build
Verify running containers: Check the status to ensure all multi-service containers are operating correctly.


## docker compose ps
Application URLs
Frontend App: http://localhost:3000

To safely halt the containers while retaining your application data:

docker compose down

## Screenshots
The screenshots/ directory holds pictorial verification of successful execution:

terminal-output.png — Console logs confirming successful container builds and database initialization (up 7/7).

browser-app.png — The user interface rendering properly inside the browser..

## Conclusion
This project illustrates the fundamental concepts of application containerization, multi-tier service architecture, and environment management utilizing Docker and Docker Compose.