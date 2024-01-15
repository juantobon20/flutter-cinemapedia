# Cinemapedia Flutter

Este es un proyecto de ejemplo de como funciona flutter y dart.

## Configuración del proyecto

1. Copiar el .env.template y renombrarlo a .env
2. Cambiar las variables de entorno (The MovieDB)
3. Cambios en la entidad, hay que ejecutar el comando

flutter pub run build_runner build

## 1. Gestor de Estado (Riverpod)

En este proyecto utilizamos Riverpod como gestor de estado. Riverpod es una biblioteca de gestión de estado en Flutter que facilita la inyección de dependencias y la gestión del estado de manera eficiente.

### ¿Qué es Riverpod?

Riverpod es un paquete de gestión de estado que sigue el patrón de Provider, pero mejora la eficiencia y flexibilidad en la gestión del estado en Flutter. Permite la inyección de dependencias de una manera más intuitiva y facilita la organización del código.

### Cómo Funciona

![Riverpod Diagram](https://miro.medium.com/v2/resize:fit:1400/1*h4ahfMrkEhwmx5_Y6Y7zOA.png)

En la imagen anterior, se ilustra de manera simplificada cómo funciona Riverpod en nuestro proyecto. Asegura una gestión del estado eficiente y sin problemas, proporcionando una forma clara de acceder y modificar los datos en toda la aplicación.

## 2. Manejo del Código - Buenas Prácticas en Flutter

- La aplicación sigue los principios de SOLID
- Los archivos, clases, metodos y variables deben ser nombradas 100% en ingles y que su nombre  sea lo más claro para que es.

### Nomenclatura de Archivos

- **Carpetas:**
  - Mantén la estructura de carpetas ordenada y lógica.
  - Utiliza nombres descriptivos para las carpetas.

- **Nombres de Archivos:**
  - Usa camelCase para los nombres de archivos.
  - Nombra los archivos de manera descriptiva y concisa.

### Nomenclatura de Clases y Variables

- Utiliza CamelCase para el nombre de las clases.
- Utiliza camelCase para el nombre de las variables

```dart
class MyClass {
  // ...
}


String myString;
void myMethod() {
  // ...
}
