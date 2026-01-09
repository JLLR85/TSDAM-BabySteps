# 👶 BabySteps: Guía y Diario para Padres Primerizos

**BabySteps** es una aplicación diseñada para apoyar a padres durante los primeros 18 meses de crianza. Combina una guía informativa de hitos del desarrollo con un diario práctico de registros diarios. Este proyecto nace de una motivación personal basada en mi propia experiencia como padre.

## 🎯 1. Objetivo del Proyecto
El objetivo es servir de apoyo real en la crianza. La app permite:
* Consultar **18 hitos del desarrollo** (pedagogía infantil).
* Gestionar un **Diario de cuidados**: registros de alimentación, ciclos de sueño, pañales y medicación.

## 🛠️ 2. Prerrequisitos y Tecnologías
Para ejecutar o visualizar el código de este proyecto se requiere:
* **Lenguaje:** Dart
* **Framework:** Flutter (SDK versión 3.0 o superior).
* **Entorno:** Zapp.run, DartPad, Visual Studio Code o Android Studio.
* **Librerías:** `intl` (para la gestión de formatos de fecha y hora).

## ⚙️ 3. Pasos para la instalación
Si deseas ejecutar el proyecto de forma local, sigue estos pasos:
1.  **Clonar o descargar** el repositorio.
2.  Abrir la carpeta en tu entorno de desarrollo.
3.  Ejecutar `flutter pub get` en la terminal para descargar las dependencias.
4.  Lanzar la aplicación con `flutter run`.

## 🧠 4. Detalles Técnicos (Arquitectura)
* **Gestión de Estado:** Implementación mediante `StatefulWidgets` y `StatefulBuilder` para actualizaciones reactivas de la interfaz.
* **UX/UI:** Diseño basado en **Material Design 3**, utilizando iconos cromáticos para identificar rápidamente las categorías de cuidado (alimentación, sueño, salud).
* **Rendimiento:** Uso de `ListView.builder` para optimizar el consumo de memoria en dispositivos móviles.

## ❤️ 5. Agradecimientos
Agradezco a mi familia por ser la fuente de inspiración diaria. Un agradecimiento especial a mi tutor **Abelardo**; aunque no pude asistir a las sesiones en vivo, sus clases grabadas han sido la guía fundamental para sacar adelante este proyecto. ¡Gracias por los consejos!
