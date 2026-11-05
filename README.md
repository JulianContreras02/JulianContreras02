# Julián Contreras

**English** · [Español](README.es.md)

**Laravel & AWS Developer · Legacy PHP → Serverless · Integrations & Automation**

Systems engineer with an MSc in DevOps (UNIR), based in Colombia (UTC−5). I modernize backend systems: I move legacy PHP to Laravel on AWS, connect systems that were never meant to talk to each other, and build batch processes that keep working when something fails at 3 a.m.

Available for freelance and contract work. I work in English and Spanish (*también trabajo en español*).

## Featured projects

| Project | What it shows | Stack |
|---|---|---|
| [laravel-serverless-aws](https://github.com/JulianContreras02/laravel-serverless-aws) | A URL shortener API with click analytics, built as a reference for moving legacy PHP to serverless. Runs on AWS Lambda with Bref; infrastructure in Terraform and deploys through GitHub Actions with OIDC (no stored AWS keys). | Laravel · Bref · Lambda · RDS · Terraform |
| [laravel-resilient-batch-jobs](https://github.com/JulianContreras02/laravel-resilient-batch-jobs) | Batch processing that survives crashes and flaky APIs: idempotent watermark, MySQL mutex, a self-healing state machine and `retry_after`-safe jobs, tested with 100,000-row worst cases. | Laravel · MySQL · Queues · Pest |
| [laravel-integrations-kit](https://github.com/JulianContreras02/laravel-integrations-kit) | System integration patterns: OAuth2 client credentials with a stampede-safe token cache, streamed XLSX export to S3, idempotent SFTP delivery with retries, and email that switches to signed links when attachments get too big. | Laravel · S3 · SFTP · OAuth2 · Docker |
| [laravel-pdf-toolkit](https://github.com/JulianContreras02/laravel-pdf-toolkit) | **Pliego**, a self-hosted PDF toolkit: merge, split, compress, rotate and convert in a network-isolated Ghostscript/qpdf worker. Files delete themselves. | Laravel · Inertia · React · Ghostscript |
| [cv-builder](https://github.com/JulianContreras02/cv-builder) | A free, private resume builder that runs entirely in the browser: three templates, PDF export, Spanish and English. No sign-up, no credit card. **[Live demo](https://juliancontreras02.github.io/cv-builder/)** | Vanilla JavaScript · GitHub Pages |
| [invoice-reminders](https://github.com/JulianContreras02/invoice-reminders) | Payment reminders over invoices in MongoDB: it emails each customer and only moves the invoice to the next step when the email is accepted. | .NET 10 · React · MongoDB · Docker |
| [GameShelf](https://github.com/JulianContreras02/GameShelf) | A native iOS app that brings a game library from Steam, PlayStation, Epic and Xbox into one place. | Swift · SwiftUI · SwiftData |

## In production work I have

- Migrated a legacy PHP system to a modular Laravel 11 platform on AWS Lambda (Bref) and EC2, with a React 18 front end.
- Automated a regulatory submission process that used to be manual (about 1,200 operations a year), with an idempotent control table, a per-client mutex, size-capped PDF packaging and an audit trail.
- Load-tested a quarterly report against 100,000 worst-case records before release.
- Rebuilt Selenium robots on a Template Method base with database checks and a watchdog.
- Added automatic error recovery to five payment cron jobs.

## How I work

- Plan first, then build, and keep the scope tight.
- Test with real data and the worst case before shipping.
- CI on every push, and every decision documented with its reason.

## Stack

PHP · Laravel · MySQL · AWS (Lambda, S3, SES, RDS, EC2) · Terraform · Docker · GitHub Actions · React · TypeScript · .NET · Swift
