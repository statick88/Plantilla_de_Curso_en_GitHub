<!--
  <<< Notas del autor: Encabezado del curso >>>
  Lee <https://skills.github.com/quickstart> para obtener más información sobre cómo crear cursos utilizando esta plantilla.
  Incluye una imagen de 1280×640, el nombre del curso en minúsculas y una descripción concisa en énfasis.
  En la configuración de tu repositorio: habilita el repositorio como plantilla, agrega tu imagen de redes sociales de 1280×640, elimina automáticamente las ramas principales.
  Junto a "Acerca de", agrega la descripción y etiquetas; desactiva las versiones, paquetes y entornos.
  Agrega tu licencia de código abierto, GitHub utiliza Creative Commons Attribution 4.0 International.
-->

# Curso: Cómo Crear Cursos a través de GitHub

_Aprende a utilizar GitHub y sus funciones para diseñar, desarrollar y ofrecer cursos educativos de manera efectiva._

<!--
  <<< Sección: Instrucciones para Clonar y Personalizar la Plantilla >>>
-->

## Instrucciones para Clonar y Personalizar la Plantilla:

1. Haz clic en el botón "Usar esta plantilla" en la parte superior de esta página para crear un nuevo repositorio basado en esta plantilla.

2. Clona el repositorio recién creado en tu computadora local:
```bash
git clone URL_del_Repositorio
```

# Curso: Cómo Crear Cursos a través de GitHub

_Aprende a utilizar GitHub y sus funciones para diseñar, desarrollar y ofrecer cursos educativos de manera efectiva._

<!--
  <<< Notas del autor: Inicio del curso >>>
  Incluye el botón de inicio, una nota sobre los minutos de Acciones,
  y dile al estudiante por qué debería realizar el curso.
  Cada paso debe estar dentro de <details>/<summary>, con un `id` establecido.
  El primer <details> debe tener `open` también.
  No uses comillas en los atributos de la etiqueta <details>.
-->

<details id=0 open>
<summary><h2>Bienvenida</h2></summary>

¡Bienvenido al Curso "Cómo Crear Cursos a través de GitHub"! En este curso, aprenderás cómo utilizar GitHub para diseñar, desarrollar y presentar cursos educativos en línea de manera efectiva utilizando herramientas y prácticas modernas.

- **¿Para quién es este curso?**: Educadores, formadores, creadores de contenido, desarrolladores y cualquier persona interesada en crear cursos en línea.
- **¿Qué aprenderás?**: Aprenderás cómo estructurar y organizar el contenido del curso, utilizar Markdown para formatear materiales educativos y aprovechar GitHub Actions para automatizar tareas de creación y despliegue.
- **¿Qué construirás?**: Crearás un curso de muestra utilizando este mismo proceso y plantilla.
- **Prerrequisitos**: Conocimientos básicos de Git y GitHub. No se requieren conocimientos de programación.
- **Duración**: Este curso consta de 5 pasos y se puede completar en aproximadamente 2 horas.

## ¿Cómo Iniciar el Curso?

1. Haz clic en el botón "Iniciar Curso" y crea un nuevo repositorio basado en esta plantilla.
2. Personaliza la descripción, los objetivos y la imagen del curso en tu repositorio.
3. Sigue los pasos de cada sección para aprender a crear cursos efectivos en línea.

</details>

<!--
  <<< Notas del autor: Paso 1 >>>
  Elige 3-5 pasos para tu curso.
  El primer paso siempre es el más difícil, ¡así que elige algo fácil!
  Enlaza a docs.github.com para más explicaciones.
  Anima a los usuarios a abrir nuevas pestañas para los pasos.
  TBD-step-1-notes.
-->

<details id=1>
<summary><h2>Paso 1: Diseño del Curso</h2></summary>

_¡Empecemos desde lo básico del curso!_

El primer paso para crear un curso efectivo es planificar y diseñar la estructura general del curso. Esto incluye decidir los módulos, las lecciones y las actividades que formarán parte del curso. Una estructura clara y lógica facilitará la navegación y el aprendizaje de los estudiantes.

**Conceptos clave**:
- Módulos y lecciones.
- Contenido teórico y práctico.
- Actividades y evaluaciones.

### :keyboard: Actividad: Diseña la Estructura del Curso

1. Abre una nueva pestaña en tu navegador y ve a la sección "Proyectos" de tu repositorio.
2. Crea un proyecto llamado "Diseño del Curso" y agrega columnas para módulos, lecciones y actividades.
3. Define los módulos principales del curso y agrega tarjetas para cada lección y actividad planificada.
4. Utiliza descripciones y comentarios en las tarjetas para detallar el contenido de cada lección.

</details>

<!--
  <<< Notas del autor: Paso 2 >>>
  Comienza este paso reconociendo el paso anterior.
  Define términos y enlaza a docs.github.com.
  TBD-step-2-notes.
-->

<details id=2>
<summary><h2>Paso 2: Creación de Contenido</h2></summary>

_¡Ahora es el momento de crear el contenido del curso!_

Una vez que hayas planificado la estructura, puedes comenzar a crear el contenido real del curso. Utilizar Markdown te permitirá dar formato al contenido de manera clara y legible, e incluir elementos como texto, imágenes, enlaces y más.

**Conceptos clave**:
- Uso de Markdown.
- Formato de texto y títulos.
- Inclusión de imágenes y enlaces.

### :keyboard: Actividad: Crea Contenido con Markdown

1. Abre una nueva pestaña en tu navegador y ve a la carpeta del primer módulo en tu repositorio.
2. Crea un archivo Markdown para la primera lección del curso.
3. Utiliza encabezados, listas y otros elementos de Markdown para estructurar y dar formato al contenido.
4. Incorpora imágenes relevantes utilizando la sintaxis adecuada.
5. Agrega enlaces a recursos externos o actividades relacionadas.

</details>

<!--
  <<< Notas del autor: Paso 3 >>>
  Comienza este paso reconociendo el paso anterior.
  Define términos y enlaza a docs.github.com.
  TBD-step-3-notes.
-->

<details id=3>
<summary><h2>Paso 3: Automatización con GitHub Actions</h2></summary>

_¡Optimiza tu flujo de trabajo con GitHub Actions!_

Automatizar ciertas tareas puede ahorrarte tiempo y garantizar la coherencia en la creación y despliegue de cursos. GitHub Actions te permite definir flujos de trabajo personalizados que se activan en respuesta a eventos específicos, como confirmaciones de código o cambios en el repositorio.

**Conceptos clave**:
- Configuración de flujos de trabajo.
- Uso de eventos y disparadores.
- Ejecución de scripts y acciones automatizadas.

### :keyboard: Actividad: Configura un Flujo de Trabajo

1. Abre una nueva pestaña en tu navegador y ve a la sección "Acciones" de tu repositorio.
2. Crea un nuevo archivo de flujo de trabajo utilizando el asistente de configuración.
3. Define un flujo de trabajo que se active cuando se confirme nuevo contenido en el repositorio.
4. Especifica pasos para clonar el repositorio en un entorno de prueba y asegurarte de que funcione según lo esperado.

</details>

<!--
  <<< Notas del autor: Paso 4 >>>
  Comienza este paso reconociendo el paso anterior.
  Define términos y enlaza a docs.github.com.
  TBD-step-4-notes.
-->

<details id=4>
<summary><h2>Paso 4: Colaboración y Comentarios</h2></summary>

_¡Recopila comentarios valiosos y mejora tu curso!_

A medida que avanzas en la creación de tu curso, es esencial recibir comentarios de otros y colaborar en mejoras. GitHub proporciona herramientas para facilitar la colaboración, como la posibilidad de realizar revisiones de código, recibir comentarios en solicitudes de extracción y mantener conversaciones dentro de los problemas.

**Conceptos clave**:
- Revisiones de código y comentarios.
- Uso de problemas para discutir mejoras.
- Gestión de colaboradores y contribuciones.

### :keyboard: Actividad: Solicita Comentarios y Realiza Revisiones

1. Abre una nueva pestaña en tu navegador y navega a la sección de "Solicitudes de Extracción" en tu repositorio.
2. Crea una nueva solicitud de extracción para una parte específica del curso que desees revisar.
3. Invita a otros colaboradores a revisar y comentar en la solicitud de extracción.
4. Discute los comentarios y realiza cambios en el contenido según sea necesario.
5. Agradece a los colaboradores por sus contribuciones y cierra la solicitud de extracción cuando estés satisfecho con los cambios.

</details>

<!--
  <<< Notas del autor: Paso 5 >>>
  Comienza este paso reconociendo el paso anterior.
  Define términos y enlaza a docs.github.com.
  TBD-step-5-notes.
-->

<details id=5>
<summary><h2>Paso 5: Publicación y Promoción</h2></summary>

_¡Tu curso está listo para el mundo!_

Una vez que hayas completado y perfeccionado tu curso, es hora de publicarlo y promocionarlo. Utiliza GitHub Pages para crear un sitio web para tu curso y promociona tu contenido a través de redes sociales y otros canales.

**Conceptos clave**:
- Publicación con GitHub Pages.
- Promoción en redes sociales y comunidades.
- Recopilación de comentarios y mejoras continuas.

### :keyboard: Actividad: Publica tu Curso y Anuncia su Lanzamiento

1. Abre una nueva pestaña en tu navegador y navega a la sección de "Configuración" en tu repositorio.
2. Habilita GitHub Pages para el repositorio y elige una plantilla o diseño para tu sitio web del curso.
3. Agrega contenido y detalles sobre el curso en el sitio web de GitHub Pages.
4. Crea publicaciones en redes sociales y anuncia el lanzamiento de tu curso.
5. Alienta a los estudiantes a inscribirse en el curso y a proporcionar comentarios para futuras mejoras.

</details>

<!--
  <<< Notas del autor: Final >>>
  Revisa lo que hemos aprendido, pide retroalimentación, proporciona los próximos pasos.
-->

<details id=X>
<summary><h2>Cierre</h2></summary>

_¡Felicidades, has completado el Curso "Cómo Crear Cursos a través de GitHub"!_

Has aprendido cómo planificar, diseñar, crear, automatizar y promocionar cursos educativos en línea utilizando GitHub y sus herramientas. Ahora tienes las habilidades y conocimientos para compartir tus conocimientos con estudiantes de todo el mundo.

### ¿Qué Sigue?

- Aplica estos conceptos para crear cursos sobre diferentes temas y disciplinas.
- Continúa mejorando tus cursos en función de los comentarios y la retroalimentación de los estudiantes.
- Explora otras características avanzadas de GitHub para enriquecer aún más tus cursos.

¡Gracias por tomar este curso y feliz creación de cursos educativos a través de GitHub!

</details>

<!--
  <<< Notas del autor: Pie de página >>>
  Agrega un enlace para obtener soporte, página de estado de GitHub, código de conducta, enlace de licencia.
-->

---

&copy; Año [Tu Nombre] &bull; [Código de Conducta](URL_del_Código_de_Conducta) &bull; [Licencia CC-BY-4.0](URL_de_la_Licencia)
