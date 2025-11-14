# 05 — Dependencias (Python, wkhtmltopdf, librerías)

1. Instala Python y paquetes de compilación:

   ``sudo apt -y install python3 python3-pip python3-venv build-essential libxslt1-dev      libzip-dev libldap2-dev libsasl2-dev libjpeg-dev libpq-dev``

   Normalmente en linux viene preinstalado python pero en caso de que no habría que poner dos comandos en la terminal.

   ``sudo apt install python3``

   ``sudo apt install python3-pip``
2. Instala **wkhtmltopdf** compatible (para reportes PDF).

   ``sudo apt install wkhtmltopdf``
3. Verifica versiones:

   ``python3 --version wkhtmltopdf --version``

   ![Servicio PostgreSQL](../assets/img/05-dependencias/dependencias-version.png "Estado del servicio")

   Una vez instalado toca revisar las versiones para ver si se ha llegado a instalar correctamenteç

> Resultado esperado: dependencias instaladas y comprobadas.
