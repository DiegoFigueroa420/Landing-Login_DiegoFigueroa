# Landing-Login_DiegoFigueroa
# Resumen del Proyecto

Este proyecto consiste en un conjunto de páginas HTML interconectadas para una aplicación web, estilizadas utilizando un único archivo CSS. La aplicación presenta un sistema de inicio de sesión, una página de registro, una opción de recuperación de contraseña y una "Página de Aterrizaje" que muestra una galería de paisajes naturales.

## Archivos

El proyecto incluye los siguientes archivos:

* `INDEX.HTML`
* `LANDING.HTML`
* `RECUPERAR.HTML`
* `REGISTER.HTML`
* `STYLE.CSS`

## Descripción de los Archivos

### `INDEX.HTML`

Esta es la página principal de inicio de sesión de la aplicación.

* **Propósito**: Permite a los usuarios iniciar sesión con un nombre de usuario y contraseña.
* **Características**:
    * Campos de entrada para nombre de usuario y contraseña.
    * Casilla de verificación "Remember me" (Recordarme).
    * Enlace "Forgot Password" (¿Olvidaste tu contraseña?) (enlaza a `RECUPERAR.HTML`).
    * Botón "Login" (Iniciar sesión).
    * Enlace "¿No tienes una cuenta? Regístrate" (enlaza a `REGISTER.HTML`).
    * Enlace "Landing Page" (Página de Aterrizaje) (enlaza a `LANDING.HTML`).

### `LANDING.HTML`

Esta página sirve como una galería que muestra varios paisajes naturales.

* **Propósito**: Muestra información sobre diferentes parques y atracciones naturales.
* **Características**:
    * Un menú desplegable con enlaces a "Especialistas", "Servicios" y "Contacto" (estos son enlaces de anclaje dentro de la página).
    * Un botón fijo "Login" en el lado izquierdo (enlaza a `INDEX.HTML`).
    * Una sección principal titulada "Conoce a Nuestros Paisajes".
    * Múltiples componentes de "tarjeta", cada uno con:
        * Una imagen de un paisaje natural.
        * Un título (por ejemplo, "Banff (Canadá)").
        * Un párrafo descriptivo sobre el paisaje.
        * Un botón "VISITAR".

### `RECUPERAR.HTML`

Esta página es para la recuperación de contraseña.

* **Propósito**: Permite a los usuarios iniciar el proceso de recuperación de contraseña.
* **Características**:
    * Título "Password Recovery" (Recuperación de Contraseña).
    * Campo de entrada para el nombre de usuario.
    * Botón "Send" (Enviar).
    * Enlace "VOLVER AL LOGIN" (Volver al Inicio de Sesión) (enlaza a `INDEX.HTML`).
    * Enlace "¿No tienes una cuenta? Regístrate" (enlaza a `REGISTER.HTML`).

### `REGISTER.HTML`

Esta página es para el registro de nuevos usuarios.

* **Propósito**: Permite a los usuarios crear una nueva cuenta.
* **Características**:
    * Título "REGISTER" (REGISTRO).
    * Campos de entrada para Nombre, Apellido, Contraseña, Confirmar Contraseña y Correo Electrónico.
    * Casilla de verificación "Remember me" (Recordarme).
    * Botón "Register" (Registrarse).
    * Enlace "VOLVER AL LOGIN" (Volver al Inicio de Sesión) (enlaza a `INDEX.HTML`).

### `STYLE.CSS`

Esta hoja de estilos proporciona el estilo visual para todas las páginas HTML.

* **Propósito**: Define el diseño, los colores, la tipografía y el comportamiento adaptable de la aplicación web.
* **Elementos clave de estilo**:
    * Importa la fuente 'Bebas Neue' de Google Fonts.
    * Establece una imagen de `background` para el `body`.
    * Estilos para el contenedor principal `main`, incluyendo `backdrop-filter` para un efecto de vidrio esmerilado.
    * Botón `login-button` con posición fija y texto vertical.
    * Estilos para `cards-container` y `card` para la galería de paisajes, incluyendo efectos al pasar el ratón.
    * Estilos para el menú `dropdown` para el botón "MENU" en la página de aterrizaje.
    * Estilos generales para campos de entrada, botones y enlaces en los formularios de inicio de sesión, registro y recuperación.
    * Ajustes responsivos para pantallas más pequeñas utilizando `@media` queries.
    * Estilos para la clase `wrapper`, que actúa como contenedor para los formularios.
