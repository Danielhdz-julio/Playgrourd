# Proyecto QA listo – Playwright

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

## Buenas prácticas incluidas

- Page Object Model
- Datos de prueba separados
- Casos positivos y negativos
- Assertions claras


