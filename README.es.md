# Julián Contreras

[English](README.md) · **Español**

**Desarrollador Laravel y AWS · De PHP heredado a serverless · Integraciones y automatización**

Ingeniero de sistemas con máster en DevOps (UNIR), en Colombia (UTC−5). Modernizo sistemas backend: llevo PHP heredado a Laravel en AWS, conecto sistemas que nunca se pensaron para hablar entre sí y construyo procesos por lotes que siguen funcionando cuando algo falla a las 3 de la mañana.

Disponible para trabajo freelance y por contrato, en español o en inglés.

## Proyectos destacados

| Proyecto | Qué demuestra | Stack |
|---|---|---|
| [laravel-serverless-aws](https://github.com/JulianContreras02/laravel-serverless-aws) | Una API para acortar enlaces con estadísticas de clics, hecha como referencia para llevar PHP heredado a serverless. Corre en AWS Lambda con Bref; la infraestructura está en Terraform y se despliega con GitHub Actions por OIDC, sin llaves de AWS guardadas. | Laravel · Bref · Lambda · RDS · Terraform |
| [laravel-resilient-batch-jobs](https://github.com/JulianContreras02/laravel-resilient-batch-jobs) | Procesos por lotes que sobreviven a caídas y a APIs inestables: marca de agua idempotente, mutex en MySQL, una máquina de estados que se recupera sola y jobs seguros frente a `retry_after`, probados con casos de peor caso de 100.000 filas. | Laravel · MySQL · Colas · Pest |
| [laravel-integrations-kit](https://github.com/JulianContreras02/laravel-integrations-kit) | Patrones de integración entre sistemas: cliente OAuth2 con caché de token a prueba de estampidas, exportación de XLSX a S3 en streaming, entrega idempotente por SFTP con reintentos y correos que cambian a enlaces firmados cuando el adjunto es demasiado grande. | Laravel · S3 · SFTP · OAuth2 · Docker |
| [laravel-pdf-toolkit](https://github.com/JulianContreras02/laravel-pdf-toolkit) | **Pliego**, una caja de herramientas PDF autoalojada: unir, separar, comprimir, rotar y convertir en un worker de Ghostscript/qpdf aislado de la red. Los archivos se borran solos. | Laravel · Inertia · React · Ghostscript |
| [cv-builder](https://github.com/JulianContreras02/cv-builder) | Un editor de hojas de vida gratuito y privado que funciona por completo en el navegador: tres plantillas, exportación a PDF, en español y en inglés. Sin registro y sin tarjeta de crédito. **[Demo en vivo](https://juliancontreras02.github.io/cv-builder/)** | JavaScript puro · GitHub Pages |
| [invoice-reminders](https://github.com/JulianContreras02/invoice-reminders) | Recordatorios de cobro sobre facturas en MongoDB: envía un correo a cada cliente y solo pasa la factura al siguiente paso cuando el envío fue aceptado. | .NET 10 · React · MongoDB · Docker |
| [GameShelf](https://github.com/JulianContreras02/GameShelf) | Una app nativa de iOS que reúne en un solo lugar la biblioteca de juegos de Steam, PlayStation, Epic y Xbox. | Swift · SwiftUI · SwiftData |

## En proyectos reales he

- Migrado un sistema PHP heredado a una plataforma modular en Laravel 11 sobre AWS Lambda (Bref) y EC2, con frontend en React 18.
- Automatizado un proceso de reporte regulatorio que antes era manual (unas 1.200 operaciones al año), con una tabla de control idempotente, un mutex por cliente, empaquetado de PDF con tope de tamaño y trazabilidad para auditoría.
- Probado un reporte trimestral con 100.000 registros de peor caso antes de salir a producción.
- Rehecho robots de Selenium sobre una base Template Method, con verificación contra la base de datos y un watchdog.
- Agregado recuperación automática de errores a cinco procesos programados de pagos.

## Cómo trabajo

- Primero planeo, después construyo, y mantengo el alcance acotado.
- Pruebo con datos reales y con el peor caso antes de publicar.
- CI en cada push, y cada decisión documentada con su porqué.

## Stack

PHP · Laravel · MySQL · AWS (Lambda, S3, SES, RDS, EC2) · Terraform · Docker · GitHub Actions · React · TypeScript · .NET · Swift
