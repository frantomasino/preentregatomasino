# eCommerce Backend

Este proyecto es una aplicación de backend para un eCommerce, desarrollado con Node.js y Express. El servidor maneja rutas para productos y carritos, permitiendo realizar operaciones CRUD sobre los productos y gestionar los carritos de compras. La persistencia de datos se realiza utilizando el sistema de archivos (File System) en archivos JSON.

## Estructura del Proyecto

src/
│
├── routes/
│   ├── products.router.js
│   └── carts.router.js
├── models/
│   ├── Cart.js
│   └── Product.js
├── services/
│   ├── ProductManager.js
│   └── CartManager.js
├── views/
│   ├── layouts/
│   │   └── main.handlebars
│   ├── home.handlebars
│   └── realTimeProducts.handlebars
│
└── app.js
└── database.js
│data/
├── products.json
└── carrito.json
├public/
└── js/
│    └── main.js
├── node_modules
├── package.json
├── package-lock.json
└── README.md

## Inicio del servidor 

nodemon src/app.js
 



### Uso

**Home**: `http://localhost:8080/home` - Muestra lista de productos que ya estan y los creados.
**Real-Time Products**: `http://localhost:8080/realtimeproducts` - Creacion de productos en tiempo real, con eliminancion para poder borrar algun producto. 

**POSTMAN** Para crear productos en el backend se puede hacer desde el POSTMAN con GET - PUT - DELETE

**Para terminar de verificar que el producto se creo pueden ir al products.json que aparecen creados.

 