## Picon Enigma2 Satelite

Picon enigma2 de canales de television de la plataforma Movistar+, que se emiten a traves del Satelite Astra 19.2º **para receptores enigma2** . Especialmente enfocado a España. Nos podeis encontrar:

*   **Grupo telegram de ayuda y soporte:** [https://t.me/joinchat/AFo2KEfzM5Tk7y3VgcqIOA](https://t.me/joinchat/AFo2KEfzM5Tk7y3VgcqIOA)
*   **Web oficial jungle-team:** https://jungle-team.com/

---

## Colabora con el projecto

La descarga de **los picones es gratuita**, no obstante si te gustan y deseas colaborar Para el mantenimiento de los servidores y Blog que gestiona jungle-team puedes realizar una donacion:

## Formato Picones

Los picones de los canales que se realizan para la plataforma Movistar+, en cada [**actualizacion de las mismas**](https://github.com/jungla-team/Picon-enigma2-Movistar/releases/tag/jungle-picon) se realizan estos logos normalmente desde 0 buscando los sources de font y luego imitando la mosca TV original de cada canal en emision, los picones los realizamos con las siguientes caracteristicas:

*   Formato .png
*   Tamaño 440 x 264
*   nombre de los picones basados en service reference de los canales 

Realizamos 4 de formatos de picon, para que cada usuario pueda elegir que tipo de picon le gusta mas o se ajusta mas a sus necesidades:

| **TIPO** | ultima actualizacion | descripcion |
| --- | --- | --- |
| Transparente | 31-01-2023 | fondo trasparente, logo tipo mosca tv original en emision  |
| Color | 31-01-2023 | Fondo transparente, logo a color  |
| Lunar | 31-01-2023 | Fondo Negro/gris degradado, logo con reflejo |
| 3D | 09-08-2022 | fondo transparente, logo tipo 3D  |

---

## Capturas visuales de tipo de Picon 

Para que podais ver visualmente como es cada picon y de esta manera haceros mejor idea de como son los mismos os dejamos unas capturas de los mismos: 

---

## **Como realizar la instalacion de los picones**

En la actualidad los picones enigma2 que realizamos en Jungle-Team la podemos instalar de diferentes metodos, por lo que podemos elegir que metodo se adapta mas a nuestras necesidades.

### **1\. Descarga directa al Pc y con programa**

Los picones los  podemos descargar en formato .zip en nuestro PC, para luego poder una vez descomprimida introducirla en nuestro receptor con un programa cliente FTP, para esta accion recomendamos [WINSCP](https://winscp.net/eng/download.php). Los pasos son muy sencillos:

1\. Nos descargamos los picones que deseamos desde [relases en github de nuestros picon](https://github.com/jungla-team/Picon-enigma2-Movistar/releases)

2\. Descomprimimos los picones .zip en nuestro pc

3\. Accedemos al receptor por ftp y debemos introducir los picones (los archivos .png), en una de las siguientes directorios de nuestro receptor enigma2:

*   /media/hdd/picon
*   /media/usb/picon
*   /usr/share/enigma2/picon
*   /picon 

### **2\. Usando el plugin JungleScript**

Junglescript es un plugin que nos permite realizar una autoinstalacion de los picones, y en cada reinicio del receptor en caso de haber actualizacion de picones estos se actualizan automaticamente, aparte junglescript nos permite muchas configuraciones extra, podeis ver el manual en este articulo:

*   [https://jungle-team.com/junglescript-guia-usuario-rev-2-0/](https://jungle-team.com/junglescript-guia-usuario-rev-2-0/)

### **3\. Añadiendo repositorios Jungle-Team**

Otro metodo de instalacion de los picones es a traves del menu plugins de la imagen que tenemos instalada, para ello es necesario previamente instalar los repositorios jungle-team, que lo podemos hacer facilmente a traves de terminal ejecutando el siguiente comando:

```diff
wget http://tropical.jungle-team.online/script/jungle-feed.conf -P /etc/opkg/
```

Una vez hemos añadido los repositorios jungle-team, ya podemos instalar facilmente la lista canales desde el menu + plugins + boton descargas en la categoria picons

### **4\. Desde jungleBot**

Junglebot es un bot telegram que nos permite controlar nuestro receptor desde telegram, una de las caracteristicas que tiene es que podemos instalar los picones desde el mismo (es necesario previamente tener instalado junglescript)

Si deseas mas informacion sobre junglebot, puedes ver el articulo manual:

*   [https://jungle-team.com/junglebot-2-5-0-controla-enigma2-con-telegram/](https://jungle-team.com/junglebot-2-5-0-controla-enigma2-con-telegram/)

---

## **Contacta con nosotros**

Si observas en los picones cualquier error, o tienes alguna mejora que te gustaria añadir a los picones o Como mejorar los mismos, puedes contactarnos al traves del grupo telegram de jungle-team:

*   https://t.me/joinchat/AFo2KEfzM5Tk7y3VgcqIOA
