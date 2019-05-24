# Installer


### Install requeriments

#### Windows 
1. Descargar Git e instalar [link -> https://git-scm.com]
2. Descargar Docker Toolbox [link -> https://docs.docker.com/v17.12/toolbox/toolbox_install_windows/]
3. Creamos una carpeta donde estara el HRSystem



#### Install HRSystem
Buscamos el git-bash e iniciamos una sesión
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

``name-container => nombre del container donde esta el proyecto de django`
