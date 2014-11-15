Linux-On-Virtex-II-Pro
======================

#####Porting Linux Kernel on Legacy Virtex II Pro Board

*******************************************************

Español: Este proyecto tiene intenciones meramente academicas; tiene como objetivo mostrar el flujo de trabajo para portar el Kernel Linux a un board FPGA Virtex II Pro. El directorio de archivos se estructura de la siguiente forma: 

* hardware
  * system.mhs
  * system.mss
  * system.xps
* linux
  * makefile
  * config
  * arch
    * powerpc
      * boot
      * config
      * platforms
* software
  * rootfs
  * my_apps
  * powerpc-405-linux-gnu
* ace 

Al final hay una foto del board con el que planeo trabajar, voy a dejar esta documentacion aqui porque puede ser de utilidad para alguien mas =).
1) Primero, hay que tener las herramientas instaladas para crear el hardware 
* ISE_DVD_J_30.5.0- ISE solo funciona SO 32 bit
* EDK            -- XPS y SDK solo funciona SO 32 bit
* lib_rev_1_1    --BSB de la tarjeta 



Board: 
  
  
![icon](http://rawski.zpt.tele.pw.edu.pl/pl/files/XUPV2P.gif)
