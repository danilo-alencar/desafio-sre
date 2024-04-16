COMANDO MINUKUBE:

minikube start
minikube addons enable ingress-dns
minikube addons enable ingress-dns
minikube addons list

Criar infra kuberbenetes:
kubectl create -f deploy.yml
kubectl create -f service.yaml
kubectl create -f ingress.yaml

