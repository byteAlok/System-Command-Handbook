# Kubernetes Commands Cheat Sheet

## Cluster Info
- `kubectl cluster-info`: Display cluster info
- `kubectl get nodes`: List all nodes

## Pod Management
- `kubectl get pods`: List pods in the current namespace
- `kubectl get pods -A`: List pods in all namespaces
- `kubectl describe pod <pod_name>`: Show detailed info about a pod
- `kubectl delete pod <pod_name>`: Delete a pod

## Deployments
- `kubectl get deployments`: List deployments
- `kubectl scale deployment <name> --replicas=3`: Scale a deployment
- `kubectl rollout status deployment/<name>`: Check rollout status

## Troubleshooting
- `kubectl logs <pod_name>`: Print logs of a pod
- `kubectl exec -it <pod_name> -- sh`: Start a shell in a pod
- `kubectl top pod`: Show resource usage of pods
