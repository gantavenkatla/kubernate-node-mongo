# kubernate-node-mongo
Node with Mongo db and deploy in kubernate with Minikube or Rancher Desktop

Steps with MiniKube : 

1) brew install minikube
2) minikube start
3) minikube status
4) kubectl get all
5) kubectl get pods
6) kubectl apply -f mongo-config.yaml
7) kubectl apply -f mongo-secret.yaml
8) kubectl apply -f mongo.yaml
9) kubectl apply -f webapp-service.yaml
10) kubectl apply -f webapp.yaml
11) kubectl get svc
12) kubectl get node -o wide
