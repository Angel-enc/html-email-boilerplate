# Mi Primer Proyecto: Email Development & Salesforce Marketing Cloud

Este es mi primer proyecto práctico de maquetación de emails profesionales. Está diseñado en el ecosistema de **Salesforce Marketing Cloud (SFMC)**, enfocado en aprender cómo enviar correos que se vean bien en cualquier lugar.

## ¿Que he aprendido con este proyecto?
Este repositorio es el resultado de mi investigación y práctica  sobre los retos de correos electrónicos:

* **Maquetación con Tablas:** He aprendido que los emails no se hacen como las web modernas. He usado tablas anidadas para que el diseño no se rompa, especialmente en **Outlook**.
* **El "Truco" de los Botones (VML):** Descubrí que Outlook ignora el CSS moderno, así que he implementado código **VML** para que los botones mantenga su color y forma.
* **Personalización con AMPScript:** He dado mis primeros pasos con el lenguaje de Salesforce (**AMPScript**) para crear saludos dinámicos ( como el `%%=v(@nombre)=%%``).
* **Flujo de Trabajo (Build):** He configurado un entorno con **Node.js** y **Juice** para que mi CSS se inyecte automáticamente en el HTML, siguiendo un proceso profesional.

## Integrtación con MuleSoft (Concepto)
Aunque estoy empezando, entiendo que este email es el final de un camino:
1. **MuleSoft** mueve los datos de los clientes desde donde estén hacia Salesforce.
2. **Marketing Cloud** recibe esos datos.
3. **Mi Código HTML** usa esos datos para que cada persona reciba un correo único.

## Cómo ver el proyecto en tu PC
Para probarlo, necesitas tener Node.js y ejecutar en orden estos comandos en tu terminal:
1. Instalar las herramientas: `npm install`.
2. Procesar el código: `npm run build`.
3. Ver el resultado: `npx serve dist`.

---
*Este es un proyecto de aprendizaje continuo. Mi meta es dominar la arquitectura de datos y la comunicación digital en el ecosistema Salesforce.*
