# Easy Ticket

Segunda entrega del proyecto: maquetación de dos pantallas con HTML5 y CSS3 puro (sin frameworks, librerías ni preprocesadores)

**Módulo:** Maquetación con CSS: Flexbox, Grid y Diseño Responsive
**Institución:** Universidad Centro Americana José Simeón Cañas (UCA)

## Descripción

Easy Ticket es una plataforma para encontrar y asegurar boletos de eventos culturales: música, teatro, arte y más, nuestro repositorio contiene la maquetación de dos pantallas del flujo de acceso diseñado en Figma durante la primera entrega:

- **Iniciar sesión** (`index.html`): pantalla de bienvenida con el formulario de acceso
- **Crear cuenta** (`registro.html`): formulario de registro de nuevos usuarios

Ambas pantallas están enlazadas entre sí mediante rutas relativas.

## Diseño en Figma

Prototipo de la primera entrega: [Identidad de marca - Easy Ticket](https://www.figma.com/design/bTfL013InOnT5Fa00BS7A3/Identidad-de-marca?node-id=0-1&t=b1Tm8w38dS6SM0F7-0)

## Integrantes

- Luis Enrique Pacheco Aguilar
- Andres Alessandro Herrera Orellana

## Tecnologías

- HTML5 semántico
- CSS3 puro: Flexbox, Grid y variables CSS
- Diseño responsive con 3 breakpoints:
  - Desktop: `min-width: 1024px`
  - Tablet: `min-width: 768px` y `max-width: 1023px`(en proceso)
  - Mobile: `max-width: 767px (en proceso)`

## Estructura del proyecto


Easy-ticket-UCA
 index.html         # Pantalla 1: Iniciar sesión
 registro.html      # Pantalla 2: Crear cuenta
 css/
 └── style.css      # Hoja de estilos externa
 img/               # Logo e imágenes
 README.md


## Cómo visualizar el proyecto

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/Lpacheco21/Easy-ticket-UCA.git
   ```
2. Abrir `index.html` en el navegador 
3. Para probar el diseño responsive, redimensionar la ventana del navegador o usar las herramientas de desarrollador presionando F12
