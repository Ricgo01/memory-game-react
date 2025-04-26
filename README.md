# 🎮 Memory Game React

![React Version](https://img.shields.io/badge/React-18.0.0-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 📝 Descripción

Un juego de memoria clásico desarrollado completamente en React sin utilizar herramientas como Create React App o Vite. El objetivo es encontrar todos los pares de cartas con las mismas imágenes en la menor cantidad de movimientos posible.

## ✨ Características

- 🃏 16 cartas (8 pares) con imágenes que deben ser emparejadas
- 👁️ Fase de vista previa que permite memorizar las cartas antes de comenzar
- ⏱️ Temporizador para medir el tiempo de juego
- 🔢 Contador de movimientos para desafiar al jugador
- 🎭 Animaciones suaves de volteo de cartas
- 🏆 Mensaje de victoria con estadísticas al completar el juego
- 🔀 Distribución aleatoria de las cartas en cada partida
- 📱 Diseño responsive adaptable a diferentes dispositivos

## 🛠️ Tecnologías utilizadas

- **React**: Biblioteca para construir interfaces de usuario
- **React DOM**: Renderizado de componentes React en el navegador
- **Babel**: Transpilador de JSX a JavaScript
- **CSS Grid**: Sistema de layout para la cuadrícula de cartas
- **CSS Transitions**: Animaciones suaves para el volteo de cartas
- **JavaScript ES6+**: Características modernas de JavaScript

## 🚀 Cómo usar

1. Clona este repositorio
2. Abre `index.html` en tu navegador
3. ¡Diviértete jugando!

No se requiere ninguna instalación adicional ya que el proyecto utiliza React a través de CDN.

## 📚 Estructura del proyecto

```
memory-game-react/
│
├── index.html          # Archivo principal que contiene todo el código
│
└── assets/             # Carpeta de recursos
    ├── turf.jpg        # Imagen de fondo
    ├── card-back.png   # Imagen del reverso de las cartas
    ├── img1.png        # Imágenes para los pares de cartas
    ├── img2.png
    └── ...
```

## 🎲 Cómo jugar

1. Al iniciar el juego, verás todas las cartas boca arriba durante 3 segundos
2. Memoriza la ubicación de las cartas
3. Las cartas se voltearán automáticamente y el juego comenzará
4. Haz clic en cualquier carta para voltearla
5. Intenta encontrar su pareja haciendo clic en otra carta
6. Si las dos cartas coinciden, se mantendrán boca arriba
7. Si no coinciden, se voltearán de nuevo tras un breve momento
8. El juego termina cuando encuentres todos los pares

## 🧠 Conceptos de React implementados

- Componentes funcionales
- Estado con React Hooks (useState)
- Efectos secundarios (useEffect)
- Renderizado condicional
- Manipulación de listas con map
- Gestión de eventos
- Clases CSS dinámicas

## 📷 Screenshots

*Las capturas de pantalla se pueden agregar después de subir el proyecto a GitHub*

## 👨‍💻 Desarrollado por

**Ricardo Díaz** - Estudiante de Ingeniería en la Universidad del Valle de Guatemala

---

⭐ Este proyecto fue creado como parte del laboratorio de React de la clase de Desarrollo Web.