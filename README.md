Proyecto de automatización QA enfocado en validar flujos funcionales clave de una aplicación web y endpoints API, utilizando Playwright bajo una arquitectura basada en Page Object Model (POM).

Se diseñaron y ejecutaron pruebas tanto de interfaz de usuario (UI) como de servicios (API), cubriendo escenarios positivos y negativos para asegurar el comportamiento correcto del sistema.

🧩 Qué se hizo
Análisis de flujos principales (login y consumo de API)
Diseño de casos de prueba funcionales
Implementación de pruebas automatizadas UI
Validación de endpoints API (status, estructura y datos)
Uso de datos de prueba separados para mayor mantenibilidad
Generación de evidencia mediante reportes HTML
🧪 Cobertura de pruebas
UI
Login exitoso
Login con credenciales inválidas
API
Consulta de lista de usuarios
Consulta de usuario por ID
🛠️ Tecnologías
Playwright
JavaScript
Node.js
🎯 Objetivo

Demostrar habilidades base en QA Automation, incluyendo:

validación funcional
estructuración de pruebas
ejecución automatizada
generación de evidencia

- Pruebas UI
- Pruebas API
- Estructura Page Object Model
- Reporte HTML
- Screenshots y video en fallos

## Requisitos

- Node.js 18 o superior

## Instalación

```bash
npm install
npx playwright install
```

## Ejecutar pruebas

### Todas
```bash
npm test
```

### Solo UI
```bash
npm run test:ui
```

### Solo API
```bash
npm run test:api
```

### Ver navegador abierto
```bash
npm run test:headed
```

### Abrir reporte
```bash
npm run report
```

## Estructura

```bash
qa-playwright-starter/
├── pages/
│   └── LoginPage.js
├── tests/
│   ├── api/
│   │   └── users.spec.js
│   └── ui/
│       └── login.spec.js
├── utils/
│   └── testData.js
├── playwright.config.js
├── package.json
└── README.md
```

## Qué valida

### UI
- Login exitoso
- Login fallido

### API
- Consulta de lista de usuarios
- Consulta de usuario por ID




