# udacity-suse-cloud-native-schorlarship

### Containerization

- docker build -t python-helloworld .
- docker images
- docker run -d -p 5000:5000 python-helloworld
- docker ps
- docker tag python-helloworld mavewrick1/python-helloworld:v1.0.0
- docker images
- docker push mavewrick1/python-helloworld:v1.0.0
- docker pull mavewrick1/python-helloworld:v1.0.0

### Create and deploy a kubernetes cluster using vagrant, virtual box and k3s

- vagrant up
- vagrant ssh
- curl -sfL https://get.k3s.io | sh
- sudo su
- kubectl get nodes
