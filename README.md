kubectl run -it fortio --rm --image=fortio/fortio -- load -qps 800 -t 120s -c 70 "http://goserver-service/healthz"

NGINX Ingress controller: https://kubernetes.github.io/ingress-nginx

cert-manager: https://cert-manager.io/docs/installation/kubernetes/

kubectl config view
kubectl config current-context

kubectl config current-context

# cria contexto dev
kubectl config set-context dev --namespace=dev --cluster=kind-fullcycle --user=kind-fullcycle

# cria contexto prod
kubectl config set-context prod --namespace=prod --cluster=kind-fullcycle --user=kind-fullcycle

kubectl config use-context dev
