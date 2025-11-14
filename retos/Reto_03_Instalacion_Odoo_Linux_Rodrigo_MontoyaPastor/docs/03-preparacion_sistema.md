# 03 — Preparación del sistema

1. Actualiza índices y paquetes:

   `` sudo apt update && sudo apt upgrade -y``

   Update se encargara de actualizar la lista de paquetes disponibles mientras que upgrade los descarga e instala a la versión más reciente

3. Configura zona horaria e idioma si procede.

   En caso de que en la instalacion del sistema no hayamos puesto madrid para la zona horaria tendremos que usar el siguiente comando

   ``sudo timedatectl set-timezone Europe/Madrid``
