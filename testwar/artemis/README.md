# ActiveMQ Artemis

Build Docker Image

docker build -f ./Dockerfile-adoptopenjdk-11 -t andidroid/artemis-2.19.0-jdk11 .

 docker push  andidroid/artemis-2.19.0-jdk11


kubectl kustomize testwar/artemis/ > out.yaml
kubectl apply -f out.yaml