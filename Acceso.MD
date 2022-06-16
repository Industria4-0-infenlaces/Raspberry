# Acceso remoto a la Rapsberry
En una Raspberrry una vez que ya hemos instalado en Sistema Operativo Raspbian:
* Preferencias - Configuración de Raspberry pi
* Seleccionamos las interfaces: habilitar SSH y VNC

Con esto podemos acceder remotamente a Raspberry sin necesidad de contar un monitor dedicado.

Sabiendo la dirección IP de la máquina:
![ip](https://github.com/Industria4-0-infenlaces/Raspberry/blob/main/ip%20a%20raspberry.JPG)

Para acceder por VNC podemos usar [VNC viewer](https://www.realvnc.com/es/connect/download/viewer/)

![VNC viewer Windows](https://github.com/Industria4-0-infenlaces/Raspberry/blob/main/acceso%20vnc.JPG)

Nos pedirá un usuario y contraseña. Nuestro usuario es industria4.

Para el acceso SSH, sencillamente usaremos el comando **ssh industria4@10.6.66.48**:
![ssh](https://github.com/Industria4-0-infenlaces/Raspberry/blob/main/ssh_acceso.JPG)
