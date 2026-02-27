REST API Best Practices — Roadmap + Free Resources
Phase 1 — REST & HTTP Foundations
1. REST Principles

Learn:

Statelessness

Resource-based URLs

Client–server separation

Uniform interface

Resources:

RESTful API Design (Microsoft)
https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design

What is REST (freeCodeCamp)
https://www.freecodecamp.org/news/rest-api-design-best-practices-build-a-rest-api/

2. HTTP Methods & Status Codes

Learn:

GET, POST, PUT, PATCH, DELETE

Idempotency

Proper status codes (200, 201, 204, 400, 401, 403, 404, 429, 500)

Resources:

MDN HTTP Methods
https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods

MDN HTTP Status Codes
https://developer.mozilla.org/en-US/docs/Web/HTTP/Status

Phase 2 — Resource-Oriented Design
3. URL Structure Best Practices

Learn:

Nouns, not verbs

Plural resource naming

Nested resources

Query parameters

Resources:

REST Naming Conventions
https://restfulapi.net/resource-naming/

Google API Design Guide
https://cloud.google.com/apis/design

4. Query Parameters & Filtering

Learn:

Pagination (?page=, ?limit=)

Filtering (?status=active)

Sorting (?sort=createdAt)

Resources:

Pagination Best Practices
https://nordicapis.com/restful-api-pagination-best-practices/

Phase 3 — Response & Error Design
5. Consistent Response Structure

Learn:

Standard success format

Standard error format

Metadata inclusion

Resources:

JSON API Spec (for structure ideas)
https://jsonapi.org/format/

6. Error Handling Strategy

Learn:

Centralized error middleware

Meaningful error messages

Avoid leaking internal details

Resources:

Express Error Handling
https://expressjs.com/en/guide/error-handling.html

Phase 4 — Versioning & Evolution
7. API Versioning

Learn:

URL versioning (/v1/)

Backward compatibility

Deprecation strategy

Resources:

API Versioning Guide
https://restfulapi.net/versioning/

Phase 5 — Security & Stability
8. Rate Limiting

Learn:

Per-IP limiting

Per-user limiting

Handling 429 responses

Resources:

express-rate-limit
https://github.com/express-rate-limit/express-rate-limit

9. CORS & Security Headers

Learn:

CORS configuration

Secure headers

Basic API hardening

Resources:

CORS Middleware
https://github.com/expressjs/cors

Helmet
https://helmetjs.github.io/

Phase 6 — Documentation & Testing
10. API Documentation

Learn:

OpenAPI (Swagger)

Postman documentation

Resources:

Swagger OpenAPI
https://swagger.io/specification/

Postman Learning Center
https://learning.postman.com/

11. API Testing

Learn:

Postman testing

Automated API tests

Integration testing basics

Resources:

Postman Docs
https://learning.postman.com/docs/

Supertest (Node testing)
https://github.com/visionmedia/supertest

Phase 7 — Production Patterns (Advanced)
12. Async Processing

Learn:

Job-based endpoints

Long-running task patterns

Polling vs Webhooks

Resources:

REST Long-Running Tasks
https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design#long-running-operations

13. Idempotency Keys

Learn:

Prevent duplicate POST operations

Retry-safe APIs

Resource:

Idempotency Explained
https://stripe.com/docs/idempotency

Execution Order

Master HTTP methods + status codes

Design clean resource-based URLs

Implement pagination + filtering

Standardize responses + errors

Add versioning

Add rate limiting + CORS + Helmet

Document with OpenAPI

Add async job-based endpoints

Implement idempotency
