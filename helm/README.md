`helm create bookapiserver`

`helm package bookapiserver/`

`helm install test ./bookapiserver/`

`kubectl port-forward svc/test-service 3201:32001`

`http://localhost:3201/`