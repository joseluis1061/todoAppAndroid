# todoAppAndroid
# 📋 ToDoListAndroid

Este es un proyecto de ejemplo para una aplicación de lista de tareas ("To-Do List") nativa para Android, desarrollada con **Jetpack Compose**.

La aplicación permite a los usuarios:

- Crear nuevas tareas
- Marcar tareas como completadas
- Eliminar tareas de la lista

---

## 💻 Tecnologías Utilizadas

- **Kotlin** → Lenguaje principal
- **Jetpack Compose** → UI declarativa moderna
- **Jetpack Datastore** → Almacenamiento de datos persistente
- **Coroutines** → Manejo de operaciones asíncronas
- **AndroidX Libraries** → Librerías base para Android

---

## 🚀 Cómo Empezar

Clona el repositorio:


https://github.com/joseluis1061/todoAppAndroid.git

1. Abrir en Android Studio

2. Sincronizar Gradle

3. Ejecutar en un emulador o dispositivo físico

## 📚 Taller de Desarrollo

A continuación se incluyen preguntas y respuestas que resumen las consideraciones y buenas prácticas aplicadas en este proyecto.

🔹 Requerimientos y Entorno

- Pregunta: ¿Qué se debe estudiar antes de comenzar?
- Respuesta: Es importante repasar los conceptos del componente formativo, conocer los requerimientos del sistema operativo Android, entender el funcionamiento de Android Studio y su SDK, y asegurar que el entorno de desarrollo esté correctamente configurado.

🔹 Diseño y Diagramas

- Pregunta: ¿Qué diagramas se deben conocer?
- Respuesta:

- Diagrama de clases: Define la estructura de datos (por ejemplo, la clase Task con sus atributos y métodos).

- Diagrama de paquetes: Organiza los módulos en paquetes con nombres significativos (UI, modelos, lógica, persistencia).

- Diagrama de componentes: Representa cómo interactúan las capas de la aplicación (interfaz, lógica de negocio y almacenamiento).

🔹 Arquitectura y Capas

- Pregunta: ¿Cómo se dividen los componentes en capas?

- Respuesta:

- Capa de Presentación: Jetpack Compose para la interfaz.

- Capa de Lógica: Gestión de tareas con clases como TaskManager.

- Capa de Datos: Persistencia con Jetpack Datastore.

🔹 Metodología de Desarrollo

- Pregunta: ¿Qué metodología se aplicó?
- Respuesta: Se siguió una metodología iterativa e incremental, aplicando patrones de diseño como MVC/MVVM, y documentando el mapa de navegación de la aplicación (pantalla principal con creación, visualización y edición de tareas).

🔹 Codificación y Librerías

- Pregunta: ¿Qué consideraciones se tuvieron al codificar?
- Respuesta:

- Se desarrollaron los módulos en Kotlin siguiendo buenas prácticas.

- Se usó Git como sistema de control de versiones.

- Se seleccionaron librerías necesarias para la capa de presentación (Compose, Material Design).

- Los módulos fueron divididos en componentes reutilizables (por ejemplo, cada tarea en la lista).

🔹 Buenas Prácticas

- Pregunta: ¿Cómo se organizó el código fuente?
- Respuesta:

- Código dividido en paquetes con nombres descriptivos (ui/, model/, data/).

- Uso de patrones de diseño acordes a la arquitectura.

- Separación clara entre vista, lógica y datos.

- Reutilización de componentes (layouts, adaptadores).

🔹 Pruebas y Documentación

- Pregunta: ¿Qué pasos se siguieron para garantizar calidad?
- Respuesta:

- Pruebas unitarias en cada módulo.

- Documentación de configuraciones de desarrollo y pruebas.

- Uso de logs y validaciones en cada acción del usuario.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Puedes abrir un issue o un pull request.

## 📝 Licencia

Este proyecto está bajo la Licencia MIT.

