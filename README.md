# Mini Project 1: Simple ML Model Deployment

Purpose: Deploy a simple ML model using a pre-trained model and to serve predictions
through an API endpoint.

1. This is a Git repository for the project which includes the ML model code and API
server code for Bike share API.
2. The API server is using a Python web framework FastAPI for serving the api.
3. GitHub Actions workflow triggers to automate model testing and deployment on
each push to the repository.
4. A Docker container is created for the API server with the necessary dependencies and
the pre-trained model.
5. Docker Hub is used to store the Docker image.
6. The Docker container is deployed on AWS EC2 using git Actions.
7. An API Gateway is used to expose the API endpoint securely.