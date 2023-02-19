

### Command
> * **start minikube** `minikube start --cpus 2 --memory 4g --driver docker --profile polar`
> * **set key-cloak** `echo "127.0.0.1 polar-keycloak" | sudo tee -a /etc/hosts`
> * **load image** `minikube image load catalog-service  order-service dispatcher-service edge-service --profile polar`
> * **enable ingress** `minikube addons enable ingress --profile polar`
> * **start ingress** `minikube tunnel --profile polar`


