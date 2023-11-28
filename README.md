# Grafana
grafana deployment yaml files
# deploy the grafana config-map file 
 kubectl create -f grafana-config.yml
# deploy the grafana deployment yaml file
 kubectl create -f grafana-deployment.yml
# deploy the grafana service yaml
  kubectl create -f grafana-service.yml

  # Now try to access the grafana url
   http://<hostip>:port
   ex: http://10.234.22.3:3000
   
