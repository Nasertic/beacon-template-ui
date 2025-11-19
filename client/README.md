# beacon-template-ui

## Deployment

1. Prerequisites

Make sure Docker and Docker Compose are installed on your machine or use a Codespace that has Docker available.

2. Clone the repository
Open your terminal and navigate to the folder where you want to store the project.

Then, clone the Beacon Template UI repository:
```bash
git clone https://github.com/EGA-archive/beacon-template-ui.git
```
Once the cloning process finishes, go inside the project directory:
```bash
cd beacon-template-ui
```
This means you’re in the correct directory and ready to start the application.

3. Start the application with Docker

In your terminal run:
```
docker compose up -d --build
```

4. Verify the Container

To confirm the container is running:
```bash
docker ps
```
Expected output:
```
CONTAINER ID   IMAGE                       COMMAND                  CREATED         STATUS         PORTS                                         NAMES
ecb9f5666960   beacon-template-ui-client   "docker-entrypoint.s…"   7 minutes ago   Up 7 minutes   0.0.0.0:3000->3000/tcp, [::]:3000->3000/tcp   template-ui
```
If it’s visible, the UI is running locally at: http://localhost:3025