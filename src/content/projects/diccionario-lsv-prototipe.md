---
title: "Prototipo Diccionario de Lengua de Señas Venezolana (1.0.0v) "
description: "Prototipo de Diccionario LSV móvil con Flutter/Dart. Aplicación interactiva que usa un modelo 3D animado para señas. Datos organizados con SQLite."
image: "../../assets/lsv-proto.jpg"
startDate: "2024-11-01T12:00:00" 
endDate: "2025-06-01T12:00:00"
skills: ["Flutter", "Dart", "SQLite", "MVVM", "Mobile-First"]
sourceLink: "https://github.com/danielguarimatadev/Diccionario-LSV"
---

## Sobre el Diccionario LSV

El Diccionario LSV es una aplicación móvil inclusiva y educativa desarrollada para facilitar el aprendizaje visual de la **Lengua de Señas Venezolana (LSV)**. Fue diseñado con la filosofía **Mobile-First**, priorizando una interfaz accesible, modular y escalable. Su objetivo es servir como puente de comunicación para usuarios sordos, oyentes en proceso de inclusión y comunidades educativas.

## Funcionalidades Clave y Diferenciador

### Experiencia de Visualización Única (Modelo 3D)
- **Animaciones 3D de Señas**: El principal diferenciador. Cada palabra es animada por un **modelo 3D** que ejecuta la seña correspondiente, ofreciendo una experiencia de aprendizaje inmersiva y precisa.
- **Búsqueda y Filtrado**: Funcionalidad de búsqueda en tiempo real sobre el vocabulario.
- **Visualización por Categorías**: Navegación de palabras organizadas por categorías temáticas, facilitando el estudio enfocado.

### Gestión Robusta de Datos
- **Base de Datos SQLite**: Uso de SQLite para el almacenamiento local del vocabulario en texto y sus categorías, garantizando acceso instantáneo y funcionalidad **offline**.
- **Gestión de Recursos Multimedia**: Estructura optimizada para manejar y cargar eficientemente los modelos 3D y/o videos de alta calidad asociados a cada seña.

## Arquitectura Técnica

### Stack Frontend Móvil
El desarrollo en Flutter asegura rendimiento nativo y código de alta calidad:
- **Flutter / Dart**: Framework principal para el desarrollo móvil multiplataforma.
- **Arquitectura MVVM**: Implementación rigurosa del patrón **Model-View-ViewModel** para una separación clara de la lógica de negocio y la interfaz de usuario, garantizando código limpio y testable. 
- **Manejo de Estado**: Uso de un sistema de gestión de estado reactivo (como Riverpod o Provider, según tu implementación) para la sincronización fluida de la UI con los datos.

## Experiencia de Usuario

- **Diseño Mobile-First**: UI/UX limpio y centrado en la usabilidad en pantallas pequeñas.
- **Optimización de Rendimiento**: Estrategias de manejo de recursos para asegurar una baja latencia en la carga de animaciones 3D.
- **Accesibilidad**: Diseño enfocado en la claridad visual y la navegación intuitiva, crucial para una herramienta inclusiva.

## Propósito e Impacto

El Diccionario LSV no es solo una aplicación, sino un proyecto con un fuerte impacto social:
- **Promoción de la Inclusión**: Sirve como una herramienta educativa vital para cerrar la brecha comunicacional.
- **Demostración Técnica**: Muestra la capacidad de implementar tecnologías avanzadas (animación 3D) en un entorno móvil y de construir soluciones mantenibles bajo principios de arquitectura sólida (**MVVM**).
- **Aprendizaje Interactivo**: Ofrece una vía moderna y atractiva para el aprendizaje de la Lengua de Señas.