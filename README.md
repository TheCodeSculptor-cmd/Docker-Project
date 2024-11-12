## Docker-Project
This project is a simple Docker setup that creates a Docker image. When this image is run as a container, it prints **"Hello, Captain!"** to the console.

## Project URL
This is a local Docker project from the roadmap.sh. You can find the project details [here](https://example.com/project-details).
## About
This project is designed to demonstrate how to create a basic Docker image using a lightweight Alpine Linux base image. It includes a simple Dockerfile that runs an `echo` command to display "Hello, Captain!" when the container is started.

## Getting Started
To run this project, you’ll need to have Docker installed on your machine. 

### Prerequisites
Ensure you have Docker installed on your machine. You can download and install Docker from [here](https://www.docker.com/products/docker-desktop/)
### Clone the Repository
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/TheCodeSculptor-cmd/Docker-Project.git
   cd hello-docker
   ```
   
2. Build the Docker Image:
Open a terminal in the project’s root directory (where the Dockerfile is located).
```bash
docker build -t hello-captain .
```
3. Run the following command to build the Docker image:
```bash
docker run hello-captain
```
4. Output:
 After running the container, you should see the following output in your terminal:
```bash 
Hello, Captain!

