# DOCKER

## 1
---
## 2 Ejecuta un contenedor a partir de la imagen hello-word. Comprueba que nos devuelve la salida adecuada. Comprueba que no se está ejecutando. Lista los contenedores que estánparado. Borra el contenedor.
![](file:///C:/Users/kalif/Desktop/Clase/Despliegue/Ejercicios/Capturas/fwgwgwe.png)
- Comprobamos si está corriendo
![](file:///C:/Users/kalif/Desktop/Clase/Despliegue/Ejercicios/Capturas/wwrgw.png)
- vemos que no 
![](file:///C:/Users/kalif/Desktop/Clase/Despliegue/Ejercicios/Capturas/wrgwrgwgw.png)
- Lo borro por su id

## 3  Crea un contenedor interactivo desde una imagen debian. Instala un paquete (por ejemplo nano). Sal de la terminal, ¿sigue el contenedor corriendo? ¿Por qué?. Vuelve a iniciar elcontenedor y accede de nuevo a él de forma interactiva. ¿Sigue instalado el nano?. Sal delcontenedor, y bórralo. Crea un nuevo contenedor interactivo desde la misma imagen. ¿Tieneel nano instalado?

- Lo corremos y dejamos que instale la imagen
![](file:///C:/Users/kalif/Desktop/Clase/Despliegue/Ejercicios/Capturas/whfiuwgiuwriufç.png)
- Actualizamos repositorios
![](file:///C:/Users/kalif/Desktop/Clase/Despliegue/Ejercicios/Capturas/owhoefohworghowrhgohrwg.png)
- Instalamos el nano
![](file:///C:/Users/kalif/Desktop/Clase/Despliegue/Ejercicios/Capturas/wgwgg3hh.png)
- No sigue corriendo, porque es interactivo y se cierra
![](file:///C:/Users/kalif/Desktop/Clase/Despliegue/Ejercicios/Capturas/wpjgwoegorwhgorwg.png)
- Accedemos de forma interactiva
![](file:///C:/Users/kalif/Desktop/Clase/Despliegue/Ejercicios/Capturas/efwefwegewgw.png)
- vemos que el nano sigue instalado
![](file:///C:/Users/kalif/Desktop/Clase/Despliegue/Ejercicios/Capturas/wgwgrwgrwgrwg.png)
- Borramos el contenedor 
![](file:///C:/Users/kalif/Desktop/Clase/Despliegue/Ejercicios/Capturas/foehwog.png)
- Creamos uno nuevo a partir de debian
![](file:///C:/Users/kalif/Desktop/Clase/Despliegue/Ejercicios/Capturas/oeqwhfiuewugw.png)
- Vemos que nano no esta instalado ![](file:///C:/Users/kalif/Desktop/Clase/Despliegue/Ejercicios/Capturas/sbirwhgiurwiugrv.png)
## 4 Crea un contenedor demonio con un servidor nginx, usando la imagen oficial de nginx. Al crear el contenedor, ¿has tenido que indicar algún comando para que lo ejecute? Accede al navegador web y comprueba que el servidor esta funcionando. Muestra los logs delcontenedor.
- Instalamos la imagen de nginx
![](file:///C:/Users/kalif/Desktop/Clase/Despliegue/Ejercicios/Capturas/wrgwrgwgr.png)
- Creamos el demonio 
![](file:///C:/Users/kalif/Desktop/Clase/Despliegue/Ejercicios/Capturas/fewfwewe.png)
- debemos ejecutarlo con este comando
![](file:///C:/Users/kalif/Desktop/Clase/Despliegue/Ejercicios/Capturas/wegwgwg.png)
- vemos los logs 
![](file:///C:/Users/kalif/Desktop/Clase/Despliegue/Ejercicios/Capturas/wegowgwoghowrhgw.png)
## 5 Crea un contenedor con la aplicación Nextcloud, mirando la documentación en docker Hub,para personalizar el nombre de la base de datos sqlite que va a utilizar.
- Creamos el contenedor 
![](file:///C:/Users/kalif/Desktop/Clase/Despliegue/Ejercicios/Capturas/wrwrgwrg.png)
- le cambiamos el nombre 
![](file:///C:/Users/kalif/Desktop/Clase/Despliegue/Ejercicios/Capturas/wofuwfiwfigwefiegwf.png)
