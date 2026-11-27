# MyBookshelf

![Kotlin](https://img.shields.io/badge/Kotlin-2.x-7F52FF?logo=kotlin&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-Material3-4285F4?logo=jetpackcompose&logoColor=white)
![Min SDK](https://img.shields.io/badge/minSdk-24-green)

**MyBookshelf** es un proyecto básico de **Android Studio** que muestra un uso ejemplar de los conocimientos que voy 
adquiriendo en el curso de **Desarrollo de Aplicaciones Multiplataforma** (*DAM*) en el módulo de **desarrollo de aplicaciones 
móviles**.

## ✨ Características
- Pantalla de **login** (`LoginScreen.kt`)
- Pantalla de **inicio** (`HomeScreen.kt`)
- Uso de la **navegación** (`NavigationWrapper.kt`)
- Aplicación de **State Hoisting** (*elevación de estado*)
- Aplicación de **UI decomposition**
> Esta lista irá creciendo a medida que avance el curso.

## 📋 Requisitos
- Android Studio Quail 3 o superior
- JDK 25 (*Gradle lo usa para compilar el proyecto*)
- Android 7.0 (*API 24*) o superior

## 🛠️ Tecnologías
- Kotlin
- Jetpack Compose + Material 3
- Navigation 3

## 📁 Estructura
```
app/src/main/java/com/example/mybookshelf/
├── MainActivity.kt            # Punto de entrada de la app
├── navigation/
│   ├── NavigationWrapper.kt   # Navegación y back stack
│   └── Routes.kt              # Definición de rutas
├── screens/
│   ├── HomeScreen.kt          # Pantalla principal
│   └── login/
│       ├── LoginScreen.kt     # Pantalla de login
│       └── LoginBody.kt       # Contenido del formulario de login
└── ui/
    └── theme/                 # Color.kt, Theme.kt, Type.kt (tema Material 3)
```

## 👤 Autor
Pol Fernández: [GitHub](https://github.com/Pol19x)
