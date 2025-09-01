# Docker---commands-task
Install Docker
Commands executed on EC2:
```bash
sudo apt-get update -y
sudo apt-get install -y docker.io
sudo systemctl start docker
sudo systemctl enable docker
Pulled the hello-world image and listed available images:
docker pull hello-world
docker images

📦 4. Docker Containers
Ran the container and listed all containers:
docker run hello-world
docker ps -a
Output confirmed Docker is working correctly.

💾 5. Docker Volumes
Created and listed a Docker volume:
docker volume create myvolume
docker volume ls

🌐 6. Docker Networks
Listed networks and inspected the default bridge network:
docker network ls
docker network inspect bridge

✅ Conclusion
Successfully:
Installed Docker on an EC2 instance
Explored core Docker commands:
Images
Containers
Volumes
Networks
