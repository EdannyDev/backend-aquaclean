# 🚀AquaClean - Backend  

## 📌Descripción  
**AquaClean Backend** es el núcleo del sistema IoT que alimenta la **web informativa** y el **panel administrativo**.  

Su objetivo principal es manejar:  
- Formularios de contacto enviados desde la web.  
- Gestión básica de usuarios.  
- Envío y administración de notificaciones **push**.  
- Autenticación y seguridad de accesos.  

## 🛠️Tecnologías utilizadas  

- **Node.js**  
- **Express** (Framework para APIs REST)  
- **MongoDB / Mongoose** (Base de datos NoSQL y modelado de datos)  
- **JWT** (Autenticación y autorización)  
- **bcryptjs** (Hash de contraseñas)  
- **dotenv** (Manejo de variables de entorno)  
- **CORS** (Control de orígenes)  
- **uuid** (Identificadores únicos)  
- **web-push** (Notificaciones push)  

## ⚙️Instalación y ejecución  

```bash
# 1. Clonar el repositorio
git clone https://github.com/EdannyDev/backend-aquaclean.git

# 2. Instalar dependencias
npm install

# 3. Crear archivo de entorno
En la raíz del proyecto, crea un archivo .env con:

MONGODB_URI=mongodb://localhost:27017/aquaDB
PORT=5000
JWT_SECRET=tu_secreto_jwt
VAPID_PUBLIC_KEY=tu_vapid_public_key
VAPID_PRIVATE_KEY=tu_vapid_private_key

# 4. Ejecutar la aplicación
npm start

# 5. La API estará disponible en
http://localhost:5000

```

## ✨Endpoints principales
- Contacto: `/api/contact`
- Usuarios: `/api/user`
- Notificaciones push: `/api/push`

## 🔗Enlaces útiles
Web Informativa: https://github.com/EdannyDev/frontend-aquaclean

Panel Administrativo: https://github.com/EdannyDev/frontend-admin-aquaclean
