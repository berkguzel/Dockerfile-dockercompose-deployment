This repository shows how to write Dockerfile, docker-compose.yaml and deployment.yaml files for a Flask project.

# Docker
1. Go into the file where Dockerfile is, run the `docker build -t #yourtag` .
1. Run `docker run -d -p 5000:5000 #yourtag` .
1. Run `curl localhost:5000`.

# Docker Compose
1. Go into the correct directory and run `docker-compose build` .
1. Run `docker-compose up -d` .
1. Run `curl localhost:5000` .

# Kubernetes
1. Go into the correct directory and run `kubectl apply -f deployment.yaml` .
1. Run `curl localhost:5000` .
