# Arquivos para executar aplicação com o kubernates

```sh
Antes de executar o app-tech-challenge-hpa,yaml é necessário exectuar o metrics.yaml
```

## Mysql

-  kubectl apply -f .\metrics.yaml
-  kubectl apply -f .\secrets.yaml
Entrar no diretório mysql
-  kubectl apply -f .\mysql-configmap.yaml
-  kubectl apply -f .\mysql-pv.yaml
-  kubectl apply -f .\mysql-deployment.yaml
  
## Java
Entrar no diretório java
-  kubectl apply -f .\app-tech-challenge.yaml
-  kubectl apply -f .\app-tech-challenge-hpa.yaml

## Acessar Aplicação
http://http://localhost:8080/