# Introducción a la Programación en Python para FP y Bachillerato

!!! note ""
    Las actividades del curso se plantean con ejemplos relacionados con el contexto profesional de los ciclos formativos.

---

## A quién va dirigido

A **profesores de informática** de Bachillerato, Ciclos Formativos de Grado Medio (SMR) o Superior (ASIR, DAW, DAM) que quieran actualizar su manera de enseñar a programar o que necesiten ponerse al día con Python antes de impartirlo en clase.

---

## Qué se va a aprender

- Conocer la sintaxis de Python desde cero, de forma progresiva.
- Controlar el flujo de un programa con condicionales y bucles.
- Estructurar el código con funciones y manejar colecciones de datos.
- Leer y escribir ficheros, capturar errores y operar con el sistema de archivos.
- Desarrollar un proyecto final aplicado directamente al temario del ciclo.

---

## Organización del Curso

!!! abstract "Distribución de sesiones (40 horas)"
    ```mermaid
    flowchart LR
      M1([M1: Variables\ny Tipos]) --> M2([M2: Condicionales])
      M2 --> M3([M3: Bucles])
      M3 --> M4([M4: Listas y\nDiccionarios])
      M4 --> M5([M5: Funciones])
      M5 --> M6([M6: Ficheros y\nExcepciones])
      M6 --> M7([M7: Práctica\nIntegradora])
    ```

---

### Módulo 1. Variables, Tipos y Entrada de Datos (5 h)

Configuración del entorno de trabajo. Tipos de datos básicos (`int`, `float`, `str`, `bool`), variables, operadores y cómo recibir datos del usuario por consola con `input()`.

📝 **Ejemplo de práctica:** Un programa que pida nombre, nota numérica y dirección IP, y muestre un resumen formateado por pantalla.

---

### Módulo 2. Condicionales (5 h)

Cómo hacer que un programa tome decisiones en función de los datos que recibe.

- Sentencias `if`, `elif`, `else`.
- Operadores de comparación y lógicos (`and`, `or`, `not`).
- Condiciones anidadas y casos límite.

📝 **Ejemplo de práctica:** Un programa que clasifique una nota numérica en su calificación textual (Insuficiente, Suficiente, Bien, Notable, Sobresaliente) y avise si el valor introducido no es válido.

---

### Módulo 3. Bucles y Control de Flujo (6 h)

Cómo repetir acciones y controlar cuándo detenerlas.

- Bucle `for` con `range()` y sobre colecciones.
- Bucle `while` para condiciones indeterminadas.
- `break`, `continue` y `else` en bucles.

📝 **Ejemplo de práctica:** Un programa que simule un sistema de acceso con intentos limitados: bloquea el acceso tras tres contraseñas incorrectas y registra los intentos fallidos.

---

### Módulo 4. Listas y Diccionarios (6 h)

Cómo almacenar y organizar conjuntos de datos.

- Listas: creación, indexación, métodos (`append`, `remove`, `sort`...).
- Diccionarios: claves y valores, cuándo usar cada estructura.
- Recorrido e iteración sobre colecciones.

📝 **Ejemplo de práctica:** Un programa que gestione una lista de equipos de red, cada uno con nombre, IP y estado, y permita añadir, buscar y listar registros.

---

### Módulo 5. Funciones (5 h)

Cómo dividir el código en unidades reutilizables y manejables.

- Definición con `def`, parámetros y valores de retorno.
- Alcance de variables (local vs. global).
- Funciones con valores por defecto y argumentos keyword.

📝 **Ejemplo de práctica:** Refactorizar el programa del módulo anterior para que cada operación (añadir, buscar, listar) sea una función independiente.

---

### Módulo 6. Ficheros, Excepciones y Sistema (6 h)

Python interactuando con el sistema operativo y los datos persistentes.

- Lectura y escritura de ficheros `.txt` y `.csv` con `open()`.
- Gestión de errores con `try` / `except` / `finally`.
- Librería `os`: listar directorios, comprobar rutas, obtener metadatos de ficheros.

📝 **Ejemplo de práctica:** Un script que recorra una carpeta del sistema y genere un informe `.csv` con el nombre, extensión, tamaño y fecha de modificación de cada archivo encontrado.

---

### Módulo 7. Práctica Integradora (7 h)

Cada participante desarrolla un programa propio que combine los contenidos del curso y sea aplicable a su contexto de aula.

📝 **Práctica:** Propuesta libre o elegida de entre las siguientes ideas:

!!! example "Ideas de proyecto"
    - **Calculadora de subredes:** a partir de una IP y máscara CIDR, calcula red, broadcast, rango de hosts y número de dispositivos.
    - **Generador de contraseñas aleatorias** con criterios configurables (longitud, caracteres especiales, mayúsculas).
    - **Corrector de notas por CSV:** lee un fichero de calificaciones, calcula la media y genera un informe con aprobados y suspensos.
    - **Inventario de aula:** gestiona por consola una lista de equipos con nombre, IP y estado, guardando los cambios en fichero.
    - **Propuesta libre:** cualquier herramienta que el docente considere útil para su asignatura o su gestión diaria.


