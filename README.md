

## Despliegue de una aplicación web escalable en AWS

Objetivo: La aplicación web utilizará un archivo PHP para mostrar la dirección IP 
del servidor donde se encuentra alojada.

## Pasos:

1) Configuración de una VPC: Los participantes crearán una VPC en AWS, configurando la subred y la tabla de ruteo correspondiente.

2) Configuración de un Load Balancer: Los participantes crearán un Load Balancer en AWS, el cual distribuirá el tráfico de la aplicación web entre las instancias EC2 que se crearán posteriormente.

3) Configuración de Auto Scaling: Los participantes configurarán Auto Scaling en AWS, lo que les permitirá escalar automáticamente el número de instancias EC2 según la carga de la aplicación web.

4) Configuración de S3: Los participantes crearán un bucket de S3 en AWS, donde almacenarán el archivo PHP que mostrará la dirección IP del servidor.

5) Configuración de EFS: Los participantes crearán un sistema de archivos de EFS en AWS, que les permitirá compartir archivos entre las instancias EC2 que se creen posteriormente.

6) Creación de un stack de CloudFormation: Los participantes crearán un stack de CloudFormation en AWS, que les permitirá automatizar la creación y configuración de los recursos que han creado hasta ahora.

7) Creación de instancias EC2: Los participantes crearán instancias EC2 en AWS, las cuales utilizarán la imagen de Amazon Linux 2 y se unirán al Load Balancer creado anteriormente.

8) Configuración de la aplicación web: Los participantes configurarán la aplicación web para que muestre la dirección IP del servidor donde se encuentra alojada. Para ello, deberán utilizar el archivo PHP almacenado en el bucket de S3 que han creado previamente.

9) Pruebas de carga: Los participantes probarán la aplicación web con herramientas de pruebas de carga para verificar que el Auto Scaling está funcionando correctamente.


