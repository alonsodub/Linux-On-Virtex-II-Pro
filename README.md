Linux-On-Virtex-II-Pro
======================

#####Porting Linux Kernel on Legacy Virtex II Pro Board

*******************************************************

Español: Este proyecto tiene intenciones meramente academicas; tiene como objetivo mostrar el flujo de trabajo para portar el Kernel Linux a un board FPGA Virtex II Pro. El directorio de archivos se estructura de la siguiente forma: 

* Hardware
  * PowerPC
   * system.mhs
   * system.mss
   * system.xps
* Linux
  * makefile
  * config
  * arch
    * powerpc
      * boot
      * config
      * platforms
* Software
  * rootfs
  * my_apps
  * powerpc-405-linux-gnu
* Xilinx91
  * ISE_DVD
  * EDK9.1
  * lib_rev_1_1
* ace 

Al final esta una imagen de la tarjeta, voy a dejar esta documentacion aqui porque puede ser de utilidad para alguien mas =)

1. Primero, hay que tener las herramientas instaladas para crear el hardware, estan en la carpeta Xilinx91
 * ISE_DVD_J_30.5.0- ISE solo funciona SO 32 bit
 * EDK9.1         -- XPS y SDK solo funciona SO 32 bit
 * lib_rev_1_1    -- BSB de la tarjeta

2. Esta es la forma como he ido abordando la implementacion 

![icon](https://alonsodub.files.wordpress.com/2014/11/disec3b1o-sistema.jpg?w=210&h=300)





Board: 
  
  
![icon](http://rawski.zpt.tele.pw.edu.pl/pl/files/XUPV2P.gif)
