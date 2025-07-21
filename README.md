📁 mi-app-3d
├── 📁 backend
│   ├── 📁 src
│   │   ├── 📁 controllers       # Lógica de las rutas
│   │   │   ├── auth.controller.js
│   │   │   ├── diseños.controller.js
│   │   ├── 📁 routes            # API endpoints
│   │   │   ├── auth.routes.js
│   │   │   ├── diseños.routes.js
│   │   ├── 📁 models            # Esquemas de DB
│   │   │   ├── usuario.model.js
│   │   │   ├── diseño.model.js
│   │   ├── 📁 middleware        # Autenticación, validaciones
│   │   │   ├── auth.middleware.js
│   │   ├── 📁 utils             # Funciones auxiliares
│   │   │   ├── cloudinary.js
│   │   ├── db.js                # Conexión a PostgreSQL
│   │   ├── server.js            # Configuración de Express
│   ├── .env                     # Variables de entorno
│   ├── package.json             # Backend dependencias
│
├── 📁 frontend
│   ├── 📁 src
│   │   ├── 📁 components        # Componentes React
│   │   │   ├── Navbar.jsx
│   │   │   ├── LoginForm.jsx
│   │   │   ├── UploadForm.jsx
│   │   │   ├── Gallery.jsx
│   │   ├── 📁 pages             # Vistas principales
│   │   │   ├── Home.jsx
│   │   │   ├── Login.jsx
│   │   │   ├── Register.jsx
│   │   │   ├── Dashboard.jsx
│   │   ├── 📁 services          # Llamadas API
│   │   │   ├── api.js
│   │   ├── App.jsx
│   │   ├── main.jsx
│   ├── package.json             # Frontend dependencias
│
├── docker-compose.yml           # Opcional: contenerización
└── README.md


