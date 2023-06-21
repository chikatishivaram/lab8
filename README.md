$ sudo apt-get update
$ sudo apt-get install docker.io -y
$ sudo usermod -aG docker $USER && newgrp docker
$ curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
$ sudo install minikube-linux-amd64 /usr/local/bin/minikube
$ sudo snap install kubectl --classic
$ minikube start --driver=docker
$ minikube status
kubectl get pods
kubectl get svc
