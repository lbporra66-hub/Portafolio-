# Bitácora de Uso de Inteligencia Artificial

## Consulta 1
- **Fecha:** 11 de Noviembre de 2026
- **Herramienta utilizada:** AI Assistant
- **Objetivo:** Generar una estructura HTML5 semántica limpia para mi portfolio personal.
- **Prompt completo:** 
  > "Necesito una estructura semántica para un portfolio con encabezado, navegación, presentación, sobre mí, proyectos, habilidades, contacto y pie de página. Usá solamente HTML5, sin CSS, JavaScript ni frameworks. Marcá con [COMPLETAR] la información que no conozcas y explicá la función de las etiquetas."
- **Parte utilizada:** La maquetación de etiquetas `<header>`, `<nav>`, `<main>`, `<section>`, `<article>` y `<footer>`.
- **Cambios realizados por mí:** Completé los campos personales adaptándolos a mi perfil (estudiante de informática y peleador de MMA amateur), ingresé los nombres reales de mis tres proyectos y configuré las rutas relativas de las imágenes.
- **¿Qué comprendí?** Comprendí la diferencia entre una etiqueta divisoria neutra (`<div>`) y etiquetas semánticas (`<article>`, `<section>`), lo cual mejora la estructura y accesibilidad del sitio.
- **¿Qué descarté y por qué?** Descarté etiquetas de formulario complejas para la sección de contacto, ya que en la versión 0.1 solo se solicita publicar información de contacto segura.

---

## Consulta 2
- **Fecha:** 11 de Noviembre de 2026
- **Herramienta utilizada:** AI Assistant
- **Objetivo:** Definir el CSS inicial usando variables para un estilo oscuro y deportivo.
- **Prompt completo:** 
  > "Mi portfolio tiene estilo oscuro moderno/deportivo, usa rojo (#e11d48), azul (#2563eb) y fondo oscuro (#0f172a), y debe transmitir disciplina, tecnología y potencia. Creá un CSS inicial con variables de color, tipografía legible, espaciados y tarjetas. Usá CSS puro, sin frameworks ni animaciones complejas. Explicá cada bloque."
- **Parte utilizada:** Definición del bloque `:root` para variables de color, diseño de tarjetas `.tarjeta` con Grid Layout y pseudo-clases `:hover`.
- **Cambios realizados por mí:** Ajusté los márgenes internos (`padding`) y agregué bordes a los contenedores de las habilidades para darles mayor jerarquía visual.
- **¿Qué comprendí?** Aprendí a utilizar variables CSS (`var(--color)`) para centralizar el tema visual y cómo `grid-template-columns: repeat(auto-fit, ...)` ayuda a que el sitio sea adaptable sin requerir reglas complejas.
- **¿Qué descarté y por qué?** Descarté reglas de animaciones en JavaScript que la IA sugirió, respetando la pauta de la clase de mantener la versión 0.1 simple y puramente en HTML/CSS.
