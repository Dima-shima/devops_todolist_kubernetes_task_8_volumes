kubectl config set-context --current --namespace=todoapp

kubectl get pods

kubectl get svc

open in brouser
http://localhost:30007

kubectl exec <pod-name> -it -- sh
ls
cd configs
ls
cat PYTHONUNBUFFERED
cd ..
cd secrets
ls
cat SECRET_KEY