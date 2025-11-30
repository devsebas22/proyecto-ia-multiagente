<p align="center">
  <img src="https://svg-banners.vercel.app/api?type=origin&text1=VioletStore&text2=Clean%20Beauty&width=1000&height=250" alt="VioletStore">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PHP-7.4+-blue?style=for-the-badge&logo=php">
  <img src="https://img.shields.io/badge/MySQL-8.0+-orange?style=for-the-badge&logo=mysql">
  <img src="https://img.shields.io/badge/Frontend-HTML5%20%26%20CSS3-green?style=for-the-badge&logo=html5">
  <img src="https://img.shields.io/badge/Backend-PHP-yellow?style=for-the-badge&logo=php">
  <img src="https://img.shields.io/badge/Status-In%20Development-yellow?style=for-the-badge&logo=progress">
</p>

---

# 📘 Proyecto VioletStore - E-commerce Clean Beauty

**VioletStore** es una plataforma de e-commerce dedicada a la belleza limpia, donde la transparencia, la ética y los ingredientes puros son nuestra principal misión. Aquí puedes comprar productos de belleza y cuidado personal 100% veganos, cruelty-free, y con ingredientes naturales, libres de sulfatos, parabenos y siliconas.

---

## 👨‍🏫 Autores

- **Juan José Ospina**
- **Sebastián Mogollón**
- **Julio César Crispín**

---

## 🚀 Características Principales

- **Catálogo de productos** con filtros avanzados por certificaciones y categorías
- **Ficha detallada de producto** con ingredientes, certificaciones y modo de uso
- **Carrito de compras** con descuentos y promociones
- **Proceso de pago** con múltiples métodos (tarjetas, PayPal)
- **Gestión de usuarios** (registro, login, perfil, historial de pedidos)
- **Asesoría personalizada** para elegir los productos adecuados
- **Contenido educativo** sobre Clean Beauty en el blog
- **Gestión de inventario** en tiempo real

---

## 🚀 Tecnologías Utilizadas

- **PHP 7.4+** para el Backend
- **MySQL 8.0+** para la base de datos
- **HTML5** y **CSS3** para el Frontend
- **XAMPP** o **MAMP** para el servidor local
- **Git & GitHub** para el control de versiones

---

## 📦 Instalación

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/usuario/violetstore.git
   cd violetstore
Configurar la base de datos:

Crear la base de datos en MySQL:

bash
Copiar código
mysql -u root -p < database.sql
O mediante phpMyAdmin:

Crea la base de datos llamada violetstore

Importa el archivo database.sql

Configurar la conexión a la base de datos:
Edita el archivo config.php con los detalles de tu base de datos:

php
Copiar código
define('DB_HOST', 'localhost');
define('DB_NAME', 'violetstore');
define('DB_USER', 'root');
define('DB_PASS', 'tu_contraseña');
Iniciar el servidor local:
Si estás utilizando XAMPP, coloca el proyecto en la carpeta htdocs y activa Apache y MySQL. Luego accede a http://localhost/violetstore.

Verificar la instalación:
Abre tu navegador y accede a http://localhost/violetstore.

📊 Modelado de Datos
Entidades Principales:
Producto:

nombre: Atributo (String)

categoria: Atributo (String)

precio: Atributo (Number)

descripcion: Atributo (Text)

imagen: Atributo (String)

stock: Atributo (Number)

Categoría:

nombre: Atributo (String)

Certificación:

nombre: Atributo (String)

Usuario:

nombre: Atributo (String)

email: Atributo (String)

contraseña: Atributo (String)

perfil: Atributo (Text)

Pedido:

usuario_id: Relación con la entidad Usuario

productos: Relación con la entidad Producto

total: Atributo (Decimal)

estado: Atributo (String)

🛒 Flujo de Compra de un Producto
Navegar por el Catálogo de Productos
El usuario accede al catálogo, filtra productos por categorías (Cuidado Facial, Limpieza, etc.) y busca por nombre o certificaciones.

Ver Detalles del Producto
Al seleccionar un producto, se muestra la ficha detallada con descripción, precio, ingredientes, certificaciones y modo de uso.

Agregar al Carrito
El usuario añade productos al carrito, que se actualiza con la cantidad y el precio total. Se verifica el stock.

Proceso de Pago
El usuario se autentica, ingresa los detalles de pago y el sistema valida la transacción. Se envía una notificación de confirmación al usuario.

Finalización del Pedido
El pedido se registra con su estado (pendiente, enviado, entregado) y se actualiza el inventario.

📋 Casos de Uso
CU-001: Registrar Nuevo Producto
El administrador registra nuevos productos en el sistema, incluyendo nombre, descripción, precio, imagen, categoría y certificaciones.

CU-002: Realizar Compra de Producto
El usuario selecciona productos, los agrega al carrito y procede al pago, donde ingresa los datos necesarios. El sistema valida la transacción y genera la confirmación de compra.

CU-003: Gestionar Inventario
El administrador gestiona el inventario, actualizando cantidades y agregando nuevos productos.

CU-004: Iniciar Sesión / Registrarse
El usuario ingresa su correo y contraseña, o se registra si no tiene cuenta.

📸 Imágenes
Página de Inicio
<p align="center"> <img src="ruta-a-imagen/violetstore-home.png" alt="Página de inicio"> </p>
Catálogo de Productos
<p align="center"> <img src="ruta-a-imagen/violetstore-products.png" alt="Catálogo de productos"> </p>
🤝 Contribuciones
¡Las contribuciones son bienvenidas! Para contribuir:

Fork el proyecto

Crea una rama para tu feature (git checkout -b feature/AmazingFeature)

Realiza tus cambios

Haz commit con el mensaje (git commit -m 'Add some AmazingFeature')

Haz push a tu rama (git push origin feature/AmazingFeature)

Abre un Pull Request

📄 Licencia
Este proyecto es parte de un trabajo académico en la Universidad Tecnológica de Pereira.

📞 Contacto
VioletStore Team

Email: contacto@violetstore.com

GitHub: github.com/violetstore

VioletStore - La Transparencia es Nuestro Ingrediente Secreto 🌿

Última actualización: Noviembre 2025

nginx
Copiar código

Este README está diseñado para hacer que el proyecto sea visualmente atractivo y fácil de navegar, con
