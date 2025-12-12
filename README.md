# 📽️ NextFilm-Front — Angular App para Gestión de Stock de Películas

**NextFilm-Front** es el frontend de una aplicación para gestionar el inventario de películas.
Está desarrollado con **Angular**, siguiendo buenas prácticas de arquitectura, componentes reutilizables y comunicación con un backend REST.

## 🎯 Resumen del proyecto

NextFilm-Front permite gestionar un catálogo de películas de forma sencilla y visual:

- Listado general de películas
- Búsquedas y filtros por género, disponibilidad, título, etc.
- Gestión del stock
- Vista detallada de cada película
- Interfaz moderna, modular y responsive

Este proyecto sirve para demostrar manejo sólido de Angular en un proyecto real.

## 🛠️ Tech Stack

- **Angular (v13+)**
- **TypeScript**
- **Angular Router**
- **Angular Material / Bootstrap / CSS propio**
- **Servicios para consumo de APIs REST**
- **Integración con backend (NextFilm-Back / API REST propia)**
- **Arquitectura modular**

## 📁 Estructura del proyecto

```
nextfilm-front/
├── src/
│   ├── app/
│   │   ├── components/
│   │   │   ├── movie-card/
│   │   │   ├── navbar/
│   │   │   └── filters/
│   │   ├── pages/
│   │   │   ├── movies-list/
│   │   │   ├── movie-detail/
│   │   │   └── stock-management/
│   │   ├── services/
│   │   ├── models/
│   │   └── app-routing.module.ts
├── angular.json
├── package.json
└── ...
```

## ✨ Funcionalidades principales

- Listado dinámico de películas
- Búsqueda y filtrado en tiempo real
- Paginación y navegación por rutas
- Vista de detalles
- Modificación del stock
- Manejo de errores en consumo de API
- Componentes reutilizables y UI responsive

## 🖼️ Capturas recomendadas

- Lista de películas
- Vista de detalle
- Filtros y búsqueda
- Gestión de stock
- Vista responsive en móvil

## 🚀 Instalación y ejecución

### Requisitos

- Node.js 16+
- Angular CLI instalado globalmente

### Pasos

1. Clona el repositorio:
```bash
git clone https://github.com/Jechig0/nextfilm-front.git
cd nextfilm-front
```

2. Instala dependencias:
```bash
npm install
```

3. Ejecuta la aplicación:
```bash
ng serve
```

4. Abre el navegador en:
```
http://localhost:4200/
```

## 🔗 Integración con API REST

| Método | Endpoint | Descripción |
|--------|----------|-------------|
| GET | `/api/movies` | Obtiene todas las películas |
| GET | `/api/movies/{id}` | Obtiene detalles por ID |
| PUT | `/api/movies/{id}` | Actualiza stock |
| POST | `/api/movies` | Crea una película nueva |

## 📦 Buenas prácticas aplicadas

- Arquitectura modular en Angular
- Servicios desacoplados y tipados
- Manejo centralizado de errores
- Componentes reutilizables
- Rutas organizadas
- UI accesible y responsive

## 📈 Habilidades demostradas

- Desarrollo avanzado con **Angular**
- Comunicación con **APIs REST**
- Diseño y modularización del frontend
- Gestión de estado local y componentes
- Creación de aplicaciones reales

## 📫 Contacto

**GitHub:** https://github.com/Jechig0  
**LinkedIn:** *(tu enlace)*  
**Email:** *(tu email profesional)*
