COMANDO MINUKUBE:

minikube start
minikube addons enable ingress-dns
minikube addons enable ingress-dns
minikube addons list

HELM Instalar Grafana e promethues: 
helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
helm install my-kube-prometheus-stack prometheus-community/kube-prometheus-stack --version 58.1.2
![image](https://github.com/danilo-alencar/desafio-sre/assets/46189256/b93e0672-18cb-42e5-99d5-712a8d5b7153)

Prometheus funcionando:

![image](https://github.com/danilo-alencar/desafio-sre/assets/46189256/ebb901c3-2334-4636-b65c-c02432945912)

DataSource:
![image](https://github.com/danilo-alencar/desafio-sre/assets/46189256/586311fb-c538-47a2-b38d-ba99ce116099)


Grafana:
![image](https://github.com/danilo-alencar/desafio-sre/assets/46189256/24f73add-27f9-4dfa-b3a0-e6812d813fb6)


node-exporter

![image](https://github.com/danilo-alencar/desafio-sre/assets/46189256/49d6790d-8601-4f3c-9834-cce806b9d62f)
![image](https://github.com/danilo-alencar/desafio-sre/assets/46189256/842e19b2-eda4-47ef-83ea-af943423dd9a)


Criar infra kuberbenetes:
kubectl create -f deploy.yml
kubectl create -f service.yaml
kubectl create -f ingress.yaml

![image](https://github.com/danilo-alencar/desafio-sre/assets/46189256/9ab7166b-a6bd-451b-ac79-d77f37bcd80b)
![image](https://github.com/danilo-alencar/desafio-sre/assets/46189256/7db0c329-f227-4b4d-a43c-cf00078ff596)




