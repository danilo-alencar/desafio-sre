COMANDO MINUKUBE:

minikube start
minikube addons enable ingress-dns
minikube addons enable ingress-dns
minikube addons list

HELM:
helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
helm install my-kube-prometheus-stack prometheus-community/kube-prometheus-stack --version 58.1.2
![image](https://github.com/danilo-alencar/desafio-sre/assets/46189256/b93e0672-18cb-42e5-99d5-712a8d5b7153)


Criar infra kuberbenetes:
kubectl create -f deploy.yml
kubectl create -f service.yaml
kubectl create -f ingress.yaml

![image](https://github.com/danilo-alencar/desafio-sre/assets/46189256/9ab7166b-a6bd-451b-ac79-d77f37bcd80b)
![image](https://github.com/danilo-alencar/desafio-sre/assets/46189256/7db0c329-f227-4b4d-a43c-cf00078ff596)


