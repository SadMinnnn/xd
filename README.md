# Descripción del Proyecto
Este proyecto utiliza la tecnología de Blazor en C# y tiene como objetivo crear un sitio web con las siguientes características.

Estructura del Proyecto
El proyecto se organiza de la siguiente manera:

Páginas del Sitio
PageWelcome (/): Esta página muestra un mensaje de bienvenida personalizado. Debe incluir un eslogan de la página. Se debe crear un componente interno que reciba el nombre de la página como parámetro.

PageContact (/contact): En esta página, se encuentra un formulario que solicita al usuario ingresar su nombre, correo electrónico, número de teléfono y un mensaje. Después de enviar el formulario, en la parte inferior se mostrará la información de contacto proporcionada con un formato específico.

PageCharacter (/character): Esta página muestra una lista de elementos consumidos de una API. Cada elemento de la lista debe mostrar los campos "name", "status" y "species". Además, se debe agregar un enlace que redirija a la página de detalles de cada elemento.

PageCharacterDetail (/character/{id}/details): En esta página se carga la información detallada del elemento seleccionado. Se deben mostrar los campos "name", "status", "location", "gender" e "imagen". También se debe mostrar el avatar del elemento.

Cómo ejecutar el Proyecto
Para ejecutar el proyecto, sigue los siguientes pasos:

Clona el repositorio en tu máquina local.
Abre la solución del proyecto en tu IDE de preferencia.
Compila y ejecuta el proyecto.
Accede a la URL correspondiente a cada página para ver su contenido.
