# UI Kit - Sistema de Gestión de Incidentes (Help Desk)

Este proyecto contiene el **Design System** inicial para la interfaz de Help Desk de la Universidad Técnica de Manabí.

## 🛠️ Tecnologías y Características
- **HTML5 Semántico**: Uso de `<main>`, `<section>`, `<article>` y `<header>`.
- **CSS3 Puro**: Sin librerías externas.
- **Variables CSS (`:root`)**: Control centralizado de colores, fuentes, sombras y radios de borde.
- **Modelo de Cajas**: Configuración global de `box-sizing: border-box`.
- **Accesibilidad**: Feedback visual claro para los estados `:hover` y `:focus-visible`.

## 🚀 Guía de Uso de Componentes

### Botones
Aplica la clase base `.btn` combinada con la variante deseada:
- `.btn.btn-primary`
- `.btn.btn-secondary`
- `.btn.btn-danger`

### Campos de Formulario
Usa la estructura `.form-group` envolviendo el `<label>` y el elemento de entrada (`.form-input` o `.form-select`).

### Badges de Prioridad
Etiquetas pequeñas para el estado de los tickets:
- `<span class="badge badge-alta">Alta</span>`
- `<span class="badge badge-media">Media</span>`
- `<span class="badge badge-baja">Baja</span>`

### Ticket Cards
Estructura en rejilla responsiva utilizando `.card-grid` y contenedores `.ticket-card`.