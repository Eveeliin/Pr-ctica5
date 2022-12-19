# Práctica 5

_He conseguido desplegar Mediawiki, Guestboook, Adminer, Wordpress, pero no conseguí abrir apache._

## Mediawiki 📖🚀

_Uno de los requisitos es hacer la parte del fichero **LocalSettings.php**._

### Instalación 🔧

* _Copie el yml de la página ofical de [Docker Hub](https://hub.docker.com/_/mediawiki) y lo guarde en el fichero docker-compose.yml_

* _Lo instalé en el terminal con el comando:_

```
docker-compose up -d
```

* _Abrí el contenedor en el que se pedían los siguientes datos:_
```
IP: 172.22.0.2 (Que se encuentra al inspeccionar el contenendor)

Nombre de usuario: wikiuser

Contraseña: example

Estos dos últimos datos están en el fichero yml.
```

## Guestbook 🐤

_Se puede utilizar cualquiera de las versiones._

### Instalación 🔧

* _Al no encontrarlo en la página ofical, encontré en la el contenido de docker-compose.yml en [esta](https://iesgn.github.io/curso_docker_2021/sesion5/guestbook.html) página web._

* _Lo instalé en el terminal con el comando:_

```
docker-compose up -d
```

* _Desplegué la página haciendo click derecho en el contenedor y haciendo click en *Open in Browser*_

## Adminer 🐀

_💬 Utilizar la imagen oficial._

### Instalación 🔧

* _El contenido de docker-compose.yml en la web de [Docker Hub](https://hub.docker.com/_/mediawiki)._

* _Lo instalé en el terminal con el comando:_

```
docker-compose up -d
```

* _Comprobé que se pudiera abrir y si se ejecutó correctamente._

## Wordpress 📖✏️

_💬 Utilizar la imagen oficial._

### Instalación 🔧

* _Copie el yml de la página ofical de [Docker Hub](https://hub.docker.com/_/mediawiki) y lo guarde en el fichero docker-compose.yml_

* _Lo instalé en el terminal con el comando:_

```
docker-compose up -d
```

* _Abrí el contenedor haciendo click derecho en:_
```
Containers>wordpress>wordpress_wordpress_1
```

* Pulsar en "Open in browser".


---
Hecho por [Evelin Reyes](https://github.com/Eveeliin) ☺️