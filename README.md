## 🇻🇪 README: Aplicación de Traducción y Aprendizaje de Lengua de Señas Venezolana (LSV)

### # 🧏🏻‍♀️ LSV App: Conectando a Venezuela

<div align="center">

Una aplicación dedicada a facilitar la comunicación y el aprendizaje de la **Lengua de Señas Venezolana (LSV)**. Nuestro objetivo es reducir la barrera comunicacional, promoviendo la inclusión y el acceso a la información para la comunidad sorda en Venezuela.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Stack](https://img.shields.io/badge/Flutter-Dart-02569B?logo=flutter&logoColor=white)](https://flutter.dev)
[![Backend](https://img.shields.io/badge/Backend-Firebase%20%2F%20Supabase-FFCA28?logo=firebase&logoColor=white)](https://firebase.google.com)
[![Version](https://img.shields.io/badge/Version-1.0.0-green)](https://github.com/danielguarimatadev/lsv-app/releases/tag/v1.0.0)

</br>



</div>

---

## ✨ Características y Funcionalidades

* **Traductor de Texto a Seña:** Permite al usuario introducir texto y visualizar su representación instantánea en LSV.
* **Diccionario LSV:** Acceso rápido y visual a un diccionario completo de señas comunes y específicas de la variante venezolana.
* **Módulos de Aprendizaje:** Aprende cada palabra paso a paso para dominar la LSV, incluyendo el alfabeto dactilológico.
* **Tecnología de Animación 3D:** Integración de animación 3D con la biblioteca **O3D de Flutter** para mayor fluidez y claridad visual de los gestos.
* **Interfaz Inclusiva:** Diseño simple y de alto contraste, optimizado para ser accesible.

---

## 🛠️ Stack Tecnológico

| Componente | Tecnología | Propósito |
| :--- | :--- | :--- |
| **Frontend/App** | **Flutter** | Desarrollo de la aplicación móvil multiplataforma. |
| **Lenguaje** | **Dart** | Lenguaje de programación principal. |
| **Animación 3D** | **O3D (Flutter)** | Renderizado de modelos 3D para la visualización de señas. |
| **Backend / DB** | **Firebase, Supabase** | Servicios de autenticación y base de datos (según configuración). |

---

## 🚀 Ejecución

| Plataforma | Comando | Descripción |
| :--- | :--- | :--- |
| **Móvil (Local)** | `flutter run` | Inicia la aplicación en el dispositivo/emulador conectado. |
| **Android** | `flutter run --release` | Compila y ejecuta la versión de lanzamiento para Android. |
| **iOS** | `flutter run --release` | Compila y ejecuta la versión de lanzamiento para iOS. |

---

## ⚙️ Arquitectura del Proyecto

El proyecto sigue una arquitectura modular enfocada en la separación de responsabilidades para facilitar el mantenimiento y escalabilidad:

* **`lib/src/screens`**: Contiene las vistas principales de la aplicación (Diccionario, Traductor, Lecciones).
* **`lib/src/components`**: Almacena los widgets reutilizables de Flutter.
* **`lib/src/services`**: Maneja la lógica de conexión al backend (Firebase/Supabase) y la gestión de datos.
* **`assets/`**: Aquí se almacenan los recursos estáticos, incluyendo los modelos 3D (`.glb`, `.obj`) utilizados por la biblioteca O3D para la representación de las señas.
* **`pubspec.yaml`**: Define todas las dependencias del proyecto, incluyendo O3D.

---

## 🤝 Contribuciones

Agradecemos mucho cualquier contribución para mejorar y expandir el contenido de la Lengua de Señas Venezolana.

1.  Haz un **Fork** del repositorio.
2.  Crea tu rama de característica (`git checkout -b feature/nueva-seña`).
3.  Comitéa tus cambios (`git commit -m 'feat: Añadir la seña para "Arepa"'`).
4.  Abre un **Pull Request**.

### 🐛 Reportar Errores

Por favor, reporta cualquier error o sugiera una nueva seña para el diccionario en la sección de [Issues](https://github.com/danielguarimatadev/daniel_portafolio/issues).

---

## 📄 Licencia

Este proyecto está bajo la **Licencia MIT**.