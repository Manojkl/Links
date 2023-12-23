kubectl get deployment
docker build -t manoj/fast-api .
eval $(minikube docker-env)  
minikube start --driver qemu --network socket_vmnet --insecure-registry=true
kubectl get pods
kubectl delete deployment fastapi-deployment 
kubectl apply -f fastapi-deployment.yaml  

https://sweetcode.io/how-to-dockerize-and-deploy-a-fast-api-application-to-kubernetes-cluster/#:~:text=We%20started%20by%20creating%20and,application%20to%20the%20Minikube%20Kubernetes. 

https://stackoverflow.com/questions/56392041/getting-errimageneverpull-in-pods

S-ZtIw7w63t6