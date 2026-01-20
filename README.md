# Rojo Carmín - Proyecto integrando JS

# Rojo Carmín - Simulador de Cotizaciones JS 🎨

Este proyecto es parte del curso de **JavaScript** en Coderhouse. Consiste en un simulador interactivo integrado en el sitio de "Rojo Carmín", una plataforma dedicada al diseño editorial, arquitectura y arte. El trabajo de HTML y CSS, corresponde al final de desarrollo web - 

## Funcionalidad
El simulador permite a los artistas presentar su obra y recibir una oferta estimada de forma automática. 
- **Entrada:** El usuario completa su nombre y un mensaje detallando su obra.
- **Proceso:** El sistema analiza palabras clave en el mensaje (Pintura, Editorial, Fotografía, Branding, Arquitectura), calcula el valor en USD, aplica una comisión de gestión y lo convierte a Pesos Argentinos (ARS).
- **Salida:** Se renderiza una respuesta dinámica directamente en el DOM (dentro de un elemento `<article>`) con los valores finales.

## Tecnologías Aplicadas
* **DOM & Eventos:** Captura de datos mediante formularios y actualización dinámica del HTML sin recargar la página.
* **Objetos y Arrays:** Gestión de categorías de servicios y precios base.
* **LocalStorage:** Persistencia de la última oferta generada para que el usuario pueda consultarla incluso tras recargar el sitio.
* **JSON:** Serialización de datos para almacenamiento.

## Cómo probar el simulador
1. Navega a la sección de **Contacto**.
2. Completa tu nombre y correo.
3. En el campo de **Comentario**, asegúrate de incluir una de las siguientes categorías: 
   - *Pintura, Editorial, Fotografía, Branding o Arquitectura*.
4. Haz clic en **Enviar**.
5. ¡Verás aparecer tu cotización personalizada con un diseño integrado al sitio!

---
**Desarrollado por:** Fiamma Pedruzzi  
