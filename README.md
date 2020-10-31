# PRÁCTICA 2 - AWS EDUCATE
![](Imágenes/aws.png)
## Instalación de máquinas en Amazon Web Services
Lo primero que debemos hacer es lanzar una nueva instancia y dentro de ella veremos una lista de AMI (Amazon Machine Image) que son máqinas ya preparadas para que se usen. Elegimos (por ejemplo) Ubuntu Server 20.04.

A continuación elegiremos el tipo de instancia. Nos dan una por defecto, la **t2.micro** aunque hay más:

- t2nano
- t2small
- t2 medium
- t2large

Después configurarémos los detalles de la instancia y también los volumenes de almacenamiento (se deja por defecto).

Y para terminar añadir los puertos que necesitamos:
- El puerto HTTP - 80
- El puerto HTTPS - 443
  
OJO (El puerto SSH siempre viene por defecto)

Una vez hayamos terminado de configurar nuestra máquina tendremos que crear (si no está creada) una key pública y privada con la que poder conectarnos por SSH (medidas de seguridad de Amazon)

![](Imágenes/key.png)

Ejecutamos script para crear la pila LAMP en nuestro Ubuntu.