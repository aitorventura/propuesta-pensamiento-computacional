# Propuesta de Formación: Python con Metacognición Aplicada

!!! quote "Idea"
    Aprender a programar es aprender a pensar. Esta formación combina la asimilación de conceptos técnicos básicos de Python con rutinas explícitas de planificación, resolución de problemas y depuración.

## 👥 Destinatarios y Contexto

La presente propuesta formativa está diseñada de forma específica para el **profesorado que imparte módulos de introducción a la programación en Ciclos Formativos de Grado Medio o materias de informática y tecnología en Bachillerato**. 

La intención es dotar a los equipos docentes, que habitualmente enfrentan el reto de enseñar a programar desde cero, de una metodología basada en la metacognición. De este modo, además de asentar conocimientos técnicos sólidos en Python, se adquieren estrategias didácticas para ayudar al alumnado a gestionar la frustración frente a la pantalla, organizar el razonamiento lógico y alcanzar mayor autonomía a la hora de detectar fallos.

## 🎯 Objetivos de la formación

- **Asentar** una base técnica en Python orientada a la lectura de código y la resolución estructurada de problemas.
- **Aplicar** hábitos metacognitivos a la programación: anticipar resultados, justificar decisiones de diseño, comprobar el funcionamiento paso a paso y revisar la estructura final.
- **Tratar el error** como parte esencial y normalizada del aprendizaje, estableciendo pautas de depuración sistemática para evitar el "ensayo y error" sin sentido.
- **Construir** materiales o secuencias didácticas transferibles directamente al aula de Formación Profesional o Bachillerato, integrando el pensamiento computacional con la reflexión.

## 🛠️ Organización de los Contenidos

El desarrollo se articula en seis bloques de contenido temático. En cada uno de ellos se introducen progresivamente estructuras técnicas de Python, siempre vinculadas a una estrategia orientada a pensar sobre cómo se programa.

!!! abstract "Itinerario Metacognitivo"

    ```mermaid
    flowchart TD
      M1["`**1.** Planificación previa`"] --> M2["`**2.** Predicción de resultados`"]
      M2 --> M3["`**3.** Monitorización del proceso`"]
      M3 --> M4["`**4.** Descomposición de problemas`"]
      M4 --> M5["`**5.** Depuración sistemática`"]
      M5 --> M6["`**6.** Diseño para el aula`"]
    ```

A continuación, se detalla el trabajo específico a realizar en cada módulo:

### Módulo 1. Pensar antes de escribir
- **Contenido técnico:** Configuración ágil del entorno (uso de IDEs básicos orientados a educación). Exploración de la sintaxis fundamental sintaxis de Python: introducción de datos (`input()`), salida por consola (`print()`), declaración de variables y familiarización con tipos de datos.
- **Foco metacognitivo:** Rutinas de planificación. Antes de teclear código, el participante aprenderá a usar plantillas de planificación (el "qué sé, qué me piden, qué datos necesito") para estructurar los pasos lógicos, mitigando el bloqueo del "lienzo en blanco".
- **Práctica propuesta:** Diseñar una calculadora interactiva guiada. La evaluación no se centrará solo en el código final, sino de la entrega de un esquema en lenguaje natural delineando la secuencia de pasos.

### Módulo 2. Tomar decisiones informadas
- **Contenido técnico:** Operadores relacionales (`==`, `<`, `!=`) y lógicos (`and`, `or`). Introducción al control de flujo con estructuras condicionales simples y anidadas (`if`, `elif`, `else`).
- **Foco metacognitivo:** La **predicción**. Se requerirá describir con precisión qué hará un fragmento de código *antes* de ejecutarlo, comparando la hipótesis inicial con el resultado provisto por el ordenador.
- **Práctica propuesta:** Construcción de un "árbol de decisiones" interactivo (por ejemplo, un selector ficticio de módulos de FP). El docente documentará todos los posibles caminos y comportamientos lógicos como paso previo al desarrollo.

### Módulo 3. Repetir con propósito
- **Contenido técnico:** Automatización mediante iterativas (`for` y `while`). Uso de variables contadoras y acumuladoras para llevar un registro del progreso dentro de un ciclo.
- **Foco metacognitivo:** Monitorización consciente. Utilización de *trazas de ejecución* en papel para probar visualmente la evolución de las variables e identificar razones estructurales de los bucles infinitos.
- **Práctica propuesta:** Desarrollar un programa validador de entradas (por ejemplo, intentos de autenticación limitados), acompañando la entrega con una tabla manual de traza de variables que demuestre cuándo y por qué rompe el bucle.

### Módulo 4. Descomponer problemas
- **Contenido técnico:** Introducción a funciones propias (`def`). Manejo de paso de argumentos, alcance de las variables locales/globales y recuperación de resultados con `return`.
- **Foco metacognitivo:** Descomposición. Metodología para dividir un reto cognitivo grande en partes inabarcables, usando diagramas de bloque que actúen de andamiaje cognitivo.
- **Práctica propuesta:** Refactorización orientada. Se entregará un bloque de código funcional pero caótico; el participante debe reconstruirlo utilizando tres sub-funciones lógicas y adjuntando el diagrama jerárquico que lo precede.

### Módulo 5. Aprender (de verdad) del error
- **Contenido técnico:** Clasificación de fallos nativos de Python (sintaxis, nombres, tipos, índices). Lectura analítica de *Tracebacks* generados por errores de ejecución.
- **Foco metacognitivo:** Depuración sistemática. Abandonar la corrección por "ensayo y error al azar". Promover el hábito: *leer alerta → formular diagnóstico → plantear solución → comprobar*.
- **Práctica propuesta:** El "Hospital de código". El participante recibe scripts deliberadamente "enfermos". Para superarlo, repara el código y extiende un "parte de intervención" exponiendo el origen del fallo y su solución técnica razonada.

### Módulo 6. Transferencia al aula
- **Contenido técnico:** Fusión de las estructuras abordadas (I/O, ramificaciones, ciclos, encapsulación) para elaborar un pequeño script integrado real.
- **Foco metacognitivo:** Transposición docente. Consolidación de un marco reflexivo: *¿Cómo aterrizo esta filosofía de aprendizaje de programación en mi instituto?*
- **Práctica propuesta:** Elaboración del producto final. El docente esbozará una actividad aplicable de 1-2 horas para sus estudiantes que incluya un ejercicio en Python y, de forma imperativa, la aplicación de al menos uno de los recursos metacognitivos vistos durante la formación.

---

## ⚙️ Planteamiento Metodológico

El enfoque metodológico busca ser netamente instrumental y aplicable para el entorno de un docente de secundaria o formación profesional. Se prioriza el desarrollo de actividades tales como:

- **Lectura y comprensión de código:** Analizar programas de corta extensión ya existentes para explicar su finalidad antes de proponer la escritura desde cero.
- **Desarrollo con andamiaje decreciente:** Retos y ejercicios guiados mediante pasos intermedios muy definidos, retirando gradualmente las pistas a medida que avanza la formación.
- **Cuaderno o registro de depuración:** Documentar e identificar los fallos encontrados durante el diseño del código propio, sirviendo también como un posible banco de errores típicos a presentar y debatir posteriormente en el aula física.
