# Pre requisite
    Minikube or Kubernetes cluster
    Helm tiller installed on the kubenernetes or minikube

# Running on Minikube

    docker build -t hello-world-helm:v1 .
    kubectl helm upgrade  --install --values ./charts/python/values-dev.yaml
