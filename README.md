# Práctica Calificada N° 3 (PC3) - Portafolio Interactivo

**Curso:** Hojas de Estilo en Cascada Avanzado  
**Estudiante:** Portafolio Interactivo  
**Modalidad:** Individual  

---

## 📌 Descripción del Proyecto
Este proyecto es una landing page denominada **"Portafolio Interactivo"** desarrollada para presentar proyectos personales y demostrar el dominio de **Bootstrap 5**, **Transformaciones 2D y 3D en CSS**, así como **Animaciones Avanzadas con `@keyframes`**.

---

## 🚀 Tecnologías e Implementaciones Realizadas

### 1. Estructura y Framework (Bootstrap 5)
- **Barra de Navegación (Navbar):** Totalmente responsiva con colapso tipo hamburguesa (`navbar-expand-lg`, `bg-dark`).
- **Sistema de Grid:** Organización responsiva utilizando `container`, `row` y combinaciones de `col-sm-12` y `col-md-4` para adaptar el diseño a móviles, tablets y computadoras.
- **Formulario de Contacto:** Diseñado con controles estándar de Bootstrap (`form-control`, `form-label`, `mb-3`).
- **Botones:** Botones de acción ("Enviar" y "Limpiar") organizados con la clase `d-grid gap-2`.

### 2. Transformaciones y Transiciones (CSS Puro)
- **Transformaciones 2D (Efecto `:hover`):**
  - **Caja 1 (Rotación):** Aplica `transform: rotate(6deg)`.
  - **Caja 2 (Escalado):** Aplica `transform: scale(1.08)`.
  - **Caja 3 (Traslación / Sesgado):** Aplica `transform: translateY(-10px) skewX(-3deg)`.
  - Todas las cajas utilizan `transition` para lograr un movimiento suave.
- **Transformaciones 3D:**
  - Implementación de tarjeta desplegable utilizando `perspective: 1000px`, `transform-style: preserve-3d` y giros en ejes 3D con `rotateY(180deg) rotateX(10deg)` y `backface-visibility: hidden`.

### 3. Animaciones CSS Avanzadas (`@keyframes`)
- **Animación Personalizada (`@keyframes slideInDown`):** Animación de entrada para el título principal de la cabecera.
- **Loader Principal (`@keyframes customSpin`):** Spinner de carga infinito ubicado en el hero header.
- **Loader Secundario:** Indicador de carga animado dentro del botón de envío del formulario.

---

## 📂 Estructura de Archivos
```text
├── index.html        # Estructura HTML5 con Bootstrap 5 y CSS embebido
└── README.md         # Documentación del proyecto para el repositorio de GitHub
```

---

## 📋 Instrucciones para la Evaluación
1. Abrir el archivo `index.html` en cualquier navegador web moderno.
2. Interactuar con las tarjetas de la sección "Proyectos" para visualizar los efectos 2D al hacer `:hover`.
3. Interactuar con la tarjeta central de la sección "Demostración de Transformación 3D" para observar el giro 3D completo.
4. Comprobar la adaptabilidad responsiva ajustando el tamaño de la ventana o inspeccionando en dispositivos móviles (`F12`).
