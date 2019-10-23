# ingress-nginx-document

# With Case use aws clb as a LB for ingress controller:
1. in nginx-configmap : use-proxy-protocol: "true"
2. AWS CLB healcheck: must be via: TCP
