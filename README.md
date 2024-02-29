Structure:

```
GHOST
		ING.yaml https:///ghost.boeing.internal.cloudgenius.app
		SVC.yaml 80
		Deploy.yaml a pod on port 2368
		pvpvc.yaml
		ghostfiles in NFS server

MySQL
		mysql svc 3306
		mysql deploy mysql:8.3.0
		pvpvc.yaml -
		mysqldata in NFS server
```
