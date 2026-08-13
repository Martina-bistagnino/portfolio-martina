# Portfolio personal — PFO1

## Descripción

Este proyecto corresponde a la **PFO1** y consiste en el desarrollo de una landing page de portfolio personal utilizando **HTML y CSS**.

La página presenta mi perfil como desarrolladora web con enfoque frontend, mi formación, mis habilidades técnicas, mi experiencia actual dentro del área de Sistemas y algunos intereses personales vinculados a la creatividad, el diseño y la comunicación.

El objetivo fue construir una landing responsive, semántica y visualmente coherente, aplicando los contenidos trabajados durante la materia.

---

## Tecnologías utilizadas

* HTML5
* CSS3
* Google Fonts
* Flexbox
* CSS Grid
* Media Queries
* Variables CSS
* Transiciones y animaciones
* Git
* GitHub
* Vercel

---

## URL del proyecto publicado

**Vercel:**
https://portfolio-martina-chi.vercel.app

portfolio-martina-chi.vercel.app

**GitHub:**

https://github.com/Martina-bistagnino/portfolio-martina.git

---

## Perfil de GitHub

**GitHub:**
https://github.com/Martina-bistagnino

---

## Decisiones de diseño

Para la identidad visual elegí combinar **minimalismo contemporáneo con una influencia Art Déco**.

El minimalismo aparece principalmente en la organización clara del contenido, el uso del espacio, la cantidad controlada de elementos visuales y una jerarquía tipográfica definida.

La influencia Art Déco se expresa mediante:

* Marcos y líneas finas.
* Formas geométricas.
* Rombos y elementos simétricos.
* Detalles dorados.
* Tipografía serif en títulos.
* Composición elegante y estructurada.

La paleta de colores utiliza tonos crema, marrón, terracota, rosa y dorado suave. La intención fue conseguir una estética cálida, elegante y profesional, evitando el estilo oscuro y tecnológico que suele aparecer en muchos portfolios de desarrollo.

---

## Tipografías

Se utilizaron dos tipografías de Google Fonts:

* **Cormorant Garamond:** utilizada principalmente en títulos y elementos destacados. Su estilo serif aporta elegancia y acompaña la inspiración Art Déco.
* **Montserrat:** utilizada en textos, navegación, botones y formularios para mantener una lectura clara y moderna.

La combinación permite diferenciar visualmente los títulos del contenido general y generar una jerarquía tipográfica más marcada.

---

## Maquetación con Flexbox y Grid

Durante el desarrollo utilicé tanto **Flexbox** como **CSS Grid**, dependiendo de las necesidades de cada componente.

**CSS Grid** fue utilizado principalmente para estructuras bidimensionales, como:

* La sección principal.
* Las tarjetas de habilidades.
* La sección de intereses.
* La sección de contacto.
* El recorrido profesional y académico.

**Flexbox** fue utilizado para elementos que necesitaban una distribución principalmente unidimensional, como:

* La barra de navegación.
* Los botones.
* Las etiquetas de tecnologías.
* Algunos grupos de enlaces.
* El footer.

La combinación de ambas herramientas permitió mantener una estructura flexible, ordenada y adaptable a distintos tamaños de pantalla.

---

## Responsive Design

El sitio fue diseñado para adaptarse a computadoras, tablets y dispositivos móviles.

Para lograrlo utilicé:

* Media Queries.
* Unidades relativas.
* `clamp()`.
* `min()`.
* Porcentajes.
* `rem`.
* `vw`.
* Columnas flexibles con Grid.
* Elementos reorganizados mediante Flexbox.

En pantallas pequeñas las secciones que originalmente utilizan varias columnas pasan a una sola columna para mejorar la lectura y evitar el desplazamiento horizontal.

---

## Interactividad y animaciones

La landing incluye distintos efectos visuales desarrollados únicamente con CSS.

Se incorporaron:

* Transiciones en botones.
* Efectos hover en enlaces.
* Efectos hover en tarjetas.
* Animaciones de entrada en la presentación principal.
* Animación de aparición de la fotografía.
* Scroll suave entre secciones.

Las animaciones fueron pensadas para acompañar la experiencia sin sobrecargar la interfaz.

Además, se agregó soporte para:

```css
@media (prefers-reduced-motion: reduce)
```

Esto permite reducir o eliminar las animaciones cuando una persona tiene configurada esa preferencia de accesibilidad en su dispositivo.

---

## Accesibilidad y HTML semántico

Se utilizaron etiquetas semánticas para estructurar correctamente el contenido:

* `header`
* `nav`
* `main`
* `section`
* `article`
* `footer`

También se incorporaron:

* Texto alternativo mediante `alt` en imágenes.
* `aria-label` en elementos que necesitan una descripción adicional.
* `label` vinculados correctamente a los campos del formulario.
* Estados `focus-visible` para mejorar la navegación mediante teclado.
* Jerarquía adecuada de títulos.

Estas decisiones permiten mejorar la comprensión de la página tanto para usuarios como para tecnologías de asistencia.

---

## Estructura del proyecto

```text
portfolio-martina/
│
├── index.html
├── README.md
│
├── css/
│   └── styles.css
│
└── img/
    └── Martina.png
```

---

## Contenido de la landing

La página incluye las siguientes secciones:

* Navegación principal.
* Presentación personal.
* Sobre mí.
* Habilidades.
* Mi recorrido.
* Más allá del código.
* Contacto.
* Enlaces a redes sociales.
* Footer.

La sección **Mi recorrido** permite mostrar mi experiencia actual dentro del área de Sistemas, mi formación académica y el aprendizaje complementario mediante cursos.

La sección **Más allá del código** muestra algunos intereses personales relacionados con diseño, fotografía, comunicación, viajes, música y lectura.

---

## Formulario de contacto

El formulario contiene:

* Nombre.
* Email.
* Mensaje.

Cada campo cuenta con su correspondiente etiqueta `label`.

El formulario es demostrativo y fue desarrollado sin servicios externos ni backend, por lo que no realiza el envío real de información.

---

## Imagen utilizada

La fotografía utilizada en la presentación principal es una **fotografía propia**.

La imagen no fue generada ni modificada mediante inteligencia artificial.

---

## Perfil técnico

Actualmente cuento con conocimientos **intermedios/avanzados en HTML, CSS y JavaScript**.

También tengo conocimientos en:

* TypeScript.
* Git y GitHub.
* MySQL.
* Backend.
* Soporte IT.
* Infraestructura.

Actualmente continúo profundizando mis conocimientos en **Angular y frameworks frontend**.

---

## Formación y experiencia

Actualmente estudio una **Tecnicatura en Desarrollo de Software**.

Además, realicé cursos relacionados con:

* JavaScript.
* MySQL.
* Desarrollo web.

En el ámbito laboral trabajo en el área de **Sistemas de Distribuidora Metropolitana**, donde realizo tareas vinculadas tanto al desarrollo como al soporte de infraestructura tecnológica de la empresa y sus sucursales.

Mi objetivo profesional es continuar orientando mi perfil hacia el **desarrollo frontend**.

---

## Uso de inteligencia artificial

Para realizar esta PFO1 utilicé **ChatGPT mediante el plan pago ChatGPT Plus**.

Ya había utilizado previamente ChatGPT para realizar consultas relacionadas con programación, revisión de código, resolución de errores y dudas técnicas, por lo que contaba con experiencia previa utilizando la herramienta como apoyo durante procesos de desarrollo.

En este proyecto utilicé ChatGPT principalmente como herramienta de **revisión**.

La herramienta fue utilizada para:

* Revisar la organización general de la landing.
* Revisar la estructura semántica del HTML.
* Revisar estilos CSS.
* Revisar el comportamiento responsive.
* Detectar posibles mejoras de accesibilidad.
* Revisar la legibilidad del contenido.
* Revisar la redacción del README.
* Analizar posibles mejoras de diseño.

Las decisiones visuales, la elección de colores, la estética general, la información personal, la organización del contenido y las modificaciones finales fueron revisadas y adaptadas con criterio propio.

También revisé el código para comprender qué función cumplía cada sección y realicé ajustes propios antes de publicar la versión final.

No se utilizaron imágenes generadas ni modificadas mediante inteligencia artificial.

---

## Publicación

El proyecto fue versionado utilizando **Git y GitHub**.

La landing fue publicada mediante **Vercel**, conectando el repositorio de GitHub con la plataforma.

Esto permite que las nuevas versiones del proyecto puedan publicarse automáticamente al realizar nuevos `push` al repositorio.

---

## Autora

**Martina Bistagnino**

Desarrolladora Web | Enfoque Frontend
