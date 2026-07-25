# NovaShop - Maquetación de Página Principal (Bootstrap 5)

**Nombre:** [Amtony Jeovani Castañeda Rios]
**Carné:** [1890-17-15352]

## Descripción del proyecto

Maquetación visual (solo diseño, sin funcionalidad) de la página principal de una
tienda online ficticia llamada **NovaShop**, desarrollada con **HTML5** y
**Bootstrap 5.3**. El proyecto cumple con los requisitos de la tarea:
carousel de imágenes, ícono de carrito con contador simulado, menú lateral de
categorías, listado de productos en tarjetas (cards) y diseño totalmente
responsivo.

## Componentes de Bootstrap utilizados

- **Navbar** (`navbar`, `navbar-expand-lg`) con menú colapsable y botón de carrito.
- **Carousel** (`carousel`, `carousel-item`, indicadores y controles) para las promociones principales.
- **Grid system** (`container`, `row`, `col-sm-3`, `col-sm-9`, `row-cols-1`, `row-cols-md-3`) para la distribución responsiva.
- **Cards** (`card`, `card-img-top`, `card-body`) para mostrar cada producto.
- **List group** (`list-group`, `list-group-item`) para el menú de categorías.
- **Badges** (`badge`, `rounded-pill`) para el contador del carrito.
- **Buttons** (`btn`, `btn-outline-light`, botón personalizado `btn-shop`) para las acciones visuales ("Agregar al carrito").
- **Utilities** (`shadow-sm`, `d-flex`, `text-muted`, `mt-auto`, etc.) para espaciado y alineación.
- **Bootstrap Icons** para el ícono del carrito de compras y otros detalles visuales.

## Diseño responsivo

- En pantallas pequeñas (celulares): los productos se muestran uno por fila (100% del ancho).
- En pantallas medianas/grandes: los productos se muestran en 3 columnas por fila.
- La columna de categorías (`col-sm-3`) y la de productos (`col-sm-9`) se apilan verticalmente en pantallas pequeñas y se muestran una junto a la otra en pantallas medianas/grandes.

## Estructura de archivos

```
tienda-online/
├── index.html      # Página principal
├── styles.css       # Estilos adicionales personalizados
└── README.md        # Este archivo
```

## Cómo ver el proyecto

1. Clonar o descargar el repositorio.
2. Abrir el archivo `index.html` en cualquier navegador, o
3. Visitar el sitio publicado: **[URL de GitHub Pages / Netlify aquí]**

## Nota

Este proyecto es únicamente de **maquetación visual**. Los botones ("Agregar
al carrito"), el menú de categorías y el contador del carrito son elementos
estáticos que no tienen funcionalidad real; su propósito es simular la
apariencia de una tienda en línea.
