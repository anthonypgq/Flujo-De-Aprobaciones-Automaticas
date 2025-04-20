# 📧 Flujo de Aprobación para Conferencias
Este proyecto fue desarrollado en Power Automate y tiene como objetivo automatizar el proceso de invitación y aprobación de conferencistas a través de correos electrónicos interactivos, con respaldo en un archivo de Excel Online (OneDrive o SharePoint).

## 📄 Descripción general
El flujo está conectado a una tabla de Excel que contiene una lista de personas seleccionadas para participar como conferencistas. A partir de esa lista, se envían automáticamente correos electrónicos de solicitud de aprobación a cada persona.

## 🔁 Funcionamiento del flujo
Se parte de una tabla en Excel con información de los conferencistas, incluyendo:

* Nombre

* Correo electrónico

* Columna de control para activar el envío de solicitud

* Columna de estado de aprobación

El flujo revisa la tabla y, según una columna específica (por ejemplo, "¿Enviar aprobación?"), envía un correo electrónico con una solicitud de aprobación a cada persona seleccionada.

El destinatario recibe un correo con dos opciones: Aceptar o Rechazar la invitación a participar como conferencista.

Según la respuesta del usuario:

* Si acepta, la columna de estado en la tabla se actualiza con el valor "Aceptado".

* Si rechaza, se actualiza con el valor "Rechazado".

## 🛠️ Requisitos
* Cuenta activa en Power Automate.

* Archivo de Excel alojado en OneDrive o SharePoint, con una tabla correctamente estructurada.

* Permisos para enviar correos electrónicos desde el entorno de Power Automate.

## 🎥 Créditos
Esta aplicación fue desarrollada tomando como referencia el siguiente video del canal Cesar Villanueva | Dynamics Axperts en YouTube:

🔗 Integra Power Automate con Excel
(https://www.youtube.com/watch?v=O71SQQ6XATY)
