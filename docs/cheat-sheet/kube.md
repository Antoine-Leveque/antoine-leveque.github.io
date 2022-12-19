---
sidebar_position: 1
---

# Kube commands
_source: https://twitter.com/it_craftsman/status/1601577532922404867_

## Cluster Management 

```bash
# Permet de voir l'adresse du control plane 
kubectl cluster-info

# Voir la version du cluster et du client 
kubectl version

# Afficher la configuration du client relative au serveur 
kubectl config view 

# Afficher la liste des rssources API disponibles 
kubectl api-resources 

# Afficher ka kuste des version API disponibles 
kubectl api-versions

# Tout lister 
kubectl get all -all-namespaces
```
