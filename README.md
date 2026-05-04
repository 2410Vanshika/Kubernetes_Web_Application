Kubernetes Scalable Web Application
 How to Run
1. Start Minikube
2. Build Docker image:
   docker build -t my-website ./website
3. Deploy:
   kubectl apply -f deployment.yaml
   kubectl apply -f service.yaml
4. Access:
   minikube service my-nginx-service
