# PSUSphere - Dockerized Django Application

## Project Description

PSUSphere is a Django-based web application for managing university colleges, academic programs, students, and campus organizations.

This project focuses on containerizing PSUSphere using **Docker and Docker Compose**, making the application easier to build, run, and deploy across different machines.

## Technologies Used

- Python
- Django
- SQLite
- Docker
- Docker Compose

## How to Run

### Development Setup

**Requirements:** Docker Desktop must be installed and running.

1. Clone this repository:

   ```bash
   git clone https://github.com/nyfastra/PSUSphere-Docker.git
   ```

2. Navigate to the project folder:

   ```bash
   cd PSUSphere-Docker
   ```

3. Build and start the application:

   ```bash
   docker compose up --build
   ```

4. Open the application in your browser:

   http://localhost:8000

### Client Setup

1. Copy `for_client/docker-compose.yml` into a folder.
2. Open that folder in your terminal.
3. Run:

   ```bash
   docker compose up -d
   ```

4. Open http://localhost:8000 in your browser.

Docker will download the image from Docker Hub if needed.

## Docker Hub

Docker image:
https://hub.docker.com/r/nyfcabral/psusphere

## Authors

- Nicole Ynarhosenne Faith F. Cabral
- Dayang Natassia Erliya M. Datu Amir Bahar