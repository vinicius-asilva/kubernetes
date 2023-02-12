# kubernetes


### deployment-nginx.yml
Provisiona 5 replicas do nginx
kubectl apply -f deployment-nginx.yml



### deploymentPostgress.yml
Cria um deployment postgress com armazenamento permanente
1. kubectl apply -f persitentVolume.yml
2. kubectl apply -f persistentVolumeClaim.yml
3. kubectl apply -f deploymentPostgres.yml

