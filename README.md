# Portfolio Personal — Nancy Vargas

Entrega de PFO1 de **Desarrollo de Sistemas Web (Front End)** — de la Tecnicatura Superior en Desarrollo de Software.  
Landing page responsive desarrollada exclusivamente con **HTML5 semántico y CSS3 puro** (sin frameworks ni JavaScript).

🔗 **Sitio en Vercel:** https://vargasnancy.vercel.app/
🔗 **Perfil de GitHub:** https://github.com/LuNanVarg
🔗 **Portfolio Docente (Padlet):** https://padlet.com/nancyvargasit/portfolio-docente-de-tecnologia-y-computacion-nivel-primario-uhjox40wogfxnss9
---

## Stack y Decisiones Técnicas

- **HTML5 Semántico:** `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<figure>`, `<footer>`.
- **Layout y Responsive:** Flexbox para navegación y componentes; CSS Grid para el Hero, Sobre mí, Skills, Curiosidades y Contacto. Media Queries para adaptación fluida a móviles/tablets.
- **Interactividad nativa (sin JS):**
  - **Menú responsive:** Resuelto con `input:checked` + selector adyacente CSS.
  - **Easter Egg:** Implementado con elementos nativos `<details>` y `<summary>`.
- **Animaciones CSS:** `@keyframes` y `transition` para la ilustración del dragón y barras de habilidades, con soporte de `@media (prefers-reduced-motion: reduce)`.
- **Formulario:** Validación nativa HTML5 (`required`, `type="email"`) y envío directo con `action="mailto:..."`.
- **Tipografías (Google Fonts):** Lilita One (títulos), Nunito Sans (cuerpo) y JetBrains Mono (código y badges).
- **Accesibilidad y Enlaces Externos:** Uso de `target="_blank"` con `rel="noopener noreferrer"` y etiquetas semánticas para enlazar perfiles profesionales (GitHub, LinkedIn y Portfolio Docente en Padlet).

---

## Declaración de Uso de IA

- **Herramientas:** Claude (Anthropic), ChatGPT (OpenAI) y Gemini (Google) — Planes gratuitos.
- **Uso:** Asistencia en la conversión y reestructuración del maquetado desde una versión previa en Python/Flask a HTML/CSS estático, consulta de selectores CSS para interactividad sin JavaScript y revisión de accesibilidad.
- **Criterio propio:** Redacción integral de contenidos, selección de paleta y tipografías, creación de recursos gráficos propios, organización de la estructura y pruebas manuales de responsividad.

------------------------------------------------------------------------

## Estructura del repositorio

``` text
Portfolio/
│
├── index.html
├── README.md
│
├── css/
│   └── style.css
│
└── assets/
    │
    ├── img/
    │   ├── dragon-claro.png
    │   ├── elsa-chan.png
    │   └── Logo2.png
    │
    └── icons/
        ├── icons8-qa.png
        ├── icons8-programacion.png
        ├── icons8-flor.png
        ├── icons8-robotica.png
        ├── icons8-ia.png
        ├── icons8-python.png
        ├── icons8-github.png
        └── ...
```

------------------------------------------------------------------------

## Ejecución local

El proyecto no requiere instalación de dependencias ni servidor.

Se puede clonar el repositorio:

``` bash
git clone https://github.com/LuNanVarg/portfolio.git
```

Luego abrir el archivo:

``` text
index.html
```

directamente en el navegador.

También puede ejecutarse mediante una extensión como **Live Server** en
Visual Studio Code.

------------------------------------------------------------------------

## Responsive

El diseño fue pensado para funcionar en:

-   Desktop.
-   Notebook.
-   Tablet.
-   Smartphone.

Se utilizaron media queries y unidades relativas para adaptar la
interfaz a diferentes resoluciones.

------------------------------------------------------------------------

## Autora

**Nancy Vargas**

Docente de Tecnología · Informática · Robótica\
Desarrollo de Software · QA & Automatización

📍 Buenos Aires, Argentina

🔗 GitHub: https://github.com/LuNanVarg\
🔗 LinkedIn: https://linkedin.com/in/vargasnancy
🔗 Portfolio Docente: https://padlet.com/nancyvargasit/portfolio-docente-de-tecnologia-y-computacion-nivel-primario-uhjox40wogfxnss9

------------------------------------------------------------------------

© 2026 Nancy Vargas

