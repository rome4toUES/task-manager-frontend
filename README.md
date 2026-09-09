# Configuración del entorno frontend y creación del primer proyecto

## Nombre del estudiante
Roman Alvarado Morales

## Descripción breve del proyecto
Este proyecto es una aplicación frontend desarrollada con TypeScript y Vite para explorar una colección local de GIFs. Incluye un modelo tipado, una galería y un formulario de búsqueda.

## Funcionalidades actuales
- Representación tipada de GIFs.
- Galería generada desde un arreglo local.
- Búsqueda por título, autor y etiqueta sin que los espacios afecten la consulta.
- Visualización del detalle de cada GIF.
- Botón para cerrar cada resultado y regresar a la pantalla principal.
- Manejo del caso sin resultados.

## Estado del proyecto
EC1 F1 A2 completada. Los datos aún son locales; la integración con Giphy API se realizará después.

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
├── pnpm-lock.yaml
├── tsconfig.json
├── public/
├── src/
│   ├── main.ts
│   ├── counter.ts
│   ├── models/
│   │   └── gif.interface.ts
│   ├── styles/
│   │   └── style.css
│   └── assets/
├── preguntas
└── README.md
```

## Flujo de uso
1. Escribe un título, autor o etiqueta en el buscador y selecciona `Buscar`.
2. Selecciona `Ver detalle` para consultar la información completa de un GIF.
3. Selecciona `Cerrar` para limpiar la búsqueda, cerrar el detalle y regresar a la pantalla principal.

## Nota
Este proyecto representa la base inicial de un entorno frontend para desarrollar aplicaciones con TypeScript y Vite. Actualmente utiliza datos locales; la integración con Giphy API se realizará después.
