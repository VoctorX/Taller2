# 📚 Seguimiento 2: Estructuras de Datos en Python  
## Conjuntos, Diccionarios, Pilas, Colas, **Comprension de Listas** y Listas Anidadas

Este proyecto muestra ejemplos prácticos del uso de **estructuras de datos fundamentales en Python**, incluyendo:

- **Conjuntos (`set`)**: para almacenar elementos únicos y realizar operaciones como pertenencia y eliminación de duplicados.
- **Diccionarios (`dict`)**: para manejar datos estructurados mediante pares clave-valor (ideal para representar objetos como estudiantes).
- **Pilas (`Stack`)**: implementadas con listas, siguiendo el principio **LIFO** (Last In, First Out).
- **Colas (`Queue`)**: implementadas con `collections.deque`, siguiendo el principio **FIFO** (First In, First Out), aplicadas en un sistema realista de gestión de pedidos.
- **List Comprehension**: para creación concisa de listas mediante filtrado y transformación en una sola línea.
- **Listas Anidadas**: para manejo de matrices y estructuras multidimensionales, incluyendo transposición de matrices.

---

## 🧪 Contenido del código

### 1. **Conjuntos**
- Creación de conjuntos a partir de listas y cadenas.
- Verificación rápida de pertenencia (`in`).
- Eliminación automática de duplicados.
- Ejemplo con frutas y operaciones básicas de conjuntos.

### 2. **Diccionarios**
- Representación de estudiantes con atributos como nombre, edad, carrera y notas.
- Modificación y eliminación de claves.
- Verificación de existencia de claves (¡ojo! el ejemplo incluye un error común al verificar claves en una **lista de diccionarios**, no en un solo diccionario).
- Manejo de múltiples estudiantes en una lista de diccionarios.

### 3. **Pilas (Stack)**
- Clase `Pila` completa con métodos:
  - `apilar()`
  - `desapilar()`
  - `ver_tope()`
  - `esta_vacia()`
- Ejemplo práctico: **invertir una palabra** usando una pila (ejemplo: "DATA" → "ATAD").
- Implementación del principio LIFO con operaciones O(1).

### 4. **Colas (Queue)**
- Uso de `collections.deque` para eficiencia.
- Clase `SistemaPedidos` que simula un restaurante:
  - Agregar pedidos (entradas a la cola).
  - Procesar pedidos en orden (salidas desde el frente).
  - Mostrar estado del sistema (pendientes vs. completados).
- Implementación del principio FIFO con gestión de tiempo real.

### 5. **List Comprehension**
- Creación concisa de listas usando sintaxis compacta.
- Filtrado y transformación en una sola línea de código.
- Ejemplo práctico: conversión de temperaturas Celsius a Fahrenheit con filtro.
- Operaciones comunes: filtrado, transformación y combinado.

### 6. **Listas Anidadas**
- Manejo de matrices y estructuras multidimensionales.
- Transposición de matrices usando list comprehension.
- Comparación con el método `zip()` para transposición.
- Aplicaciones en álgebra lineal y manipulación de datos tabulares.

---

## 📽️ Presentación Interactiva Sobre Listas Comprendidas (Mi tema)

Las listas comprendidas se explican en detalle en la siguiente página interactiva con demostraciones en vivo:

👉 **[Aprender sobre Listas Comprendidas en la página interactiva en Netlify](https://listascomprendidas.netlify.app/)**

---

## ⚜️ Presentación Interactiva sobre todas las listas

Aprende mas sobre las listas vistas en clase en la siguiente página interactiva con demostraciones en vivo:

➡️ **[Aprender de forma divertida mas sobre las todas las listas vistas en clase](https://voctorx.github.io/Taller2/)**

---

## 💾 Repositorio

Este código forma parte del repositorio oficial del proyecto:

🔗 **[github.com/VoctorX/Taller2](https://github.com/VoctorX/Taller2)**

### 🛠️ Cómo clonar el repositorio

Para obtener una copia local del proyecto, ejecuta en tu terminal:

```bash
git clone https://github.com/VoctorX/Taller2.git
```

### 📁 Estructura del proyecto

```
Taller2/
├── README.md
├── compañerosListas.ipynb     # Cuaderno de Jupyter con todos los ejemplos
├── index.html                 # Página web interactiva con demostraciones sobre TODAS las listas
└── Compresión de Listas en Python - Victor y Gabriel.pdf # Presentacion sobre la comprension de Listas, por Victor y Grabiel
```

### 🚀 Cómo ejecutar el proyecto

#### Opción 1: Usar Jupyter Notebook (Recomendado)
1. Asegúrate de tener Jupyter instalado:
   ```bash
   pip install jupyter
   ```
2. Inicia Jupyter:
   ```bash
   jupyter notebook
   ```
3. Abre el archivo `compañerosListas.ipynb`

#### Opción 2: Ver la página interactiva
1. Visita: [https://voctorx.github.io/Taller2/](https://voctorx.github.io/Taller2/)
2. Explora las 6 estructuras de datos con demostraciones interactivas

### 📋 Requisitos técnicos

- **Python 3.x** (cualquier versión reciente)
- **Jupyter Notebook** (opcional, para ejecutar el .ipynb)
- **Módulos estándar de Python**:
  - `collections` (para deque)
  - `time` (para el sistema de pedidos)
  - `copy` (para operaciones avanzadas)

No se requieren librerías externas adicionales.

---

## 🎯 Características del proyecto

- ✅ **Código funcional**: Todos los ejemplos son ejecutables y están completamente probados
- ✅ **Documentación completa**: Explicaciones detalladas y comentarios en el código
- ✅ **Diseño interactivo**: Página web con demostraciones en vivo para cada estructura
- ✅ **Ejemplos prácticos**: Aplicaciones reales como sistema de pedidos y procesamiento de datos
- ✅ **Múltiples formatos**: Notebook interactivo, página web y archivos Python individuales
- ✅ **Sin dependencias**: Usa solo módulos estándar de Python

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - consulta el archivo [LICENSE](LICENSE) para más detalles.

---

## Construido con 🛠️

_Herramientas y lenguajes utilizados en los proyectos de este repositorio:_

* [Git](https://git-scm.com/) - Control de versiones ![GitHub](https://img.shields.io/badge/GitHub-actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
* [Visual Studio Code](https://code.visualstudio.com/) - Editor de código
* [Python](https://www.python.org/) - Lenguaje de programación ![Python](https://img.shields.io/badge/Python-3.13-3776AB?style=for-the-badge&logo=python&logoColor=white)s

---

## 👨‍💻 Autor
**Victor Cordoba** - *Creador y desarrollador principal* - [VoctorX](https://github.com/VoctorX)

Creado por **Victor Cordoba (VoctorX)** como parte de la actividad de **Seguimiento 2** del curso de **Lenguajes de Programación**.

- **GitHub**: [VoctorX](https://github.com/VoctorX)
- **Página de la exposicion**: [listascomprendidas.netlify.app](https://listascomprendidas.netlify.app/)
- **Página del proyecto (todas las listas)**: [https://voctorx.github.io/Taller2/](https://voctorx.github.io/Taller2/)
- **Repositorio**: [Taller2](https://github.com/VoctorX/Taller2)

---


## Apoyame 🎁

* Comenta a otros sobre este proyecto 📢
* Da las gracias públicamente 🤓.
* Dona con cripto a esta dirección: `0x95d80d2e959099458EDCfd3E14391A44F532177a`
* Dona con Paypal: [![Donar con PayPal](https://img.shields.io/badge/Donar%20con-PayPal-00457C?logo=paypal&logoColor=white)](https://www.paypal.com/donate/?business=cordobavictorml@gmail.com&no_recurring=0&currency_code=USD) 

---

## 🙏 Agradecimientos

- Al profesor del curso de Lenguajes de Programación por las guías y recursos proporcionados
- A la comunidad de Python por la documentación y ejemplos de referencia
- A los compañeros de clase por su colaboración y retroalimentación

---

**Nota**: Este proyecto fue creado con fines educativos como parte de la actividad de **Seguimiento 2** del curso de **Lenguajes de Programación**.



