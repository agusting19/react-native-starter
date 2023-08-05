# React Native Expo Starter

En este repositorio puedes encontrar una aplicación React Native Expo creada con TypeScript. La aplicación integra React Navigation y React Material Elements, además de tener configuraciones de ESLint.

## Requisitos previos

Antes de comenzar, asegúrate de tener instalado Node.js en tu sistema. Puedes descargarlo e instalarlo desde el sitio oficial: https://nodejs.org/

## Pasos para levantar el proyecto

1. **Clonar el repositorio:** Comienza clonando este repositorio en tu máquina local. Puedes usar el siguiente comando en tu terminal:

   ```
   git clone https://github.com/tu-usuario/react-native-expo-starter.git
   ```

2. **Instalar dependencias:** Navega al directorio del proyecto e instala las dependencias ejecutando los siguientes comandos:

   ```
   cd react-native-expo-starter
   npm install

   ```

3. **Iniciar el servidor de desarrollo:** Para levantar la aplicación en un servidor de desarrollo local, ejecuta el siguiente comando:

   ```
   npx expo start
   ```

4. **Escanear el código QR:** Una vez que el servidor de desarrollo esté funcionando, se abrirá una página en tu navegador con un código QR. Escanea este código QR con la aplicación "Expo Go" en tu dispositivo móvil (disponible en Google Play o App Store).

5. **Ejecutar la aplicación**: Después de escanear el código QR, la aplicación se cargará en tu dispositivo móvil.

## Estructura del proyecto

El proyecto sigue la siguiente estructura de directorios:

    react-native-expo-starter/
    ├── assets/ # Archivos de recursos como imágenes y fuentes
    ├── src/ # Código fuente de la aplicación
    │ ├── api / # Contiene los archivos relacionados con las llamadas a API
    │ ├── constants/ # Archivos con constantes y configuraciones
    │ ├── components/ # Componentes reutilizables
    │ ├── screens/ # Pantallas de la aplicación
    │ ├── navigation/ # Configuración de navegación
    │ ├── types/ # Archivos de definiciones de tipos TypeScript
    │ └── App.tsx # Punto de entrada de la aplicación
    ├── App.tsx # Archivo principal de la aplicación
    ├── package.json # Archivo de configuración de npm
    └── ... # Otros archivos y directorios

¡Listo! Ahora deberías tener la aplicación React Native Expo ejecutándose en tu dispositivo móvil. ¡Puedes comenzar a trabajar en tu proyecto desde aquí!

Si tienes algún problema o pregunta, no dudes en abrir un "issue" en este repositorio. ¡Buena suerte con tu proyecto!
