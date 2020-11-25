# Syspass

## Syspass for K8S

 
 **Deploy**
 

    kubectl apply -f syspass-namespace.yml
    kubectl apply -f syspass-volumes.yml
    kubectl apply -f syspass-secrets.yml
    kubectl apply -f syspass-db-statefulset.yml 
    kubectl apply -f syspass-app-statefulset.yml
    kubectl apply -f syspass-app-hpa.yml 
    kubectl apply -f syspass-ingress.yml

Obs: Default  user root password mysql is 'syspass'
 
