![logo speedy](https://jungle-team.com/wp-content/uploads/2023/04/picon_logo.png)

[![Licencia speedy](https://jungle-team.com/wp-content/uploads/2023/03/licence.png)
](https://github.com/jungla-team/Speedy-OEA-autoinstall/blob/main/LICENSE) [![chat telegram](https://jungle-team.com/wp-content/uploads/2023/03/telegram.png)
](https://t.me/joinchat/R_MzlCWf4Kahgb5G) [![donar a jungle](https://jungle-team.com/wp-content/uploads/2023/03/donate.png)
](https://paypal.me/jungleteam)


`Picon enigma2 Moistar` son logos de canales en png correspondientes a la Plataforma Movistar+, que se muestran en la interfaz grafica de receptores enigma2, aunque tambien pueden ser usados en otros dispositivos compatibles.

Si deseas obtener ayudas asi como prestarlas sobre este desarrollo, asi como con enigma2 en general, tenemos  [grupo de Telegram](https://telegram.me/pythontelegrambotgroup) . ¡Únete a nosotros!

Si deseas estar a la ultima sobre novedades desarrolladas por jungle team [canal de Telegram noticias](https://telegram.me/pythontelegrambotchannel) .

## Caracteristicas de los picones

Los picones de los canales que se realizan para la plataforma Movistar+, en cada [**actualizacion de las mismas**](https://github.com/jungla-team/Picon-enigma2-Movistar/releases/tag/jungle-picon) se realizan estos logos normalmente desde 0 buscando los sources de font y luego imitando la mosca TV original de cada canal en emision, los picones los realizamos con las siguientes caracteristicas:

*   Formato .png
*   Tamaño 440 x 264
*   nombre de los picones basados en service reference de los canales 

Realizamos 4 de formatos de picon, para que cada usuario pueda elegir que tipo de picon le gusta mas o se ajusta mas a sus necesidades:

| **TIPO** | ultima actualizacion | descripcion |
| --- | --- | --- |
| Transparente | 16-03-2025 | fondo trasparente, logo tipo mosca tv original en emision  |
| Color | 16-03-2025 | Fondo transparente, logo a color  |
| Lunar | 16-03-2025| Fondo Negro/gris degradado, logo con reflejo |
| 3D | 16-03-2025 | fondo transparente, logo tipo 3D  |

---

## Capturas visuales de tipo de Picon

Para que podais ver visualmente como es cada picon y de esta manera haceros mejor idea de como son los mismos os dejamos unas capturas de los mismos:


![1_0_1_75B0_422_1_C00000_0_0_0](https://user-images.githubusercontent.com/44529886/229458556-f59930c7-ec4f-4cb6-8d7c-d5aa6225180b.png)![1_0_1_75FA_408_1_C00000_0_0_0](https://user-images.githubusercontent.com/44529886/229459668-bf73d02f-97e1-4b33-895c-1e64a717c518.png)
![1_0_1_75F9_408_1_C00000_0_0_0](https://user-images.githubusercontent.com/44529886/229459836-049e2015-cd93-4b3a-9f9f-4f524f6a6819.png)
![1_0_1_76C0_40E_1_C00000_0_0_0](https://user-images.githubusercontent.com/44529886/229460025-b32febcc-fcec-4b5f-8272-eb3dad9a8bb2.png)
![1_0_1_746A_3F0_1_C00000_0_0_0](https://user-images.githubusercontent.com/44529886/229460244-c9552163-6310-4895-bf11-50e45c4774da.png)
![1_0_1_7478_3F0_1_C00000_0_0_0](https://user-images.githubusercontent.com/44529886/229460446-abbfdb53-7fd9-46c2-83ae-fbb0d6b50ac9.png)


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

*   [https://jungle-team.com/guia-junglebot-revolution-4-1-1/](https://jungle-team.com/guia-junglebot-revolution-4-1-1/)

### **5\. Desde Panel extra Openspa**

Desde panel Extra openspa tambien estan disponibles los picones para su descarga.


## Obteniendo ayuda

Si los recursos mencionados anteriormente no responden a sus preguntas o dudas,  o te ha resultado muy complicado, tienes varias formas de obtener ayuda.

1.  Tenemos una comunidad donde se intenta que se ayudan unos a otros en nuestro [grupo de Telegram](https://t.me/joinchat/R_MzlCWf4Kahgb5G) . ¡Únete a nosotros! Hacer una pregunta aquí suele ser la forma más rápida de obtener respuesta y poder hablar directamente con los desarrolladores.
2.  Tambien puedes leer con detenimiento los manuale disponibles en nuestro blog https://jungle-team.com/.

## contribuir

Los picones estan desarrollado sbajo codigo abierto, por lo que las contribuciones de todos los tamaños son bienvenidas para mejorar o ampliar las posibilidades del mismo. También puede ayudar [informando errores o solicitudes de funciones a traves del grupo telegram](https://t.me/joinchat/R_MzlCWf4Kahgb5G) .

## [](jungleteam#donating)donando

De vez en cuando nos preguntan si aceptamos donaciones para apoyar el desarrollo. Si bien, mantener `picones movistar`  es nuestro hobby y  pasatiempo, si tenemos un coste de mantenimiento de servidor de repositorios asi como [del blog enigma2](https://jungle-team.com/), por lo que si deseas colaborar en su mantenimiento sirvase de realizar [Donacion](https://paypal.me/jungleteam)

## [](jungle-team#license)Licencia

Puede copiar, distribuir y modificar el software siempre que las modificaciones se describan y se licencien de forma gratuita bajo [LGPL-3](https://www.gnu.org/licenses/lgpl-3.0.html) . Los trabajos derivados (incluidas las modificaciones o cualquier cosa vinculada estáticamente a la biblioteca) solo se pueden redistribuir bajo LGPL-3.
