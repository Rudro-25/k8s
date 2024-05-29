# Initial time (create new helm and edit deployment & service according to your book_api_server details)

`helm create bookapiserver`

`helm package bookapiserver/`

# For re-use this code by coping this folder

`helm install test ./bookapiserver/`

`kubectl port-forward svc/test-service 3201:3200`

`http://localhost:3201/`