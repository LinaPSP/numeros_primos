# 🎈 Prime Scan Party - Detector de Números Primos

¡Una forma vibrante, colorida y divertida de explorar el mundo de las matemáticas! **Prime Scan Party** es una aplicación web de una sola página (SPA) que identifica números primos en tiempo real con una interfaz dinámica, animaciones de confeti y elementos flotantes.

## ✨ Características

- **Análisis en Tiempo Real:** No necesitas presionar botones. El resultado aparece mientras escribes.
- **Interfaz Dinámica:** La aplicación cambia de color y estado según el resultado (Verde para primos, Rojo para no primos).
- **Efectos Visuales:**
  - **Confeti:** Explosión de colores al encontrar un número primo.
  - **Burbujas Flotantes:** Números aleatorios que decoran el fondo.
  - **Fondo Animado:** Degradados en movimiento para una experiencia moderna.
- **Sistema de Logros:** Contador de números primos encontrados durante la sesión.
- **Diseño Responsivo:** Funciona perfectamente en móviles, tablets y computadoras.

## 🚀 Instalación y Uso

Este proyecto es "Plug & Play". No requiere dependencias ni servidores.

1. Descarga el archivo `index.html` (o el nombre que le hayas dado).
2. Haz doble clic en el archivo para abrirlo en tu navegador preferido (Chrome, Firefox, Edge, Safari).
3. ¡Empieza a escribir números y diviértete!

## 🛠️ Tecnologías Utilizadas

- **HTML5:** Estructura semántica.
- **CSS3:** - Animaciones de fotogramas clave (`@keyframes`).
    - Flexbox para el centrado.
    - Filtros de desenfoque (`backdrop-filter`).
    - Degradados dinámicos.
- **JavaScript (Vanilla):** - Lógica matemática optimizada para detección de primos (basada en la raíz cuadrada).
    - Manipulación del DOM en tiempo real.
    - Motor de partículas simple para el confeti.

## 🧠 Lógica Matemática

Para garantizar la eficiencia, el detector utiliza el siguiente algoritmo:
1. Descarta números menores a 2.
2. Verifica si el número es 2 (único primo par).
3. Evalúa divisores solo hasta la raíz cuadrada del número ingresado ($\sqrt{n}$), reduciendo drásticamente la carga de procesamiento para números grandes.

## 📝 Licencia

Este proyecto es de código abierto y libre de usar para fines educativos o recreativos. 

---
Hecho con ❤️ por [Tu Nombre/Usuario]