# Zip Zap Gateway
This repository contains the global configuration for our Kubernetes Engine infrastructure

## Production (zip-zap-gateway)
    Ingress: public-ingress
    Public IP: 35.190.4.154
    Cluster: central-cluster
    Zone: us-central1-b

### Application endpoints
See gce-static-ip-ingress.yaml for specific backend routes.

Web frontend

    *.corp.indiraactive.com

API backends

    *.api.indiraactive.com


## Staging (zip-zap-gateway-staging)
TODO: nathang