### Hi, I'm Mohattab — Backend Developer

I build backend systems and APIs with Node.js/TypeScript, focused on clean
architecture, databases, and production-readiness.

**Backend stack:** Node.js · TypeScript · JavaScript · NestJS · Express ·
PostgreSQL · Prisma · MongoDB · JWT · Docker · GitHub Actions (CI) ·
Jest · Supertest · Swagger/OpenAPI · Socket.IO

## Featured projects

**[`ecommerce-backend`](https://github.com/mohatab/ecommerce-backend)**
An e-commerce backend built incrementally, phase by phase, with NestJS,
TypeScript (strict), PostgreSQL/Prisma, and Docker. Foundation phase is done —
config validation, health checks, pagination primitives, a full CI pipeline
(lint, build, unit + e2e tests against a real Postgres instance, Docker image
build), and Swagger docs. Authentication and the core domain (products,
orders, payments) are the next phases in progress.

**[`recruitment-investment-api`](https://github.com/mohatab/recruitment-investment-api)**
A Node.js/Express + MongoDB REST API combining a recruitment platform (job
postings, CV-based applications) with an investor–startup management system.
JWT authentication, Stripe payments, and real-time notifications/chat over
Socket.IO, documented with Swagger/OpenAPI. Jest/Supertest test suite and a
GitHub Actions CI pipeline.

## Engineering focus

- **API design** — REST endpoints documented with Swagger/OpenAPI
- **Authentication** — JWT-based auth (implemented in `recruitment-investment-api`)
- **Database design** — relational schema with Prisma/PostgreSQL, and
  MongoDB/Mongoose models
- **Validation** — `class-validator` DTOs (NestJS), Joi schemas
- **Error handling** — structured global exception filters / centralized
  error middleware, consistent JSON error responses
- **Testing** — Jest unit/e2e tests against a real database (`ecommerce-backend`),
  Jest + Supertest smoke tests (`recruitment-investment-api`)
- **CI / GitHub Actions** — automated lint, build, and test pipelines on every push
- **Real-time** — Socket.IO for live notifications and chat
- **Containerization** — Docker / Docker Compose
