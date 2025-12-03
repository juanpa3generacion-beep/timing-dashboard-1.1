# Sistema de Cronometraje - Instrucciones de Instalación

Este archivo contiene todos los pasos necesarios para crear el proyecto desde cero.

## Paso 1: Crear el proyecto Next.js

\`\`\`bash
npx create-next-app@latest timing-dashboard
\`\`\`

Cuando te pregunte:
- TypeScript: Yes
- ESLint: Yes
- Tailwind CSS: Yes
- src/ directory: No
- App Router: Yes
- Turbopack: Yes
- Customize import alias: No

## Paso 2: Estructura de carpetas

Crea la siguiente estructura:
\`\`\`
timing-dashboard/
├── app/
│   ├── page.tsx
│   ├── layout.tsx
│   └── globals.css
├── components/
│   └── ui/
│       ├── button.tsx
│       ├── card.tsx
│       ├── input.tsx
│       └── label.tsx
├── lib/
│   └── utils.ts
├── public/
│   └── manifest.json
├── package.json
├── tsconfig.json
├── next.config.mjs
└── postcss.config.mjs
\`\`\`

## Paso 3: Instalar dependencias

Copia el contenido de package.json de este ZIP y ejecuta:
\`\`\`bash
npm install
\`\`\`

## Paso 4: Copiar archivos

Copia todos los archivos de este ZIP a tu proyecto, respetando la estructura de carpetas.

## Paso 5: Ejecutar localmente

\`\`\`bash
npm run dev
\`\`\`

Abre http://localhost:3000

## Paso 6: Desplegar en Vercel

1. Sube el código a GitHub
2. Ve a vercel.com
3. Importa tu repositorio
4. Despliega

## Paso 7: Instalar en tu celular

1. Abre la URL de Vercel en Chrome en Android
2. Toca el botón "Instalar App" o usa el menú de Chrome
3. La app se instalará como una aplicación nativa

## Notas importantes

- El Bluetooth Web API solo funciona en Chrome en Android
- Necesitas un dispositivo ESP32 configurado para enviar datos por Bluetooth
- Los datos se guardan en localStorage del navegador
