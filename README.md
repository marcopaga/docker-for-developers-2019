[![License: CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/4.0/80x15.png)](https://creativecommons.org/licenses/by-sa/4.0/

# Docker for Developers

## Cheat Sheet

https://www.docker.com/sites/default/files/Docker_CheatSheet_08.09.2016_0.pdf

## kubernetes on minikube

```
minikube start --vm-driver virtualbox --memory 4096 --cpus 3

kubectl apply -f kubernetes.yml

http $(minikube service locations --url)/locations 

http $(minikube service locations --url)/locations/Solingen

http "$(minikube service maintenance --url)/update?firmwareVersion=2"

http $(minikube service maintenance --url)/metrics
kubectl delete pod,service,deployment,secret -l app=workshop

```