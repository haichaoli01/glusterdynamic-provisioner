# Build command

$ sudo docker buildx create --name mybuilder --driver docker-container
$ sudo docker buildx use mybuilder
$ sudo docker run --rm --privileged tonistiigi/binfmt --install all
$ sudo docker login
$ sudo docker buildx build -t dockerhubName/glusterdynamic-provisioner:v1.3 --platform=linux/arm64,linux/amd64 . --push
