# Hola, soy Jesus Jimenez 👋

Desarrollador JavaScript full-stack en etapa junior, enfocado en construir APIs seguras, aplicaciones web mantenibles y flujos transaccionales confiables.

Trabajo principalmente con **Node.js, Express, MySQL y React**. Me interesa comprender no solo cómo implementar una funcionalidad, sino también por qué una arquitectura, un patrón o una estrategia de datos resulta adecuada para cada problema.

## Proyectos destacados

### Gestor SaaS de ventas de lotería

[![CI del Gestor SaaS](https://github.com/YisusDev123/Gestor-SaaS-de-ventas-de-loteria/actions/workflows/ci.yml/badge.svg)](https://github.com/YisusDev123/Gestor-SaaS-de-ventas-de-loteria/actions/workflows/ci.yml)

SaaS multi-tenant para gestionar ventas, cajas, sorteos, resultados, reportes, usuarios y suscripciones.

Aspectos técnicos destacados:

- aislamiento de datos y autorización por tenant;
- operaciones de caja y ventas con transacciones MySQL;
- jobs idempotentes para procesos programados;
- API REST modular con validación y manejo uniforme de errores;
- frontend PWA construido con React;
- pruebas automatizadas, migraciones y CI reproducible.

[Ver repositorio](https://github.com/YisusDev123/Gestor-SaaS-de-ventas-de-loteria)

### Plataforma transaccional de apuestas

[![CI de la plataforma transaccional](https://github.com/YisusDev123/plataforma-transaccional-de-apuestas/actions/workflows/ci.yml/badge.svg)](https://github.com/YisusDev123/plataforma-transaccional-de-apuestas/actions/workflows/ci.yml)

Plataforma full-stack para gestionar usuarios, KYC, billeteras, depósitos, retiros, sorteos, apuestas y pagos automáticos.

Aspectos técnicos destacados:

- consistencia de saldos mediante transacciones y bloqueos pesimistas;
- idempotencia para evitar apuestas, movimientos o pagos duplicados;
- control de concurrencia y tratamiento de resultados inciertos;
- separación entre API, servicios, persistencia y jobs;
- autenticación, autorización por roles y validación de entradas;
- PWA con reglas conservadoras para operaciones financieras.

[Ver repositorio](https://github.com/YisusDev123/plataforma-transaccional-de-apuestas)

## Stack principal

- **Backend:** JavaScript, Node.js, Express y APIs REST.
- **Datos:** MySQL, SQL transaccional, migraciones y modelado relacional.
- **Frontend:** React, Vite, React Router, TanStack Query y Tailwind CSS.
- **Calidad:** Jest, Vitest, Testing Library, Playwright, ESLint y GitHub Actions.
- **Seguridad:** JWT, validación de entradas, rate limiting, CORS, Helmet y control de acceso por roles.

## Enfoque de ingeniería

- Mantener controladores pequeños y reglas de negocio verificables.
- Diseñar operaciones monetarias atómicas e idempotentes.
- Tratar concurrencia, timeouts y reintentos como parte del diseño.
- Evitar complejidad arquitectónica que el problema todavía no necesita.
- Documentar las decisiones técnicas y sus compensaciones.

## Actualmente aprendiendo

- selección de arquitecturas según el contexto del producto;
- observabilidad y operación de sistemas en producción;
- despliegues reproducibles y automatización de infraestructura;
- diseño de sistemas escalables sin perder claridad ni mantenibilidad.

## Contacto

Puedes revisar mi trabajo y evolución directamente en mis repositorios de GitHub.
