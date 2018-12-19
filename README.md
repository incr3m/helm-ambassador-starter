helm repo add datawire https://www.getambassador.io/helm

helm install --name ambassador-test datawire/ambassador

helm upgrade -i --namespace default hello-world-web hello-world-web
