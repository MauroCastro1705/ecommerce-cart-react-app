# E-commerce con Carrito de Compras en React

Este es un proyecto de e-commerce desarrollado en React que incluye un carrito de compras funcional. La aplicación permite a los usuarios navegar por productos, ver detalles de cada producto, agregar productos al carrito y gestionar su compra. Está construido utilizando React, Tailwind CSS para estilos y una estructura de componentes modular.

## Características principales

- **Navegación entre páginas**: Uso de `react-router-dom` para manejar rutas y navegación.
- **Página de inicio (`Home`)**: Muestra una lista de productos disponibles.
- **Página de detalles (`Detail`)**: Muestra información detallada de un producto específico.
- **Carrito de compras**: Permite agregar, eliminar y gestionar productos en el carrito.
- **Diseño responsive**: Utiliza Tailwind CSS para un diseño moderno y adaptable a diferentes dispositivos.
- **Gestión del estado del carrito**: Implementa un store para manejar el estado del carrito de compras.

## Estructura del proyecto
maurocastro1705-ecommerce-cart-react-app/
├── README.md
├── LICENSE
├── package.json
├── tailwind.config.js # Configuración de Tailwind CSS
├── public/
│ ├── index.html
│ ├── manifest.json
│ └── robots.txt
└── src/
├── App.css # Estilos globales
├── App.js # Componente principal de la aplicación
├── App.test.js # Pruebas unitarias
├── index.css # Estilos de entrada
├── index.js # Punto de entrada de la aplicación
├── products.js # Datos de los productos
├── reportWebVitals.js # Métricas de rendimiento
├── setupTests.js # Configuración de pruebas
├── assets/
│ └── images/ # Imágenes utilizadas en el proyecto
├── components/
│ ├── cartItem.js # Componente para un ítem del carrito
│ ├── cartTab.js # Componente para la pestaña del carrito
│ ├── header.js # Componente del encabezado
│ ├── layout.js # Layout principal de la aplicación
│ └── productCart.js # Componente para mostrar un producto en el carrito
├── pages/
│ ├── detail.js # Página de detalles del producto
│ └── home.js # Página de inicio
└── stores/
├── cart.js # Lógica del carrito de compras
└── index.js # Store principal