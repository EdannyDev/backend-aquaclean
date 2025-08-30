🚀AquaClean - Backend

📌Descripción
Este es el backend del sistema AquaClean IoT.
Proporciona las APIs necesarias para la web informativa y el panel administrativo.
Su principal objetivo es manejar formularios de contacto, la gestión básica de usuarios y el envío de notificaciones push en ambos frontends.

Funcionalidades principales:
-Gestión de usuarios registrados.
-Manejo de formularios de contacto enviados desde la web.
-Envío y gestión de notificaciones push.
-Autenticación segura con JWT.

🛠️Tecnologías utilizadas
-Node.js
-Express (Framework para APIs REST)
-MongoDB / Mongoose
-JWT (autenticación y autorización)
-bcryptjs (hash de contraseñas)
-dotenv (manejo de variables de entorno)
-cors
-uuid
-web-push (notificaciones push)

⚙️Instalación y ejecución

1.-Clonar el repositorio:
git clone https://github.com/EdannyDev/backend-aquaclean.git

2.-Instalar dependencias:
npm install

3.-Crear un archivo .env en la raíz del proyecto con las siguientes variables:
MONGODB_URI=mongodb://localhost:27017/aquaDB
PORT=5000
JWT_SECRET=<tu_secreto_jwt>
VAPID_PUBLIC_KEY=<tu_vapid_public_key>
VAPID_PRIVATE_KEY=<tu_vapid_private_key>

4.-Ejecutar la aplicación:
npm start

5.-La API estará disponible en:
http://localhost:5000

✨Endpoints principales
Contacto - /api/contact
Usuarios - /api/user
Notificaciones push - /api/push

🔗 Enlaces útiles
Frontend Web informativa: https://github.com/EdannyDev/aquaclean-app
Panel Administrativo: https://github.com/EdannyDev/admin-aquaclean-app
