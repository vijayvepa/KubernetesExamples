### Create NGINX Pod

k run my-nginx --image=nginx:alpine

### Get all Pods

- k get all
- k get pods

### Port Forward

k port-forward my-nginx-65959bc4b9-4pcvt 8080:80

- where the above is a pod name

### Delete Pod 

- Will bring up another pod

 k delete pod/my-nginx-65959bc4b9-6lzxx

 ### Delete Deployment

