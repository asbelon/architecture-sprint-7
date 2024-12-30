# Роли и полномочия

Определены роли для администрирования kubernetes см [таблица](Роли%20и%20полномочия.xlsx)

# Настройка kubernetes

```bash
minikube start --vm-driver=hyperv
```

```bash
minikube dashboard
```

```bash
kubectl get nodes
```

```bash
kubectl get all --all-namespaces
```

```bash
kubectl apply -f ./dev-ops_engineer/role.yaml
```

```bash
kubectl apply -f ./dev-ops_engineer/rolebinding.yaml
```

```bash
kubectl apply -f ./service_engineer/role.yaml
```

```bash
kubectl apply -f ./service_engineer/rolebinding.yaml
```
