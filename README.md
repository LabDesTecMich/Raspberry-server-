# Raspberry-server-
Este respositorio cuenta con los pasos a seguir y comandos para instalar, crear y modificar los programas necesarios para montar un proyecto IoT con envio de datos a través de MQTT, utilizando Node-Red y MYSQL.

##Matreiales necesarios:

1. Raspberry Pi 4 modelo B 8Gb.

2. Micro-Sd 32Gb.

3. convertidor Usb a MicroSd.

5. Cable mini-HDMI a HDMI.

6. Pantalla o Monitor.

7. Teclado y Mouse.

8. fuente de alimentación de Raspberry Pi 4.

## Instalación del Sistema operativo y programas necesarios:

Empezaremos descargando la herramienta [Raspberry pi imager](https://www.raspberrypi.com/software/) en nuestro sistema

![](imagenes/RaspberrypiImager.JPG)

Posteriormente insertaremos la Micro-Sd en el adaptador Usb y la conectaremos a la computadora, continuaremos ejecutando el programa Raspberry pi imager, en el cual seleccionaremos el dispositivo que ocuparemos(para este caso sera la raspberry pi 4), el sistema operativo que le instalaremos (Raspberry pi OS (64bit)y la undad de almacenamiento en donde haremos la instalación(la undad que aparece la MicroSd que insertamos previamente). daremos al boton de next y nos mostrara una pantalla en la cual podremos configurar algunos aspectos como lo son el usuario, contraseña, red wifi, asi como habilitar opciones como ssh.

Al finalizar la instalación expulsaremos la Micro-Sd de nuestro pc y la retitaramos del adaptador para colocarla en la ranura de nuestra RaspBerry Pi 4, conectaremos el teclado y mouse a los puertos usb de la raspberry, asi como el cable de hdmi a la pantalla, conectaremos el cblae de la fuente de alimentación y la encenderemos.

```
sudo apt upgrade

sudo apt update

```



