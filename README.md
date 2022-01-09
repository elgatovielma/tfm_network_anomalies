# Instrucciones


## Prerequisito:

Crearse una cuenta en GitHub y luego descargar [git](https://git-scm.com/downloads) para poder manejar los comandos en el CLI.

Tambien hay que crear un ssh key siguendo [estas instrucciones](https://git-scm.com/book/en/v2/Git-on-the-Server-Generating-Your-SSH-Public-Key) y agregarla en [SSH and GPG keys](https://github.com/settings/keys)


## Descargar repo:

```
git clone https://github.com/elgatovielma/tfm_network_anomalies.git
```

Al descargar el codigo, se tendrá una nueva carpeta en la cual estará el proyecto y luego se debe entrar en la carpeta.

## Comandos Básicos:


Antes de hacer cualquier nuevo cambio se comprueba si alguien más subio algo al repo para sí bajar esos cambios:
```
git pull
```

Para ver cambios hechos:
```
git diff
```

Para subir nuevos cambios se usa:
```
git add .
git commit -m "Mensaje que describa el cambio hecho"
git push
```
