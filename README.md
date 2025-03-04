# ReadMe
https://apisix.apache.org/blog/2021/12/15/deploy-apisix-in-kubernetes/#option-2-deployment-via-yaml-file


kubectl apply -f etcd.yaml
kubectl apply -f apisix.yaml
kubectl apply -f apisix-dashboard.yaml

kubectl port-forward service/apisix-dashboard 8080:80
Finally, visit localhost:8080 to see the Dashboard related information. The default login password is admin,admin.

kubectl port-forward service/apisix-admin 9180:9180
