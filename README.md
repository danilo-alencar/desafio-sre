COMANDO MINUKUBE:

minikube start
minikube addons enable ingress-dns
minikube addons enable ingress-dns
minikube addons list

Criar infra kuberbenetes:
kubectl create -f deploy.yml
kubectl create -f service.yaml
kubectl create -f ingress.yaml

![image](https://github.com/danilo-alencar/desafio-sre/assets/46189256/9ab7166b-a6bd-451b-ac79-d77f37bcd80b)


