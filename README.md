# Build command
sudo docker buildx build -t dockerhubName/glusterdynamic-provisioner:v1.3 --platform=linux/arm64,linux/amd64 . --push
