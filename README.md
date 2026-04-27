Verificador de Números Primos

Una aplicación web interactiva, rápida y elegante desarrollada en un solo archivo. Permite a los usuarios verificar matemáticamente si un número entero dado es un número primo o no.

🚀 Características

Arquitectura de un solo archivo: HTML, CSS (Tailwind) y JavaScript consolidados en un único documento (verificador-primos.html) para máxima portabilidad.

Algoritmo Optimizado: Implementa una lógica matemática eficiente que descarta de forma rápida números pares y múltiplos de tres, iterando únicamente hasta la raíz cuadrada del número para un mejor rendimiento.

Explicación del Resultado: Si un número no es primo, el aplicativo no solo te lo indica, sino que te muestra cuál fue el primer divisor encontrado.

Validación de Entradas: Protege la aplicación alertando al usuario sobre campos vacíos, números decimales y números menores o iguales a 1.

Diseño Responsivo: Interfaz moderna, limpia y adaptable a cualquier tamaño de pantalla (móviles, tablets y escritorio).

Accesibilidad: Soporte para ejecutar la validación presionando la tecla Enter.

🛠️ Tecnologías Utilizadas

HTML5: Estructura semántica de la aplicación.

Tailwind CSS (vía CDN): Framework de utilidades CSS para un diseño ágil, moderno y responsivo sin necesidad de archivos de hojas de estilo externos.

Vanilla JavaScript: Lógica principal del algoritmo y manipulación del DOM, sin depender de librerías o frameworks pesados.

⚙️ Cómo ejecutar el proyecto

Dado que la aplicación se ejecuta íntegramente en el navegador del cliente (Client-side), no requiere de instalaciones complejas ni servidores locales:

Descarga o guarda el código en un archivo llamado verificador-primos.html.

Haz doble clic sobre el archivo para abrirlo directamente en tu navegador web preferido (Google Chrome, Firefox, Safari, Edge, etc.).

Asegúrate de tener conexión a internet la primera vez que lo abres para que el CDN de Tailwind CSS pueda cargar los estilos.

¡Listo! Escribe un número en el campo de texto y presiona "Verificar".

📂 Estructura del Código

El archivo está lógicamente dividido en secciones estándar de la web:

<head>: Contiene los metadatos, la importación de Tailwind CSS y animaciones personalizadas breves en la etiqueta <style>.

<body>: Contiene la interfaz gráfica de usuario (GUI), incluyendo la tarjeta central, los iconos (SVG) y el formulario.

<script>: Alberga la función principal verificarPrimo(), el algoritmo matemático y los eventos del teclado.