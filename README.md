# kubernetes-postgresql
## Déployer Postgresql sur Kubernetes avec Haute Disponibilité


kubectl create namespace database

kubectl apply -f pv-localstorage.yaml -n database

kubectl apply -f ./postgresql -n database

kubectl apply -f ./pgpool -n database

kubectl apply -f ./client -n database





