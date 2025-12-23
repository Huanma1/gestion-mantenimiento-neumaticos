# TyreFlow - Sistema de Gestión de Neumáticos y Flota

Una solución integral diseñada para el control, seguimiento y mantenimiento de neumáticos en flotas de transporte y talleres mecánicos. Este sistema optimiza el ciclo de vida de los neumáticos, desde su instalación hasta el recauchaje o desecho final.

## 🚀 Características Principales

- **Gestión de Inventario:** Control detallado de neumáticos, marcas, medidas y estados.
- **Flujo de Reparación y Recauchaje:** Seguimiento de envíos a talleres externos y procesos de renovación.
- **Recepción Masiva:** Interfaz optimizada para móviles que permite recepcionar múltiples ítems con un solo clic.
- **Seguimiento de Kilometraje:** Registro preciso de rendimiento por neumático y unidad (patente).
- **Reportes Dinámicos:** Visualización de tasas de rechazo, estados de flota y proyecciones de mantenimiento mediante gráficos interactivos.
- **Gestión de Desechos:** Control de neumáticos fuera de servicio con motivos de baja auditables.

## 🛠️ Stack Tecnológico

### Frontend
- **React 19** con **Vite** para una experiencia de desarrollo ultra rápida.
- **TypeScript** para un código robusto y tipado.
- **Tailwind CSS** para un diseño moderno, responsivo y "glassmorphic".
- **Recharts** para la visualización de datos y analíticas.

### Backend
- **FastAPI** (Python) para una API de alto rendimiento y documentación automática (Swagger).
- **SQLAlchemy** como ORM para la gestión de la base de datos.
- **MySQL** como motor de base de datos persistente.

## 📦 Instalación y Configuración

### Requisitos Previos
- Node.js (v18+)
- Python 3.10+
- MySQL Server

### Configuración del Backend
1. Navega a la carpeta `/back`.
2. Crea un entorno virtual: `python -m venv venv`.
3. Activa el entorno e instala dependencias:
   ```bash
   pip install fastapi uvicorn sqlalchemy pymysql python-dotenv
