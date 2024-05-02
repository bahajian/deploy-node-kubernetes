# Create Image file
```
docker build -t bahajian/basic-app:v0.0.1 .
docker push bahajian/basic-app:v0.0.1
```

#### For test the docker image you can run it
```
docker run -p 1338:1338 -d --name basic-app bahajian/basic-app:v0.0.1
```


## For installing the ingress nginx need to run this command inside the kubernetes cluster
https://kubernetes.github.io/ingress-nginx/deploy/#docker-desktop
```
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.10.1/deploy/static/provider/aws/deploy.yaml

```



# Deploy Nodejs application on Azure Kubernetes Service with CircleCI







[![CircleCI](https://circleci.com/gh/CIRCLECI-GWP/deploy-node-kubernetes.svg?style=svg)](https://github.com/CIRCLECI-GWP/deploy-node-kubernetes)

<p align="center"><img src="https://avatars3.githubusercontent.com/u/59034516"></p>

## Clone the repository:

run the following command on your terminal to clone the repository:

```bash
git clone https://github.com/CIRCLECI-GWP/deploy-node-kubernetes.git

cd deploy-node-kubernetes
```

## Install the dependencies

Install the dependencies using the following command:

```bash

npm install
```

## Running the application

```bash
node app.js
```

### About CircleCI Guest Writer Program

Reviewers: [Ron Powell][ron], [Stanley Ndagi][stan], [Amos Omondi][amos]

[blog]: https://circleci.com/blog/application-logging-with-flask/
[author]: https://github.com/mwaz
[ron]: https://github.com/ronpowelljr
[stan]: https://github.com/NdagiStanley
[amos]: https://github.com/amos-o
