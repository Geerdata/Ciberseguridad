# Ciberseguridad
Repositorio con contenidos de Ciberseguridad

Instalación de Entorno Virtual para PC
Descargar de la Pagina oficial VirtualBox, Ejecutable para Windows 
*  https://www.virtualbox.org/wiki/Downloads

Despues descargaremos de la pagina oficial KALI LINUX (El Sistema Operativo de Seguridad Informatica)
* https://www.kali.org/get-kali/#kali-virtual-machines

Aqui descargaremos la ISO de Virtual Box 

![image](https://github.com/Geerdata/Ciberseguridad/assets/12371674/79752469-8326-4544-acac-5b2a53f2e331)






Instalación de Entorno Virtual para MOBILE Sin Root
Video tutorial de Referencia   
* https://www.youtube.com/watch?v=sbVjKgIh_iY

Documentacion oficial de KALI LINUX - NETHUNTER
* https://www.kali.org/docs/nethunter/nethunter-rootless/


Primeramente se debera instalar en el movil una terminal para Ejecutar KALI
* En este link se encuentra el APK dependiendo de su dispositivo
* https://github.com/termux/termux-app/releases
* Por defecto puede ejecutar. /64-v8a.apk
![image](https://github.com/Geerdata/Ciberseguridad/assets/12371674/69cddeac-3f6e-43ca-af05-ccabde42d97b)

Cuando se descargue en su dispositivo, al ejecutar el apk, arrojara el mensaje para instalar
Despues de instalar, lo tendra como una aplicacion, si acceder entrara a un entorno de comandos

Aqui debera ejecutar el siguiente comando para validar si hay actualizaciones pendientes

    pkg update -y 	


Ahora debera brindar permisos de almacenamiento, esto lo hara con el siguiente comando 

    kali@kali:~$ termux-setup-storage

Ahora instalaremos el comando para acceder a la web

    kali@kali:~$ pkg install wget		
tttt
Ahora instalaremos 

kali@kali:~$ wget -O install-nethunter-termux  https://offs.ec/2MceZWr
kali@kali:~$ chmod +x install-nethunter-termux
kali@kali:~$ ./install-nethunter-termux

    3 - KALI 
Elegir la opción 1 FULL KALI
Despues pedira si queremos borrar el archivo decimos que NO

    4 - NETHUNTER

nh - r Abrir consola de kali linux root
nano /etc/resolv.conf 
cambiar el nombre server por 8.8.8.8
Por Último corremos este comando para aplicar la actualizaciones

apt update

    5 - Corregir futuros errores


Actualización de librerías
     apt install dbus-x11 -y

Para probar las funciones de KALI 
Primero tenemos que salir del root con el comando
	exit

entramos al entorno con comando
    nh	

https://github.com/termux/termux-app/releases

nos aparecera asi
    kali@localhost

Ahora debemos crear una contraseña DBUS para kali nh

 kex passwd  : kalikali

para activar el servicio de conexión

se debe poner nh kex

se activará el nethunter kex server con el puerto 5901


Ahora debemos instalar la interfaz
para vincular las rutas de red

debemos descargar la app store de https:://store.nethunter.com

Instalar la app Tienda  F-DROP 
buscar  nethunter kex VNC
en instalar la app


