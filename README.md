# PSUSphere

## Project Description
PSUSphere is a Django website for managing university colleges, programs, students, and campus organizations.

## Features
- View colleges and course programs.
- Manage student information.
- Manage campus organizations and members.
- Use the Django admin dashboard.

## Technologies
- Python and Django
- Docker and Docker Compose
- SQLite

## How to Run

### Development Setup

1. Clone this repository.
2. Open the project folder.
3. Run:

   ```bash
   docker compose up --build
   ```

4. Open http://localhost:8000 in your browser.

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

https://hub.docker.com/r/nyfcabral/psusphere

## Author
Nicole Ynarhosenne Faith F. Cabral