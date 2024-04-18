# Requisitos

![banner](./images/banner-requisitos.webp)

# Contenido

- [Requisitos](#requisitos)
  - [Requisitos Funcionales](#requisitos-funcionales)
  - [Requisitos no Funcionales](#requisitos-no-funcionales)

Como se explica en [qué son requisitos?](que-son-requisitos.md), antes de iniciar un desarrollo, es importante tener conocimiento de qué es lo que requiere el usuario y en qué orden se debe abordar estos requisitos.

Aún, cuando no vamos a pronfundizar en la gestión de requisitos, si levantaremos algunos con el fin de tener claro qué se va a desarrollar, pero, sin perder de vista, que el objetivo principal de este proyecto es sobre técnicas para la resolución de problemas en el desarrollo de software.

Se requiere de un microservicio API RESTful que reciba peticiones HTTP para la gestión de Productos y Servicios que serán vendidos y ofrecidos por nuestra empresa example.com.

## Requisitos Funcionales

![requisitos funcionales](./images/functional%20requests%20.webp)

Los requisitos funcionales, son todos aquellos requisitos que ofrecen una funcionalidad al usuario del sistema.

1. Gestión de Productos
   - Agregar Producto: Permitir a los usuarios añadir nuevos productos al sistema con detalles como nombre, descripción, precio y cantidad en stock.
   - Editar Producto: Habilitar la edición de los detalles de un producto existente.
   - Eliminar Producto: Permitir la eliminación de productos del sistema.
   - Listar Productos: Mostrar una lista de todos los productos disponibles, con la capacidad de filtrar por diversas categorías como precio, popularidad y recién añadidos.
   - Buscar Producto: Funcionalidad para buscar productos específicos basados en diferentes criterios como nombre, categoría o rango de precios.
2. Gestión de Inventarios
   _ Actualizar Inventario: Actualizar la cantidad de stock disponible para cada producto.
   _ Visualización de Inventario: Permitir a los usuarios ver el estado actual del inventario de productos. \* Alertas de Inventario Bajo: Generar notificaciones automáticas cuando los niveles de inventario de un producto caigan por debajo de un umbral predeterminado.
3. Gestión de Categorías
   - Agregar Categoría: Añadir nuevas categorías de productos al sistema.
   - Editar Categoría: Modificar detalles de categorías existentes.
   - Eliminar Categoría: Eliminar categorías del sistema.
   - Listar Categorías: Mostrar todas las categorías existentes para facilitar la navegación y la búsqueda de productos.
4. Gestión de Precios
   - Establecer Precios Especiales: Definir precios especiales para promociones o descuentos.
   - Actualizar Precios: Cambiar los precios de los productos individualmente o en masa.
   - Historial de Precios: Mantener un registro de los cambios de precios para referencia futura.
5. Integración con Otros Servicios
   - Integración con Sistemas de Pago: Conectar el microservicio con sistemas de pago para procesar transacciones.
   - Integración con Plataformas de Logística: Facilitar la integración con sistemas de logística para el envío y la entrega de productos.
6. Seguridad y Autorización
   - Autenticación de Usuarios: Asegurar que solo los usuarios autenticados puedan acceder al sistema y realizar operaciones.
   - Roles y Permisos: Definir diferentes niveles de acceso para distintos tipos de usuarios (administradores, gestores de inventario, vendedores, etc.).
   - Registro de Actividades: Mantener un log de todas las acciones realizadas en el sistema para auditorías y seguimiento de la seguridad.
7. Interfaz de Usuario
   - APIs RESTful: Desarrollar interfaces API RESTful claras y documentadas para la interacción con el microservicio desde otros sistemas o interfaces de usuario.
8. Soporte Multilingüe
   - Internacionalización: Soportar múltiples idiomas para que el microservicio pueda ser utilizado por usuarios en diferentes regiones geográficas.

## Requisitos no Funcionales

![requisitos no funcionales](./images/non%20functional%20requests.webp)
