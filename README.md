Este es el segundo laboratorio de Kubernetes.
Para correr aplique el despliegue y el servicio con

`kubectl apply -f modelPod.yaml`

`kubectl apply -f service.yaml`


Y si está hosteando k8s con docker desktop, conecte su puerto 8000 con el contenedor con el siguiente comando

`kubectl port-forward svc/model-service 8000:8000`

Este proceso ocupará su terminal.
