Demo-Helm-Chart

 helm repo add demo https://watri.github.io/demo-chart/
 helm repo update
 helm install demo-service demo/demo -n prod --dry-run
 