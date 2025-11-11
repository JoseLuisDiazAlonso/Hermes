# Hermes 🚛⚡

Sistema integral de gestión para control de combustible y manejo de residuos, diseñado para optimizar operaciones logísticas y proporcionar análisis detallados de recursos.

## 📋 Descripción

ProyectoAtreva es una aplicación web full-stack que centraliza la gestión de dos áreas operativas críticas:

- **Control de Combustible**: Seguimiento completo de consumo, costos y eficiencia de vehículos
- **Gestión de Residuos**: Monitoreo de recolección, análisis de peso y métricas ambientales

El sistema proporciona capacidades de entrada de datos, visualización mediante tablas filtrables, gráficos analíticos y cálculos automáticos como el consumo promedio de combustible.

## ✨ Características Principales

### Módulo de Combustible
- 📊 Registro de consumo por vehículo y conductor
- 💰 Seguimiento de precios y análisis de costos
- 📈 Cálculo automático de consumo promedio
- 🚗 Gestión de datos de vehículos (matrículas, modelos)
- 👤 Administración de información de conductores
- 📉 Gráficos y reportes de eficiencia

### Módulo de Residuos
- ♻️ Registro de recolección de residuos
- ⚖️ Medición y seguimiento de pesos
- 📊 Análisis y métricas de recolección

### Funcionalidades Generales
- 🔐 Sistema de autenticación y autorización seguro
- 🔍 Tablas interactivas con filtros avanzados
- 📊 Visualización de datos mediante gráficos
- 💾 Base de datos robusta para almacenamiento persistente
- 📱 Interfaz web responsive y moderna
- 🔄 API RESTful para integración

## 🛠️ Tecnologías

### Backend
- Node.js / Express (o tu framework backend elegido)
- Base de datos relacional (PostgreSQL/MySQL)
- Sistema de autenticación JWT

### Frontend
- Framework moderno (React/Vue/Angular)
- Librería de gráficos (Chart.js/D3.js)
- CSS/Tailwind para estilos

### DevOps
- Git para control de versiones
- GitHub para gestión de proyecto
- Testing automatizado

## 📁 Estructura del Proyecto

```
ProyectoAtreva/
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── middleware/
│   │   └── config/
│   ├── tests/
│   └── package.json
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── utils/
│   ├── public/
│   └── package.json
├── database/
│   ├── migrations/
│   └── seeds/
├── docs/
└── README.md
```

## 🚀 Instalación

### Prerrequisitos
- Node.js (v16 o superior)
- npm o yarn
- Base de datos (PostgreSQL/MySQL)

### Pasos de Instalación

1. **Clonar el repositorio**
```bash
git clone https://github.com/tu-usuario/ProyectoAtreva.git
cd ProyectoAtreva
```

2. **Instalar dependencias del backend**
```bash
cd backend
npm install
```

3. **Instalar dependencias del frontend**
```bash
cd ../frontend
npm install
```

4. **Configurar variables de entorno**
```bash
# Crear archivo .env en backend/
cp .env.example .env
# Editar .env con tus configuraciones
```

5. **Configurar la base de datos**
```bash
cd backend
npm run db:migrate
npm run db:seed
```

6. **Iniciar el servidor de desarrollo**

Terminal 1 (Backend):
```bash
cd backend
npm run dev
```

Terminal 2 (Frontend):
```bash
cd frontend
npm start
```

## 📖 Uso

### Acceso a la Aplicación
1. Abre tu navegador en `http://localhost:3000`
2. Inicia sesión con tus credenciales
3. Navega entre los módulos de Combustible y Residuos

### Módulo de Combustible
- Accede a "Combustible" desde el menú principal
- Registra nuevos consumos usando el formulario
- Visualiza estadísticas y gráficos de eficiencia
- Filtra datos por conductor, vehículo o fecha

### Módulo de Residuos
- Accede a "Residuos" desde el menú principal
- Registra recolecciones con peso y ubicación
- Consulta reportes y métricas de recolección
- Analiza tendencias mediante gráficos

## 🗺️ Roadmap de Desarrollo

### Milestone 1: Configuración Inicial (Semana 1)
- ✅ Configuración del repositorio
- ✅ Estructura de directorios
- ✅ Configuración de herramientas de desarrollo
- ✅ Documentación inicial

### Milestone 2: Base de Datos (Semanas 1-2)
- 🔄 Diseño del modelo de datos
- 🔄 Implementación de migraciones
- 🔄 Configuración de conexiones
- 🔄 Seeds de datos de prueba

### Milestone 3: Autenticación (Semana 2)
- 🔄 Sistema de login/registro
- 🔄 Gestión de tokens JWT
- 🔄 Middleware de autorización
- 🔄 Protección de rutas

### Milestone 4: APIs (Semanas 3-4)
- 🔄 API de combustible (CRUD completo)
- 🔄 API de residuos (CRUD completo)
- 🔄 Endpoints de análisis y estadísticas
- 🔄 Validación de datos

### Milestone 5: Frontend (Semanas 5-6)
- 🔄 Componentes de interfaz
- 🔄 Módulo de combustible
- 🔄 Módulo de residuos
- 🔄 Gráficos y visualizaciones
- 🔄 Tablas interactivas

### Milestone 6: Testing y Deployment (Semanas 7-8)
- 🔄 Tests unitarios y de integración
- 🔄 Tests E2E
- 🔄 Configuración de CI/CD
- 🔄 Despliegue en producción

**Tiempo estimado total**: 6-8 semanas (1 desarrollador full-time)

## 🧪 Testing

```bash
# Tests del backend
cd backend
npm test

# Tests del frontend
cd frontend
npm test

# Tests E2E
npm run test:e2e
```

## 📝 Convenciones de Código

- Utilizar ESLint para mantener calidad de código
- Seguir guía de estilo establecida
- Escribir commits descriptivos siguiendo Conventional Commits
- Documentar funciones y componentes complejos

## 🤝 Contribución

Las contribuciones son bienvenidas. Por favor:

1. Fork del proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit de tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 👥 Autor

**Tu Nombre**
- GitHub: [@tu-usuario](https://github.com/tu-usuario)

## 🙏 Agradecimientos

- A todos los contribuidores que participen en el proyecto
- Comunidad de código abierto por las herramientas utilizadas

---

⭐ Si este proyecto te resulta útil, considera darle una estrella en GitHub
