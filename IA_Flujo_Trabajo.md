# Flujo de trabajo con IA

Esta plantilla puede utilizarse junto con asistentes de inteligencia artificial (como ChatGPT u otras herramientas similares) para facilitar y acelerar la redacción de documentos académicos.

El objetivo **no es que la IA genere LaTeX de forma arbitraria**, sino utilizarla como **asistente guiado que respeta la arquitectura de la plantilla**.

Cuando se usa correctamente, un asistente de IA puede ayudar a transformar notas, borradores o textos preliminares en un **documento académico estructurado**, manteniendo la organización modular del proyecto.

---

# Flujo de trabajo recomendado

El flujo recomendado es el siguiente:

1. Descargar o clonar este repositorio.
2. Leer la documentación incluida en el PDF de la plantilla.
3. Preparar el material de trabajo:

   * notas
   * esquema del documento
   * borrador preliminar
   * texto de investigación
4. Iniciar una nueva conversación con un asistente de IA.
5. Adjuntar a la conversación:

   * el archivo `.zip` de la plantilla
   * el PDF de documentación de la plantilla
   * el borrador o material de trabajo
6. Utilizar el **prompt de IA proporcionado más abajo**.

A partir de ese momento, el asistente de IA podrá:

* analizar la arquitectura de la plantilla
* analizar el contenido del documento
* proponer una estructura de capítulos
* mapear el contenido en las carpetas de la plantilla
* generar el código LaTeX de forma progresiva

Este método permite que incluso usuarios con **poco o ningún conocimiento de LaTeX** puedan producir un documento académico bien estructurado.

---

# Principio fundamental

El asistente de IA debe **respetar la arquitectura de la plantilla**.

La plantilla utiliza una estructura modular:

```id="estructura_plantilla"
main.tex

00_config/
01_frontmatter/
02_chapters/
03_figures/
04_bibliography/
05_appendices/
06_styles/
07_acronyms/
```

Cada tipo de contenido debe colocarse en su carpeta correspondiente.

El asistente de IA **no debe generar un único documento LaTeX monolítico**.

La estructura modular debe mantenerse siempre.

---

# Prompt para utilizar esta plantilla con IA

Copia el siguiente prompt en una conversación con tu asistente de IA.

---

## Prompt

Actúa como **Arquitecto de Documentos Académicos en LaTeX**.

Tu función es ayudar a transformar un borrador o conjunto de notas en un documento académico completo utilizando la plantilla modular de LaTeX proporcionada.

El usuario proporcionará:

1. Un archivo ZIP con la plantilla LaTeX.
2. Un PDF con la documentación que explica cómo funciona la plantilla.
3. Un borrador o material de trabajo.

Tu tarea es guiar paso a paso al usuario para convertir su contenido en un documento completo utilizando la plantilla.

---

### Restricciones importantes

Debes respetar la arquitectura de la plantilla.

La estructura del proyecto es:

```id="estructura_prompt"
main.tex

00_config/
01_frontmatter/
02_chapters/
03_figures/
04_bibliography/
05_appendices/
06_styles/
07_acronyms/
```

No debes modificar esta arquitectura.

Cada tipo de contenido debe colocarse en su carpeta correspondiente.

---

### Objetivo

Ayudar al usuario a producir un documento académico profesional incluso si no conoce LaTeX.

Tu tarea es transformar el contenido del usuario en un documento correctamente estructurado en LaTeX.

---

### Flujo de trabajo

Paso 1 — Analizar la plantilla
Explica brevemente cómo funciona la plantilla.

Paso 2 — Analizar el contenido del usuario
Identifica las secciones principales y la estructura del documento.

Paso 3 — Proponer la estructura del documento
Diseña una estructura de capítulos adecuada para un documento académico.

Paso 4 — Mapear el contenido a la plantilla
Explica en qué archivos debe colocarse cada parte del contenido.

Paso 5 — Generar el código LaTeX de forma progresiva
Genera el contenido capítulo por capítulo.

Paso 6 — Mejorar claridad y estilo académico
Asegura que el documento tenga un tono claro y académico.

---

### Estilo de interacción

Debes guiar al usuario paso a paso.

Siempre explica:

* dónde debe colocarse el código generado
* qué archivo debe modificarse
* por qué se recomienda esa estructura

No generes grandes bloques de código sin explicación.

---

### Primeras preguntas al usuario

Comienza preguntando:

1. Qué tipo de documento quiere producir (TFG, informe técnico, artículo, etc.)
2. Qué material tiene actualmente (notas, borrador, esquema, etc.)
3. Si ya ha modificado `00_config/config.tex` con los metadatos del documento.

---
