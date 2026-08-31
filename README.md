# Configuración del entorno frontend y creación del primer proyecto

## Nombre del estudiante
Roman Alvarado Morales

## Descripción breve del proyecto
Este proyecto sirve como base para la configuración de un entorno frontend con TypeScript y Vite. Incluye la estructura inicial de una aplicación web simple, con un contador interactivo como ejemplo de uso básico del entorno.

## Tecnologías utilizadas
- HTML5
- CSS3
- TypeScript
- Vite
- Node.js

## Requisitos previos
- Tener instalado Node.js en el sistema
- Tener un gestor de paquetes como npm o pnpm

## Instalación
1. Clona este repositorio o descarga el proyecto.
2. Abre una terminal en la carpeta raíz del proyecto.
3. Ejecuta el siguiente comando para instalar las dependencias:

```bash
npm install
```

O si prefieres pnpm:

```bash
pnpm install
```

## Ejecución
Para iniciar el proyecto en modo desarrollo, ejecuta:

```bash
npm run dev
```

O con pnpm:

```bash
pnpm dev
```

Luego abre la URL que indique Vite en la terminal, normalmente:

```bash
http://localhost:5173
```

## Scripts disponibles
- `npm run dev` - Inicia el servidor de desarrollo
- `npm run build` - Compila el proyecto con TypeScript y genera la versión de producción
- `npm run preview` - Previsualiza la compilación de producción

## Estructura principal del proyecto
```bash
fundamentos-ts/
├── index.html
├── package.json
├── tsconfig.json
├── vite.config.ts
├── public/
├── src/
│   ├── main.ts
│   ├── counter.ts
│   ├── style.css
│   └── assets/
└── README.md
```

## Nota
Este proyecto representa la base inicial de un entorno frontend, ideal para comenzar a desarrollar aplicaciones con TypeScript y Vite.
