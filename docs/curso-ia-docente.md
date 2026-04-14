# Herramientas de Inteligencia Artificial para la Creación de Contenido Didáctico

!!! note ""
    Los docentes preparamos materiales durante horas que a veces el alumnado consume en minutos. Este curso nace de esa realidad: hay herramientas disponibles ahora mismo que reducen drásticamente ese tiempo sin renunciar a la calidad. No hace falta saber de tecnología, solo saber qué quieres conseguir.

---

## A quién va dirigido

A **cualquier docente** de Secundaria, Bachillerato o Formación Profesional que prepare clases, redacte exámenes, adapte materiales o lleve tiempo buscando cómo mejorar sin que eso suponga más horas frente al ordenador.

No se necesitan conocimientos previos de informática.

---

## Qué se va a aprender

- Entender cómo funcionan los asistentes de IA y qué limitaciones tienen.
- Formular instrucciones eficaces para obtener resultados útiles (*prompting*).
- Generar y adaptar materiales didácticos: explicaciones, actividades y textos para distintos niveles.
- Crear instrumentos de evaluación: rúbricas, baterías de preguntas y pruebas escritas.
- Usar NotebookLM para trabajar exclusivamente con el temario propio, sin riesgo de alucinaciones.
- Convertir textos en esquemas visuales con Napkin y crear recursos interactivos con PartyRock.
- Redactar apuntes en Markdown y publicarlos como página web con Google Antigravity y GitHub Pages.


---

## Organización del Curso

!!! abstract "Distribución de sesiones (40 horas)"
    ```mermaid
    flowchart LR
      M1([M1: Fundamentos\nde IA y Prompting]) --> M2([M2: Materiales\nDidácticos con IA])
      M2 --> M3([M3: Evaluación\ny Rúbricas])
      M3 --> M4([M4: NotebookLM])
      M4 --> M5([M5: Visualización\ne Interactividad])
      M5 --> M6([M6: Markdown,\nAntigravity y Pages])
      M6 --> M7([M7: Práctica\nIntegradora])
    ```

---

### Módulo 1. Fundamentos de IA y Prompting (5 h)

Antes de usar cualquier herramienta, conviene entender qué hace realmente un asistente de IA y qué no hace. Este módulo sienta las bases para trabajar con la IA de forma productiva y sin llevarse sorpresas.

**Contenidos:**

- Qué es un modelo de lenguaje y cómo genera respuestas (sin tecnicismos).
- Diferencias prácticas entre **Gemini**, **ChatGPT** y otros asistentes: cuándo usar cada uno.
- Cómo funciona el *prompting*: la instrucción que se da a la IA determina el resultado.
- Estructura de un buen prompt: contexto, tarea, formato y restricciones.
- Limitaciones reales: alucinaciones, sesgos y fechas de corte de conocimiento.

📝 **Ejemplo de práctica:** Comparar los resultados obtenidos con el mismo objetivo pero instrucciones distintas, y refinar la instrucción hasta obtener una respuesta útil.

---

### Módulo 2. Generación de Materiales Didácticos con IA (6 h)

Uso de asistentes de IA para reducir el tiempo de preparación de contenidos: temario, explicaciones, textos adaptados y actividades.

**Contenidos:**

- Generar una explicación de un concepto para distintos niveles educativos.
- Adaptar un texto de Bachillerato a 1º de ESO o para una adaptación curricular significativa.
- Elaborar una secuencia de actividades para una unidad didáctica.
- Solicitar variantes de un mismo ejercicio con distinto nivel de dificultad.
- Revisar y corregir redacciones del alumnado con retroalimentación detallada.

📝 **Ejemplo de práctica:** Generar con IA una explicación de un concepto de la propia asignatura en tres niveles de dificultad distintos y evaluar cuál es más útil en cada caso.

---

### Módulo 3. Evaluación y Rúbricas con IA (5 h)

La IA puede acelerar significativamente la creación de instrumentos de evaluación. Este módulo trabaja con los tipos de demanda más habituales en el aula.

**Contenidos:**

- Generar rúbricas analíticas con criterios alineados a la LOMLOE.
- Crear baterías de preguntas tipo test, de desarrollo o de caso práctico.
- Producir una prueba escrita completa a partir de los objetivos de una unidad.
- Usar la IA para generar plantillas de corrección o parrillas de observación.
- Revisar con IA si una prueba está equilibrada en dificultad y competencias evaluadas.

📝 **Ejemplo de práctica:** Generar la rúbrica de evaluación de una tarea real de la propia asignatura y comparar el resultado con la que el docente usa actualmente.

---

### Módulo 4. NotebookLM: Trabajar con los Propios Documentos (6 h)

**Google NotebookLM** funciona de manera diferente a ChatGPT o Gemini: no genera contenido desde su conocimiento general, sino que trabaja exclusivamente con los documentos que el usuario le proporciona. Esto lo hace especialmente útil en entornos educativos, donde el temario está definido.

**Contenidos:**

- Qué es NotebookLM y en qué se diferencia de otros asistentes.
- Subir apuntes, libros de texto, normativas o programaciones didácticas.
- Generar guías de estudio, resúmenes y esquemas basados únicamente en el material cargado.
- Crear un banco de preguntas de examen derivado del temario propio.
- Generar un *podcast* de introducción a una unidad para que el alumnado escuche antes de clase.
- Limitaciones: el sistema no funciona con documentos protegidos o escaneados sin OCR.

📝 **Ejemplo de práctica:** Cargar los apuntes del siguiente tema que se va a impartir y obtener una guía de estudio y un banco de preguntas listo para usar.

---

### Módulo 5. Visualización e Interactividad (6 h)

Este módulo agrupa dos herramientas de naturaleza diferente pero complementarias: **Napkin** para convertir texto en esquemas visuales, y **Amazon PartyRock** para crear pequeños recursos interactivos sin programar.

**Napkin — Esquemas y visualizaciones (2 h)**

- Cómo funciona: se pega un texto y la herramienta propone distintos tipos de visualización (esquema, mapa, línea de tiempo, diagrama, etc.).
- Ajustar y exportar el resultado para proyectarlo en clase o incluirlo en apuntes.

**Amazon PartyRock — Recursos interactivos (4 h)**

- Qué es PartyRock y cómo se diferencia de un simple chatbot.
- Crear una aplicación con bloques visuales: asistente de preguntas, corrector de textos, quiz con explicaciones.
- Publicar el recurso y compartir el enlace con el alumnado.
- Casos de uso: simulador de conversación para idiomas, asistente de repaso, generador de ejercicios aleatorios.

📝 **Ejemplo de práctica:** Transformar un texto de apuntes en un esquema visual con Napkin, y crear con PartyRock un recurso sencillo para el alumnado de la propia asignatura.

---

### Módulo 6. Publicar Apuntes en la Web: Markdown, Google Antigravity y GitHub Pages (6 h)

Este módulo introduce un flujo de trabajo para que el docente pueda publicar sus apuntes como una página web, accesible desde cualquier dispositivo y siempre actualizada, sin necesidad de saber programar ni gestionar servidores.

La cadena es sencilla: se escribe en **Markdown**, se gestiona con **Google Antigravity** y se publica con **GitHub Pages**.

**Markdown — Escribir sin procesar de texto (1 h)**

Markdown es un sistema de formato en texto plano que se aprende en minutos:

| Lo que escribes | Lo que se ve |
|---|---|
| `# Título` | Encabezado grande |
| `**negrita**` | **negrita** |
| `- elemento` | • elemento de lista |
| `[texto](url)` | [enlace](url) |

- Crear un documento con títulos, listas, tablas y bloques de código.
- Previsualizar el resultado en tiempo real.

**Google Antigravity — Redactar y organizar en la nube (2 h)**

- Qué es Antigravity y para qué sirve en un contexto docente.
- Crear y editar documentos Markdown directamente en el navegador.
- Organizar una colección de apuntes por temas o unidades didácticas.
- Usar la IA integrada para refinar el texto o generar contenido de apoyo.

**GitHub Pages — Publicar la web (3 h)**

- Qué es GitHub y qué es un repositorio (explicación sin tecnicismos).
- Subir los apuntes a un repositorio y activar GitHub Pages con un clic.
- El resultado: una URL propia con los apuntes publicados, sin coste y sin publicidad.
- Actualizar el contenido: cada cambio se refleja automáticamente en la web.
- Compartir el enlace con el alumnado en lugar de enviar archivos por correo.

📝 **Ejemplo de práctica:** Publicar una unidad didáctica propia como página web y compartir el enlace con el resto del grupo.

---

### Módulo 7. Práctica Integradora (6 h)

Cada participante prepara, con las herramientas vistas en el curso, los materiales de una clase real. El objetivo es salir del módulo con algo concreto ya hecho.

**Estructura de la sesión:**

- Tiempo de trabajo individual con apoyo del formador.
- Puesta en común: cada docente muestra qué ha generado y cómo lo usaría.
- Reflexión sobre qué herramienta resulta más útil según la asignatura y la etapa.

📝 **Ejemplo de práctica:** Preparar para una unidad concreta: una explicación adaptada, una rúbrica de evaluación, un esquema visual y, opcionalmente, los apuntes publicados en la web.
