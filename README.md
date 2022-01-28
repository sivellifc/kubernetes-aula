kubectl run -it fortio --rm --image=fortio/fortio -- load -qps 800 -t 120s -c 70 "http://goserver-service/healthz"

NGINX Ingress controller: https://kubernetes.github.io/ingress-nginx

cert-manager: https://cert-manager.io/docs/installation/kubernetes/