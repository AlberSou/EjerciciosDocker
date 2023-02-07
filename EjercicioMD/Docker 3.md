# Docker 3

## 1. Crea un volumen docker que se llame miweb.
![](../Capturas/docker31.png)

## 2. Crea un contenedor desde la imagen php:7.4-apache donde montes en el directorio/var/www/html (que sabemos que es el DocumentRoot del servidor que nos ofrece esaimagen) el volumen docker que has creado.

![](../Capturas/docker32.png)

## 3. Utiliza el comando docker cp para copiar un fichero index.html en el directorio/var/www/html.

![](../Capturas/docker33.png)
## 4. Accede al contenedor desde el navegador para ver la información ofrecida por el fichero index.html.

![](../Capturas/docker34.png)

## 5. Borra el contenedor
![](../Capturas/docker35.png)

## 6. Crea un nuevo contenedor y monta el mismo volumen como en el ejercicio anterior.


![](../Capturas/docker36.png)
## 7. Accede al contenedor desde el navegador para ver la información ofrecida por el fichero index.html. ¿Seguía existiendo ese fichero?

![](../Capturas/docker37.png)
- Existe