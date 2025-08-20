# Cazador-de-precios

Cazador de Precios 🛒
Una aplicación web colaborativa para que una comunidad pueda registrar, validar y comparar precios de productos en diferentes tiendas, construida sin necesidad de un servidor tradicional.

Características Principales
Envío de Ofertas: Formulario dinámico para que los usuarios agreguen nuevos precios, productos, marcas y tiendas.

Búsqueda y Filtros: Búsqueda en tiempo real y filtros por tienda y marca para encontrar ofertas fácilmente.

Votación Comunitaria: Sistema de doble votación para calificar la calidad de una oferta (+1/-1) y su veracidad (+1/-1).

Auto-Moderación: Las publicaciones marcadas como falsas por la comunidad se eliminan automáticamente.

Historial de Precios: Gráficos y listas que muestran la fluctuación del precio de un producto a lo largo del tiempo.

Sección de Comentarios: Permite a los usuarios discutir y añadir información contextual a cada oferta.

Voto Único: Utiliza localStorage para prevenir que un usuario vote múltiples veces en la misma oferta.

Interfaz Responsiva: Diseño profesional que se adapta a computadoras y dispositivos móviles, con una vista de "tarjetas" en pantallas pequeñas.

Inteligencia de Datos: Calcula y muestra el precio por unidad para una comparación justa y destaca la mejor oferta.

Tecnologías Utilizadas
Frontend: HTML, Tailwind CSS, JavaScript (Vanilla)

Backend/API: Google Apps Script

Base de Datos: Google Sheets

Gráficos: Chart.js

Cómo Funciona
El sitio web (index.html) actúa como el frontend. Se comunica con una API creada en Google Apps Script, la cual sirve como un backend "serverless". Este script se encarga de leer y escribir datos en una hoja de cálculo de Google Sheets que funciona como la base de datos principal, almacenando tanto los precios como los comentarios en hojas separadas.
