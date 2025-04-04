# E-commerce de Muebles (DSM-TP)

# Integrantes

- 47403 - Gómez, Agustín
- 46804 - Pitavino Tomás

# Estructura

<!-- `backend/`: API en Node.js + Express + MongoDB -->

`frontend/`: Aplicación en React + TypeScript

# Repositorios

- [backend app](https://github.com/lordagustin22/ECommerce-dsw-backend)

# Enunciado

Se pretende hacer un e-commerce de una mueblería. Los clientes podrán buscar y filtrar cada producto en un catálogo que se les muestra. Cada producto se identifica por id, nombre, descripción, precio, y categoría.

Los proveedores pueden registrarse y subir sus productos.

Clases: Cliente, Producto, Administrador, Precio, Proveedor, Vendedor

1. Modelado del Negocio

- Stakeholders (Actores Clave)

Clientes:

- Compradores de muebles (B2C).
- Empresas que compran a granel (B2B, opcional).

Administradores:

- Gestionan catálogo, pedidos y usuarios.
- Vendedores/Proveedores (opcional):
- Si el marketplace permite múltiples vendedores.

2. Requisitos Funcionales

- Para Clientes:

* Registro/login (email o redes sociales).
* Catálogo de muebles con filtros (categoría, precio, material).
* Carrito de compras + checkout (Stripe/PayPal).
* Historial de pedidos.
* Reseñas y ratings.

- Para Administradores:

* Panel de control (CRUD de productos, usuarios, pedidos).

* Dashboard de ventas (gráficos con Chart.js).

* Gestión de envíos (integración con API de logística).

- Para Vendedores (AD):

* Subida de productos.
* Gestión de inventario.

3. MVP (Mínimo Producto Viable)

- Fase 1: Catálogo + carrito + checkout básico.
- Fase 2: Autenticación + panel de administrador.
- Fase 3 (opcional): Reseñas, integración con logística.

<!-- 4. Tecnologías Confirmadas -->
<!---->
<!-- - Frontend: React + TypeScript + TailwindCSS. -->
<!-- - Backend: Node.js + Express + MongoDB. -->
<!-- - Pagos: Stripe/PayPal (sandbox para testing). -->
<!-- - Cloud: MongoDB Atlas + Cloudinary (imágenes). -->
