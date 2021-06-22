# helm-charts

helm search hub prometheus
helm search repo prometheus
helm install
helm status
helm show values
helm get values
helm rollback
helm list
helm repo list

---------

helm create inginx-helm
helm lint
helm package inginx-helm
helm install inginx-helm ./inginx-helm-0.1.0.tgz -n kube-slack
helm uninstall inginx-helm

helm repo index --url https://srinadh-lanistar.github.io/helm-chart/ .
helm dep up 

helm repo add inginx-chart https://srinadh-lanistar.github.io/helm-charts/
helm repo remove inginx-chart