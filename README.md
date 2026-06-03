# Patagonia Wingfoil 

Landing page oficial desarrollada para **Patagonia Wingfoil**, la escuela de wingfoil de un amigo en la Patagonia Argentina (Lago Meliquina y San Carlos de Bariloche). 

Este proyecto es una web estática (*Single Page*) diseñada para ser rápida, visualmente inmersiva y orientada a la conversión directa. 
Permite a los usuarios conocer las tarifas de clases, consultar el alquiler de equipos de primera línea (KT Surfing), conocer al fundador y contactarse fácilmente para reservar.

## Características Principales

* **Diseño 100% Responsive:** Adaptable a todos los dispositivos (Mobile, Tablet, Desktop) mediante Flexbox, CSS Grid y Media Queries.
* **UI/UX Inmersiva:** Implementación de un tema oscuro (Dark Theme) con una paleta de colores personalizada (Negro, Gris oscuro y un "Azul Patagonia" de acento).
* **Efectos Parallax:** Animaciones suaves en el scroll interactuando con las imágenes de fondo y el logo principal mediante CSS (`background-attachment: fixed`) y Vanilla JavaScript.
* **Integración de Contacto Rápido:** Botón flotante y *Call to Actions* (CTAs) vinculados directamente a la API de WhatsApp para facilitar reservas.
* **SEO & Social Sharing:** Etiquetas *Meta* y *Open Graph* configuradas para una correcta previsualización al compartir el enlace en redes sociales o WhatsApp.

## Tecnologías Utilizadas

* **HTML5:** Estructura semántica del contenido.
* **CSS3:** Estilos personalizados usando variables `:root`, Grillas y Flexbox. No se utilizaron frameworks externos para mantener la máxima velocidad de carga.
* **JavaScript (Vanilla):** Lógica simple para el efecto parallax del logo principal durante el scroll.
* **Tipografías:** Integración de Google Fonts (`Exo 2` para títulos y `Inter` para cuerpos de texto).
* **Iconografía:** FontAwesome 6.0 para iconos de la interfaz (WhatsApp).

## Instalación y Uso Local

Al ser un proyecto estático sin dependencias de backend, correrlo localmente es muy sencillo:

1. Cloná este repositorio en tu máquina local:
   ```bash
   git clone [https://github.com/tu-usuario/patagonia-wingfoil.git](https://github.com/tu-usuario/patagonia-wingfoil.git)
