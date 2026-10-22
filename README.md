# Node.js Demo App - CI/CD Pipeline

## Project Overview
This project demonstrates automated build and Docker image deployment using GitHub Actions.

## Technologies Used
- Node.js
- Express
- GitHub
- GitHub Actions
- Docker
- Docker Hub

## Application
The Node.js application runs on port 3000 and responds to HTTP requests.

## CI/CD Workflow
1. Code is pushed to the main branch.
2. GitHub Actions checks out the source code.
3. Node.js dependencies are installed.
4. The configured test command runs.
5. Docker builds the application image.
6. The image is pushed to Docker Hub.

## Docker Hub Image
https://hub.docker.com/repository/docker/sravikareddy/nodejs-demo-app/tags

## Run Locally
Install dependencies:
npm install

Start the application:
node app.js

Open http://localhost:3000 in your browser.

## Security
Docker Hub credentials are stored in GitHub Actions repository secrets.
