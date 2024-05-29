# custom resouce definition create


`kubectl apply -f crd-greeting.yaml`

`kubectl apply -f test-greeting.yaml`



**Steps to See API Server Groups**

`kubectl proxy`

open `curl localhost:8001`

[//]: # (open `curl localhost:8001 | grep -i gvramana` to check API group )


# see crd details

`kubectl api-resources`

`kubectl get crd greetings.gvramana.io -o yaml`
