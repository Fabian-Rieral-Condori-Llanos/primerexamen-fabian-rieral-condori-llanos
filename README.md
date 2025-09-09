# Autor:Fabian Rieral Condori Llanos

Desarrolador y Pentester

examen para complemetario de ING sistemas 

## Proyecto de Manaco tipo landing page para examen html5

Propuesta con Html5 y CSS para landing page semántica y accesible.

### Características del proyecto:
- Estructura HTML5 semántica completa

## Accesibilidad (a11y)

Este proyecto implementa las siguientes características de accesibilidad web:

• **Skip Link**: Se añadió un enlace "Saltar al contenido principal" que aparece al navegar con teclado, permitiendo a usuarios de lectores de pantalla evitar la navegación repetitiva.

• **Navegación por teclado mejorada**: Todos los elementos interactivos (enlaces, botones) son accesibles mediante teclado con indicadores visuales de foco claramente definidos usando `outline` de 3px en color azul (#005fcc).

• **Textos alternativos descriptivos**: Las imágenes de productos incluyen atributos `alt` detallados que describen el tipo de zapato, color y uso recomendado, proporcionando contexto real en lugar de texto genérico.

• **Roles ARIA apropiados**: Se implementaron roles semánticos como `banner`, `main`, `navigation`, `contentinfo` y `list`/`listitem` para mejorar la estructura semántica para tecnologías asistivas.

• **Etiquetas asociadas correctamente**: Los precios incluyen `aria-label` para clarificar la lectura, y los botones tienen `aria-describedby` conectado con texto oculto que explica la acción específica.

• **Soporte para preferencias de usuario**: Se añadió soporte para `prefers-reduced-motion` para usuarios que prefieren animaciones reducidas, deshabilitando todas las transiciones CSS cuando esta preferencia está activa.

### Validación realizada:
- ✅ Contraste de colores verificado (texto negro #333 sobre fondos claros)
- ✅ Navegación completa por teclado probada (Tab, Shift+Tab, Enter, Space)
- ✅ Estructura semántica validada con herramientas de desarrollo del navegador

## SEO

Este proyecto implementa optimización SEO on-page siguiendo las mejores prácticas:

• **Título optimizado**: Se cambió de genérico "MANACO - Calzado de Calidad" a específico "MANACO - Calzado Deportivo, Casual y Formal | Zapatos de Calidad" (71 caracteres) incluyendo palabras clave relevantes y diferenciando tipos de productos.

• **Meta descripción estratégica**: Descripción de 156 caracteres que incluye llamada a la acción, palabras clave primarias (calzado, zapatos, deportivos, casuales, formales) y propuesta de valor única "impulsa tu paso".

• **Open Graph completo**: Implementación de meta tags OG (og:title, og:description, og:image, og:url, og:type, og:site_name, og:locale) para optimizar compartición en redes sociales con imagen placeholder profesional.

• **Estructura de encabezados coherente**: H1 único y descriptivo "Calzado que impulsa tu paso" como título principal, H2 para sección "Productos", H3 para nombres específicos de productos, manteniendo jerarquía semántica clara.