# 07 — Calendario y Citas

### Calendario (día/semana/mes).

Para poder organizarnos Odoo nos proporciona un calendario como otro cualquiera donde lo puedes ver por dias, semana, meses o años

<img src="../assets/img/07-calendario_y_citas/calendario-calendario.png" alt="crearBD" width="1000">

### Integración con Google Calendar** (API OAuth GCP).

Primero tendremos que ir a Google console cloud e instalar la API de Google Calendar (Los mismos pasos para instalar una API que en el apartado de gmail).

La única diferencia es que la URL de direccionamiento será diferente, en este caso será la siguiente:

https://nombre.odoo.com/google_account/authentication

<img src="../assets/img/07-calendario_y_citas/calendario-Crendeciales.png" alt="crearBD" width="1000">

Una vez terminado tendremos que ir a credenciales y copiar el ID de cliente en Ajustes->Calendario y lo mismo con el Secreto de cliente.

Para añadir algun evento simplemente le pincahamos a cualquier parte del calendario y se nos abrirá la siguiente pantalla, le damos a mas opciones para verlo al completo

<img src="../assets/img/07-calendario_y_citas/calendario-Evento.png" alt="crearBD" width="400">

<img src="../assets/img/07-calendario_y_citas/calendario-EventoOpciones.png" alt="crearBD" width="800">

Desde aqui podemos seleccionar la duracion, la ubicación o incluso poner un enlace a alguna videollamada, ya sea desde google meet o cualquier otra web de videollamadas.
