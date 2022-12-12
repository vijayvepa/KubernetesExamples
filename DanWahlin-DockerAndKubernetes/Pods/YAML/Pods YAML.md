### Dry Run

k create -f nginx.pod.yaml --dry-run --validate=true

### Create

k create -f nginx.pod.yaml  --save-config

### Save
k apply -f 


### Audit

k describe pod my-nginx

### Port Forward

k port-forward my-nginx 9090:80

### SSH into

k exec my-nginx -it sh

