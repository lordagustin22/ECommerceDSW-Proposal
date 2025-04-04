# E-commerce de Muebles (DSM-TP)

## Integrantes

- 47403 - Gómez, Agustín
- 46804 - Pitavino Tomás
- 49806 - Enzo Zajarías

## Estructura

<!-- `backend/`: API en Node.js + Express + MongoDB -->

`frontend/`: Aplicación en React + TypeScript

## Repositorios

- [backend app](https://github.com/lordagustin22/ECommerce-dsw-backend)

## Descripción

Esto es un E-commerce de una mueblería. Los clientes podrán buscar, filtrar cada producto en un catálogo que se les muestra, así como agregarlos a favoritos. Los productos se pueden agregar directamente al carrito o pasar al checkout inmediatamente. Al hacer checkout se puede elegir el medio de pago que más le convenga al cliente. Conforme un cliente compra muchos productos, se les va otorgando puntos que les permitirán tener descuentos. Los costos de envío se reducirán cuando los clientes compren en mucha cantidad. Las compras en mucha cantidad son consideradas como compras mayoristas. Hay un sistema de reseñas donde cada cliente puede dejar su opinión del producto. Cada compra hecha por un usuario se agrega a un historial de pedidos.

Los administradores pueden subir, actualizar, gestionar y borrar cada uno de los productos.

Clases: Cliente, Producto, Administrador, Precio, Proveedor, Vendedor

1. Modelado del Negocio

- Clientes:

  - Compradores de muebles (B2C).

- Administradores:

  - Gestionan catálogo, pedidos y usuarios.

2. Requisitos Funcionales

   - Para Clientes:

     - Registro/login (email o redes sociales).
     - Catálogo de muebles con filtros (categoría, precio, material).
     - Carrito de compras + checkout
     - Historial de pedidos.
     - Reseñas y ratings.

   - Para Administradores:

     - Panel de control (CRUD de productos, usuarios, pedidos).
     - Gestión de inventarios
     - Dashboard de ventas
     - Gestión de envíos

3. MVP (Mínimo Producto Viable)

   - Fase 1: Catálogo + carrito + checkout básico.
   - Fase 2: Autenticación + panel de administrador.
   - Fase 3 (opcional): Dashboard de ventas + reseñas + integración con logística.

<!-- 4. Tecnologías Confirmadas -->
<!---->
<!-- - Frontend: React + TypeScript + TailwindCSS. -->
<!-- - Backend: Node.js + Express + MongoDB. -->
<!-- - Pagos: Stripe/PayPal (sandbox para testing). -->
<!-- - Cloud: MongoDB Atlas + Cloudinary (imágenes). -->
