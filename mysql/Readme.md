  For minikube delete storage
  kubectl get storageclass
  kubectl delete storageclass <storage_class_name>
  and create mysql storage and apply
  FOR ISSUE IN MINIKUBE:-

  Try these incase of any issue:
minikube stop
minikube delete
docker system prune --all
sudo sync && echo 3 | sudo tee /proc/sys/vm/drop_caches
docker volume ls
(if exist any delete)
minikube start
