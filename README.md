# krisshop

## 📋 Resumen del Proyecto - KristalShop

### Objetivo
Crear una página web para mostrar y gestionar productos con las siguientes características:

### Requisitos Técnicos

#### Frontend
- Framework: Vite + React (ligero y simple)
- Estilos: Tailwind CSS

#### Backend (Supabase)
- Autenticación: Supabase Auth (login/registro)
- Base de datos: PostgreSQL (almacenar productos)
- Storage: Supabase Storage (guardar imágenes de productos)

### Funcionalidades Requeridas

#### 1. Página Principal (Pública)
✅ Mostrar galería de productos  
✅ Sistema de filtros para productos  
✅ Responsive design

#### 2. Panel de Administración (Protegido)
✅ Autenticación requerida  
✅ Formulario para subir productos  
✅ Upload de imágenes a Supabase Storage  
✅ Gestión de productos (crear/editar)

#### 3. Sistema de Autenticación
✅ Login de usuarios  
✅ Registro de nuevos usuarios  
✅ Protección de rutas admin

### Estructura del Proyecto

```text
kristalshop/
├── src/
│   ├── components/      (Productos, Filtros, FormSubir)
│   ├── pages/           (Home, Admin, Login)
│   ├── lib/             (supabaseClient.js)
│   └── App.jsx
├── package.json
└── README.md
```
