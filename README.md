#### Configuration docker hrsystem

```
$ cd /carpeta-donde-esta-hrsystem
$ git clone https://github.com/evervasquez/hrsystem_installer.git hrsystem
$ cd hrsystem
$ docker-compose up
```


#### List container
```
$ docker ps
```

#### Migrations Django
```
$ docker exec -i -t [name-container] /bin/bash
```
name-container => nombre del container donde esta el proyecto de django
