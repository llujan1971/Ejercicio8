# Ejercicio8
Detalle ejercicio 8 curso de Kubernetes

// Crear el configmap

kubectl -n arba apply -f configmap-env.yaml

// Aplicar el deploy

kubectl -n arba apply -f deployment.yaml
