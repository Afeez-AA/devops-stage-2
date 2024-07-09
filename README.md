# Full-Stack FastAPI and React Template

Welcome to the Full-Stack FastAPI and React template repository. This repository serves as a demo application for interns, showcasing how to set up and run a full-stack application with a FastAPI backend and a ReactJS frontend using ChakraUI.

## Project Structure

The repository is organized into two main directories:

- **frontend**: Contains the ReactJS application.
- **backend**: Contains the FastAPI application and PostgreSQL database integration.

Each directory has its own README file with detailed instructions specific to that part of the application.

## Getting Started

To get started with this template, please follow the instructions in the respective directories:

- [Frontend README](./frontend/README.md)
- [Backend README](./backend/README.md)

## STEPS

## Cloning the Repository
To get started, clone the repository:

```bash
git clone https://github.com/Afeez-AA/devops-stage-2.git
cd devops-stage-2
```

## For Local Deployment
To run the application locally, use the following command:
```bash
docker-compose -f docker-compose.yml up

```

## Production Deployment
For production deployment:
1. Rename the production Docker Compose file:
 ```bash
 cp docker-compose.prod.yml docker-compose.yml
```
2. Update docker-compose.yml with necessary details like your domain name.

3. Run the application:
```bash
docker-compose up
```
*Kindly note that plan is still ongoing to make one docker compose file usable by both local and production by utilizing variables*




