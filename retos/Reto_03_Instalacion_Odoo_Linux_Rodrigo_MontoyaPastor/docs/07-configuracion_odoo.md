# 07 — Configuración de Odoo (`/etc/odoo/odoo.conf`)

1. Crea/edita el archivo de configuración con:
   
   Primero deberemos de configurar el archivo de configuración de Odoo con el siguiente comando

   ``nano /etc/odoo/odoo.conf``

   Una vez dentro de este archivo se deberían de modificar los siguientes datos:

   ```ini
   [options]
   db_host = False
   db_port = False
   db_user = odoo
   db_password = False
   addons_path = /opt/odoo/odoo-src/addons
   logfile = /var/log/odoo/odoo.log
   xmlrpc_port = 8069
   ```
3. Crea carpetas y permisos si procede:

   Si queremos revisar los cambios (desde errores, avisos, arranques, ...) que vayan pasando dentro de Odoo, habrá que utilizar el siguiente comando:

   ```bash
   sudo mkdir -p /var/log/odoo && sudo chown odoo:odoo /var/log/odoo
   ```

   Esta carpeta es muy importante ya que nos ayudará a depurar errores.
