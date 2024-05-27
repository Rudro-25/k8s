`helm create bookapiserver`

`helm package bookapiserver/`

`helm install test ./bookapiserver/`

`kubectl port-forward svc/test-service 3201:3200`

`http://localhost:3201/`