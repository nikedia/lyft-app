# **Lyft App** 

* **Track:** _Common Core_
* **Curso:** _Crea tu propia red social_
* **Unidad:** _No reinventes la rueda_
* **Conocimientos técnicos:** _`HTML`, `CSS`, `BOOTSTRAP`, `JQUERY`, etc._

***

## **Objetivo**

El reto consiste en replicar el app [**Lyft**](#), en versión móvil. Se ha pedido añadir un efecto splash al inicio, y que esta redirija a la página principal de la app, el cual contendrá un input de celular, el cual será de 10 dígitos. Luego se generará un código de validación de 3 dígitos a través de un alert. Luego, en otra vista se validará esa clave, y si pasa se pasará a la siguiente vista que consiste en unos input para poner datos generales como nombres, apellidos y email. Una vez se le redireccionará a la vista final del app.

## **Flujo de Aplicación**

*Vista splash con duración de 2 a 5 segundos que redirecciona a tu vista de inicio. La vista de inicio cuenta con dos botones, en esta ocasión seguiremos el flujo de **SING UP**.

![lyft img](assets/documents/splash.png)

* En la siguiente vista tenemos un formulario donde nuestro usuario puede escoger el país y debe ingresar su número de teléfono. El botón de NEXT debe estar deshabilitado hasta que se ingrese un número de 10 dígitos.

![lyft img](assets/documents/ingreso-numero.png)

* Una vez ingresado el número de teléfono se habilita el botón y al dar click debe enviar una alerta con un código generado aleatoriamente (LAB-000) y redireccionar a la siguiente vista.

![lyft img](assets/documents/generacion-codigo.png)

* En esta vista se debe ingresar el código dado anteriormente y una vez hecho esto se habilita el botón que redirecciona a nuestro usuario a la vista donde ingresa sus datos. (Puede tener la opción de enviar otro código.).

![lyft img](assets/documents/verificacion-numero.png)

* Para ingresar sus datos necesitamos un formulario que le pida su nombre, apellido y correo electrónico. Deberá también tener un checkbox para que se acepten los términos y condiciones del servicio.

![lyft img](assets/documents/ingreso-datos.png)

* Ya que se ha realizado lo anterior, sólo se deberá mostrar una vista al usuario que le indique que ha concluido con el registro exitosamente.

![lyft img](assets/documents/final.png)

## Contenido del Repositorio

* Contiene una carpeta en el cual hay un archivo base `index.html` (estructura del proyecto y enlaces CSS y funcionalidades JS). En adición, está el `README.md` que contiene la explicación de este proyecto. Y el pluggin `eslintrc` (ayuda con la validación de la sintaxis del proyecto).

* En la carpeta `assets`, se encuentran las carpetas `icons` (favicon de la pestaña), `documents`  (documentación del proyecto) e `images` (imágenes de referencia del proyecto).

* En la carpeta `vendors,` se encuentran los frameworks  `BOOTSTRAP` y `JQUERY`.

* En la carpeta `views`, se encuentran las diferentes vistas del proyecto.

* En la carpeta `css`, hay un archivo base `main.css` (estilos del proyecto).

* En la carpeta `js`, hay un archivo base `app.js`, `sigunp.1.js` (funcionalidades del  proyecto).

## Herramientas

* VISUAL STUDIO CODE.

## Recursos

* [Jquery Quick API Reference](https://oscarotero.com/jquery/)

## Nota

* La página sólo se ha hecho para dispositivos móviles por el momento.

## Resultado

[Resultado del Proyecto.](#)