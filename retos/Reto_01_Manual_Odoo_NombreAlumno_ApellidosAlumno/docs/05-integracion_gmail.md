# 05 — Integración con Gmail (OAuth GCP + Add-on)

> Estructura orientativa

## Requisitos

- Cuenta Google Cloud (GCP).

## Pasos resumidos

### Activar plugin de correo

<img src="../assets/img/05-integracion_gmail/ajustesGenereales-pCorreo.png" alt="datos" width="600">

Vamos a ajustes bajamos a integracions y activamos el plugin del correo.

Una vez hecho esto tendremos que ir a email e instalar Odoo Inbox *Add-on* en Gmail.

<img src="../assets/img/05-integracion_gmail/integracion-mailOdoo.png" alt="datos" width="600">

Para esto le damos al "+" que hay en la barra lateral y buscamos el plugin y lo instalamos

<img src="../assets/img/05-integracion_gmail/integracion-loginOdoo.png" alt="datos" width="300">

Una vez instalado nos pedira iniciar sesion poniendo la url de la base de datos.

Una vez hecho esto con el plugin del correo activado en Odoo y el plugin de mail instalado, podemos ver la información de la compañía.

<img src="../assets/img/05-integracion_gmail/integracion-ejemplo.png" alt="datos" width="300">

Aqui podemos ver la descripcion, ingresos anuales, el sitio web y más.

### 2

Vamos a ajustes bajamos hasta integraciones y activamos la *Autenticación OAuth*

<img src="../assets/img/05-integracion_gmail/integracion-OAuth.png" alt="datos" width="600">


Una vez habilitado tenemos que ir a google cloud para crear un nuevo proyecto

URL: https://console.cloud.google.com/welcome/new?pli=1

<img src="../assets/img/05-integracion_gmail/integracion-proyecto.png" alt="datos" width="600">

Una vez creado seleccionamos el proyecto y el buscador de google cloud buscamos *Gmail API* para habilitarlo.

Cuando lo hayamos habilitado tendremos que crear unas credenciales.

<img src="../assets/img/05-integracion_gmail/integracion-API.png" alt="datos" width="600">

<img src="../assets/img/05-integracion_gmail/integracion-API1.png" alt="datos" width="400">

Primero seleccionamos el tipo de API y le daremos permisos de los datos del usuario

<img src="../assets/img/05-integracion_gmail/integracion-API2.png" alt="datos" width="600">

Luego rellenamos los datos que nos pidan.

<img src="../assets/img/05-integracion_gmail/integracion-API3.png" alt="datos" width="600">

Y en la siguiente pantalla podremos agregar o quitar permisos, le damos y agregamos los permisos que nos interesen

Por último nos pedirá el tipo de aplicación el nombre y añadiremos una URL de redireccionamiento.

La cual será: https//nombre-bbdd-odoo.odoo.com/google_gmail/confirm

<img src="../assets/img/05-integracion_gmail/integracion-API4.png" alt="datos" width="600">

Una vez terminado iremos a credenciales seleccionaremos la que acabamos de crear y aqui tendremos tanto el ID secreto como el ID de cliente para añadirlo a Odoo.

<img src="../assets/img/05-integracion_gmail/integracion-credenciales.png" alt="datos" width="800">

Copiamos el ID de cliente y seleccionamos el proovedor de Google para añadir el ID en la siguiente linea.

<img src="../assets/img/05-integracion_gmail/integracion-IDcliente.png" alt="datos" width="800">

Por último copiamos de nuevo el ID cliente y el ID secreto y lo pegamos en Correos electrónicos que se encuentra en ajustes

<img src="../assets/img/05-integracion_gmail/integracion-correoPersonalizado.png" alt="datos" width="600">



