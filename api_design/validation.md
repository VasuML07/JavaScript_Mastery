API Validation — Roadmap + Free Resources
Phase 1 — Foundations
1. HTTP & Request Structure

Learn:

req.body

req.params

req.query

Status codes (400, 422)

Resources:

MDN HTTP Overview
https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview

Express Request Object
https://expressjs.com/en/5x/api.html#req

2. Basic Input Validation Concepts

Learn:

Required fields

Type checking

Range validation

Enum validation

Resource:

freeCodeCamp – Node.js API Validation
https://www.freecodecamp.org/news/how-to-validate-express-requests/

Phase 2 — Schema Validation (Core Skill)
3. Zod (Recommended for TypeScript)

Learn:

z.object()

z.string(), z.number()

.min(), .max()

.refine()

safeParse()

Custom errors

Resources:

Official Docs
https://zod.dev

Zod GitHub
https://github.com/colinhacks/zod

YouTube – Zod Crash Course
https://www.youtube.com/results?search_query=zod+crash+course

4. Joi (Alternative)

Learn:

Joi.object()

Schema validation

Middleware usage

Resources:

Official Docs
https://joi.dev

Joi GitHub
https://github.com/hapijs/joi

Phase 3 — Express Middleware Validation

Learn:

Custom validation middleware

Centralized error handling

Validation before controller logic

Resources:

Express Middleware Guide
https://expressjs.com/en/guide/using-middleware.html

Central Error Handling (YouTube)
https://www.youtube.com/results?search_query=express+central+error+handling

Phase 4 — File & Payload Validation (Critical for ML APIs)

Learn:

File upload validation (Multer)

MIME type checking

File size limits

JSON body size limits

Resources:

Multer Docs
https://github.com/expressjs/multer

Express Body Size Limit
https://expressjs.com/en/resources/middleware/body-parser.html

Phase 5 — Security Validation

Learn:

Input sanitization

XSS basics

SQL/NoSQL injection basics

CORS

Helmet

Resources:

OWASP Top 10
https://owasp.org/www-project-top-ten/

Helmet
https://helmetjs.github.io/

CORS Middleware
https://github.com/expressjs/cors

Phase 6 — Rate Limiting & Abuse Protection

Learn:

express-rate-limit

IP-based limiting

Redis-backed rate limiting

Resources:

express-rate-limit
https://github.com/express-rate-limit/express-rate-limit

Redis
https://redis.io/docs/

Phase 7 — Advanced Patterns

Learn:

Conditional validation

Cross-field validation

Versioned schemas

DTO pattern

Request size limits in production

Resources:

NestJS Validation (for architecture ideas)
https://docs.nestjs.com/techniques/validation

OpenAPI Spec
https://swagger.io/specification/

Practice Order (Execution Plan)

Validate simple POST body using Zod

Add middleware-based validation

Add file upload validation

Add centralized error handler

Add rate limiting

Add payload size limits

Implement cross-field validation

Secure with Helmet + CORS
