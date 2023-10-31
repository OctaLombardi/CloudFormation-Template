

## Despliegue de una aplicación web escalable en AWS

Objetivo: La aplicación web utilizará un archivo PHP para mostrar la dirección IP 
del servidor donde se encuentra alojada.

## Pasos:

En este proyecto, el primer paso consistirá en la configuración de una VPC en AWS, donde se definirá la subred y la tabla de ruteo correspondiente. Seguido de esto, se procederá a configurar un Load Balancer, el cual distribuirá el tráfico de la aplicación web entre las instancias EC2 que se crearán posteriormente. La configuración de Auto Scaling será esencial para permitir el escalado automático del número de instancias EC2 en función de la carga de la aplicación web. Además, se creará un bucket de S3 en AWS para almacenar un archivo PHP que mostrará la dirección IP del servidor. Se configurará un sistema de archivos de EFS en AWS para permitir compartir archivos entre las instancias EC2. Luego, se automatizará la creación y configuración de los recursos mediante un stack de CloudFormation en AWS. Se crearán instancias EC2 utilizando la imagen de Amazon Linux 2 y se unirán al Load Balancer. La aplicación web se ajustará para mostrar la dirección IP del servidor, utilizando el archivo PHP almacenado en el bucket de S3 creado previamente. Finalmente, se realizarán pruebas de carga para verificar el funcionamiento correcto del Auto Scaling.

