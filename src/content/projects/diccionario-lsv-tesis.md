---
title: "Diccionario de Lengua de Señas Venezolana (2.0.0v) "
description: "Diccionario LSV móvil con Flutter/Dart. Usa modelo 3D animado. Gestión de datos con SQLite y persistencia (login/almacenamiento) en Firebase/Supabase. Incluye apartados de Práctica y Aprender."
image: "../../assets/lsv-tesis.jpeg"
startDate: "2025-06-02"
skills: ["Flutter", "Dart", "SQLite", "Supabase", "Firebase", "MVVM", "Mobile-First"]
demoLink: "https://youtu.be/M25SvkihnaQ"
---

## Arquitectura del Proyecto (2.0.0v)

El Diccionario LSV es una aplicación móvil avanzada enfocada en la inclusión y la educación, construida sobre una arquitectura de datos robusta y un front-end de alto rendimiento.

### Repository Stats

[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white)](https://dart.dev)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black)](https://firebase.google.com)
[![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=black)](https://supabase.io)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat)](LICENSE)

### Core Technologies

- **Frontend Framework**: **Flutter (v2.x)** con Dart. Garantiza una experiencia nativa en iOS y Android a partir de una única base de código.
- **State Management**: Implementación de una arquitectura de gestión de estado avanzada (ej. Provider/BLoC) para la segregación de responsabilidades y la reactividad de la interfaz.
- **Visualización 3D**: Uso de librerías para renderizar un **modelo 3D animado** que simula con precisión la Lengua de Señas Venezolana (LSV), añadiendo un componente de accesibilidad y aprendizaje clave.

### Persistencia y Gestión de Datos

La gestión de datos se diseñó bajo un modelo híbrido para optimizar el rendimiento y la escalabilidad:

1.  **Almacenamiento Local (SQLite):** Utilizado para la base de datos principal del vocabulario LSV, asegurando acceso instantáneo y funcionalidad **offline** sin dependencia de la red.
2.  **Servicios Backend (Firebase & Supabase):** Implementación de ambos servicios para gestionar la **persistencia en la nube**.
    * **Login y Autenticación de Usuarios:** Controlado por estos servicios, permitiendo perfiles personalizados.
    * **Almacenamiento de Datos:** Utilizado para el seguimiento del progreso del usuario en los módulos de Práctica y Aprender.

### Componente Académico y Educativo

El diseño curricular está integrado directamente en la aplicación a través de dos módulos clave:

- **Módulo 'Aprender':** Ofrece lecciones estructuradas y progresivas que facilitan la adquisición sistemática del vocabulario y la gramática LSV.
- **Módulo 'Práctica':** Incluye ejercicios interactivos y evaluaciones periódicas para reforzar el dominio del contenido, registrando el progreso y los resultados en el perfil de usuario.
