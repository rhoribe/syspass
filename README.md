# Syspass

## Syspass for K8S

 
 **Deploy**
 

    kubect apply -f syspass-namespace.yml
    kubect apply -f syspass-volumes.yml
    kubect apply -f syspass-secrets.yml
    kubect apply -f syspass-db-statefulset.yml 
    kubect apply -f syspass-app-statefulset.yml
    kubect apply -f syspass-app-hpa.yml 
    kubect apply -f syspass-ingress.yml

Obs: Default  user root password mysql is 'syspass'
 
