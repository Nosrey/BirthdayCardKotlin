# HappyBirthday Android App

Este proyecto es una aplicación de Android desarrollada en Kotlin utilizando Jetpack Compose. La aplicación muestra un mensaje de felicitación de cumpleaños en la pantalla.

## Características

- La aplicación muestra una imagen y un mensaje de felicitación.
- El mensaje de felicitación incluye el texto del mensaje y el nombre del remitente.
- La aplicación utiliza Jetpack Compose para la interfaz de usuario.

## Código

El punto de entrada de la aplicación es la clase `MainActivity`. En el método `onCreate`, se establece la interfaz de usuario para esta actividad utilizando el método `setContent`. Dentro de `setContent`, se aplica el `HappyBirthdayTheme`, que es un tema personalizado para la aplicación. La interfaz de usuario está envuelta dentro de un `Surface`, que es un bloque de construcción fundamental para el diseño de la interfaz de usuario en Jetpack Compose.

La función `GreetingImage` es una función componible que muestra una imagen y un texto de saludo. Utiliza un diseño `Box` para apilar a sus hijos. El composable `Image` se utiliza para mostrar una imagen, y el composable `GreetingText` se utiliza para mostrar el mensaje de saludo.

La función `GreetingText` es otra función componible que muestra el mensaje de saludo y el nombre del remitente. Utiliza un diseño `Column` para organizar a sus hijos verticalmente. El composable `Text` se utiliza para mostrar el texto.

Finalmente, la función `BirthdayCardPreview` es una función de vista previa que permite ver cómo se ven tus funciones componibles en la vista previa de Android Studio.

## Requisitos

- Android Studio Arctic Fox | 2020.3.1 Patch 2 o superior.
- Kotlin 1.5.10 o superior.
- Gradle 7.0.2 o superior.

## Cómo ejecutar

1. Clona este repositorio.
2. Abre el proyecto en Android Studio.
3. Ejecuta la aplicación en un emulador o dispositivo Android.

## Licencia

Este proyecto está bajo la licencia MIT.