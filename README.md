📋 Gestor de Solicitudes

Gestor de Solicitudes es una aplicación web moderna desarrollada en React y bundlada con Vite, diseñada para la administración eficiente, filtrado y seguimiento en tiempo real de requerimientos y trámites. 
La plataforma combina la reactividad de los componentes de React con una arquitectura limpia basada en gestión de estado global y contexto.

💻 Características Principales

Gestión de Requerimientos (CRUD): Creación, lectura, actualización y filtrado dinámico de solicitudes.

Gestión de Estado Híbrida:

React Context API: Administración del flujo principal de solicitudes (SolicitudesContext).

Redux Toolkit: Control centralizado de preferencias del usuario y configuraciones globales (preferenciasSlice).

Navegación Fluida: Rutas dinámicas configuradas con React Router, incluyendo vistas para listados, formularios de creación, detalle individual de solicitudes y pantalla de error 404 personalizada.

Simulación de Servicios API: Capa de servicios decoupled (src/api/) preparada para la integración con backends RESTful mediante llamadas asíncronas.

Interfaz de Usuario Responsiva: Diseño estilizado con CSS moderno y modular para una óptima experiencia visual en dispositivos móviles y de escritorio.

🛠️ Tecnologías Utilizadas

Librería Core: React 18+

Herramienta de Construcción: Vite

Gestión de Estado: Redux Toolkit (@reduxjs/toolkit) & React Context API

Enrutamiento: React Router DOM (react-router-dom)

Lenguaje: JavaScript (ES6+) / HTML5 / CSS3

Control de Calidad: Oxlint (.oxlintrc.json)

📂 Arquitectura del Proyecto

gestor-solicitudes/
├── public/                 # Recursos estáticos (Logos, iconos SVG)
├── src/
│   ├── api/                # Clientes API y configuración de peticiones HTTP
│   ├── assets/             # Imágenes y recursos multimedia del cliente
│   ├── components/         # Componentes UI reutilizables (Formularios, Filtros, Navbar, etc.)
│   ├── context/            # Proveedores de contexto (SolicitudesContext)
│   ├── data/               # Mock data para testing y prototipado rápido
│   ├── pages/              # Vistas principales (Inicio, Login, Listado, Detalle, etc.)
│   ├── store/              # Configuración de Redux Store y Slices de estado
│   ├── App.jsx             # Componente raíz y layout principal
│   └── main.jsx            # Punto de entrada de la aplicación
├── index.html              # HTML principal
├── package.json            # Dependencias y scripts del proyecto
└── vite.config.js          # Configuración de Vite
