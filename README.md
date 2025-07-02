# InventarioPro 📦

Aplicación web para la gestión de inventario, desarrollada con React, Vite, Supabase y otras tecnologías modernas. Permite registrar productos, movimientos de stock, usuarios y mucho más.

## 🚀 Tecnologías

- ⚛️ React + Vite
- 🌐 React Router DOM
- 🎨 Styled Components
- 💬 Supabase (Auth + Base de datos)
- ⚡ React Query
- 📊 Recharts
- 🧪 React Query Devtools

## 📁 Estructura de carpetas

src/
├── components/
├── context/
├── hooks/
├── pages/
├── routers/
├── store/
├── supabase/
├── styles/
└── utils/



## 🛠️ Instalación

```bash
# Cloná el repositorio
git clone https://github.com/mariomarquesto/InventarioPro.git
cd InventarioPro

# Instalá dependencias
npm install

# Ejecutá el proyecto
npm run dev



Crea un archivo .env con tus credenciales de Supabase:

VITE_SUPABASE_URL=https://tu-url.supabase.co
VITE_SUPABASE_ANON_KEY=tu-clave-anon


🔐 Autenticación

Se utiliza Supabase Auth para registrar e iniciar sesión con email/password.
📦 Funcionalidades

Login de usuarios

Panel de control por permisos

Gestión de productos

Registro de movimientos de entrada/salida

Visualización de estadísticas y reportes

    Soporte para temas (oscuro / claro)

🧠 Estado global

    Zustand + React Query para el manejo eficiente del estado y la cache.

