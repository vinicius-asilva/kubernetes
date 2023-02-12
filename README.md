# kubernetes


### deployment-nginx.yml
Provisiona 5 replicas do nginx, execute com o comando:
```
kubectl apply -f deployment-nginx.yml
```



### deploymentPostgress.yml
Cria um deployment postgress com armazenamento permanente, seguindo os comandos abaixo:
```
kubectl apply -f persitentVolume.yml

kubectl apply -f persistentVolumeClaim.yml

kubectl apply -f deploymentPostgres.yml
```




