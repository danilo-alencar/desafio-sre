DESAFIO SRE:

COMANDO MINUKUBE:

minikube start

minikube addons enable ingress-dns
minikube addons enable ingress-dns
minikube addons list
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>


Instalar Grafana e promethues: 


helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
helm install my-kube-prometheus-stack prometheus-community/kube-prometheus-stack --version 58.1.2
![image](https://github.com/danilo-alencar/desafio-sre/assets/46189256/b93e0672-18cb-42e5-99d5-712a8d5b7153)
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>

Prometheus funcionando:

![image](https://github.com/danilo-alencar/desafio-sre/assets/46189256/38c129fe-9837-495e-bba1-065151268cae)
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>

DataSource:
![image](https://github.com/danilo-alencar/desafio-sre/assets/46189256/3385990a-e2cd-4054-b0f3-14301daeeb7d)
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>


Grafana:
![image](https://github.com/danilo-alencar/desafio-sre/assets/46189256/24f73add-27f9-4dfa-b3a0-e6812d813fb6)
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>

node-exporter

![image](https://github.com/danilo-alencar/desafio-sre/assets/46189256/49d6790d-8601-4f3c-9834-cce806b9d62f)
![image](https://github.com/danilo-alencar/desafio-sre/assets/46189256/842e19b2-eda4-47ef-83ea-af943423dd9a)
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>

Criar infra kuberbenetes:
kubectl create -f deploy.yml

kubectl create -f service.yaml

kubectl create -f ingress.yaml

![image](https://github.com/danilo-alencar/desafio-sre/assets/46189256/407cc9c7-7fe5-44db-9bb6-b61461426be0)


![image](https://github.com/danilo-alencar/desafio-sre/assets/46189256/32bdd04f-37d5-4a65-a97d-953a2a0dd386)

![image](https://github.com/danilo-alencar/desafio-sre/assets/46189256/ce67cc69-867d-416e-a1ca-0d2a3d8b3030)





