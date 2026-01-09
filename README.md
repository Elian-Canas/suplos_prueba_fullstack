# Proyecto Fullstack de Licitaciones

Proyecto fullstack para la gestión, registro y visualización de ofertas y licitaciones, construido con PHP 8.2 (backend) y Vue.js 2.6 (frontend), siguiendo el patron MVC y desplegado con Docker.

## 🏗️ Estructura del Proyecto
```
suplos_prueba_fullstack/
├── backend/              # Backend en PHP 8.2
│   ├── app/              # Controllers, Models, Helpers, Validations
│   ├── db/               # Migraciones, seeds, backups
│   ├── config/           # Configuración de la aplicación
│   ├── public/           # Archivos estáticos (PHP index para compatibilidad)
│   └── vendor/           # Dependencias con Composer (si aplica)
│
├── frontend/             # Aplicación Vue.js 2.6
│   ├── src/              # Componentes, vistas, store, servicios
│   ├── public/           # Assets públicos
│   ├── package.json      # Dependencias npm
│   ├── .env              # Variables de entorno
│   └── vue.config.js     # Configuración de Vue CLI
│
├── nginx/                # Configuración de servidor web reverse proxy
│   └── default.conf      # Configuración de Nginx
│
├── docker-compose.yml    # Orquestación de contenedores
└── README.md             # Documentación del proyecto
```

# Instalación
Clonar todo el repositorio con cada de los submodulos
`git clone --recurse-submodules https://github.com`

Ubicarse dentro de la carpeta
cd suplos_prueba_fullstack

# Construir e iniciar los contenedores
docker-compose up --build