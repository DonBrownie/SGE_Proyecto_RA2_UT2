# 06 — Instalación de Odoo

Para la instalación de Odoo simplemente tendremos que ejecutar los siguientes comandos:

``-wget -q -O - https://nightly.odoo.com/odoo.key | sudo gpg --dearmor -o /usr/share/keyrings/odoo-archive-keyring.gpg ``

``-echo 'deb [signed-by=/usr/share/keyrings/odoo-archive-keyring.gpg] https://nightly.odoo.com/17.0/nightly/deb/ ./' | sudo tee /etc/apt/sources.list.d/odoo.list ``

``-sudo apt-get update && sudo apt-get install odoo``

![Servicio PostgreSQL](../assets/img/06-instalacion-Odoo/instalacion-Odoo.png "Estado del servicio")
