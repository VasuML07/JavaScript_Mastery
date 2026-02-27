🛡 API Validation (Production-Grade for ML Systems)
🎯 Objective

Design robust validation layers that:

Prevent malformed input

Protect ML models from abuse

Avoid server crashes

Ensure consistent data contracts

Improve security posture

By the end, you should be able to build validation pipelines that make your API resilient under hostile conditions.

🧠 Part 1 — Core Concepts
1. What Validation Really Is

Validation is:

Structural checking (shape of data)

Type checking

Constraint enforcement

Sanitization

Security filtering

It is NOT:

Just checking if field exists.

Understand:
Validation belongs at the boundary of your system.

Everything entering your API is untrusted.

2. Types of Validation

You must know the differences:

1. Schema Validation

Ensures structure matches expected format.

Example:

{
  "email": "string",
  "password": "string"
}
2. Business Logic Validation

Example:

User must be premium to run large model.

Image size must be < 5MB.

Age must be >= 18.

3. Security Validation

Example:

Block script injection

Reject suspicious payload sizes

Restrict file types

⚙ Part 2 — Schema Validation Tools (Node.js)
3. Zod (Recommended)

Learn:

z.object()

z.string().email()

z.number().min()

Safe parsing

Custom error messages

Type inference (if using TypeScript)

Why Zod is strong:

Type-safe

Clean API

Great for TS projects

Free resource:
Zod official docs + YouTube tutorials.

4. Joi (Alternative)

Learn:

Schema creation

Middleware integration

Validation options

Understand:
Joi is mature but less TypeScript-friendly.

🧱 Part 3 — Middleware-Based Validation
5. Validation Layer Architecture

Correct flow:

Request → Validation Middleware → Controller → Service → Model

Never validate inside controllers.

Separation of concerns keeps code clean.

6. Request Areas to Validate

You must validate:

req.body

req.params

req.query

Headers (sometimes)

Example:

GET /models?page=1&limit=10

Validate:

page is number

limit <= 50

Without limit checks:
Someone requests 1 million rows.

Server dies.

🤖 Part 4 — ML-Specific Validation

This is where most people fail.

7. File Upload Validation

Validate:

File type (MIME)

File extension

Max file size

Image dimensions (if needed)

Content type consistency

Never trust:

File name

Client-side checks

Example failure:
User uploads 200MB “image”.
Your inference service crashes.

8. Input Size Limits

Set:

JSON body size limit

Max request payload size

Timeout limits

In Express:

express.json({ limit: '1mb' })

Why:
Large payload = memory exhaustion attack.

9. Numerical Input Constraints

ML example:

{
  "age": 999999999,
  "income": -500000
}

Without constraints:
Model predictions become garbage.

Validate:

Ranges

Required fields

Enum values

🔐 Part 5 — Security-Focused Validation
10. Prevent Injection Attacks

Learn:

NoSQL injection basics

SQL injection basics

XSS basics

Command injection basics

Use:

Sanitization libraries

Strict schema validation

Escaping outputs

Free resource:
OWASP Top 10 (must read)

11. Rate-Based Abuse Protection

Validation isn’t only structure.

You must validate:

Too many requests

Repeated login attempts

Excessive inference calls

Use:

express-rate-limit

Redis-backed rate limiting

📦 Part 6 — Error Handling Strategy
12. Standardized Validation Errors

Return consistent structure:

{
  "status": "error",
  "message": "Validation failed",
  "errors": [
    { "field": "email", "message": "Invalid email format" }
  ]
}

Never leak:

Internal stack traces

Library error internals

Keep it clean and controlled.

🧪 Part 7 — Advanced Validation Patterns
13. Conditional Validation

Example:

If modelType = "vision", require image.

If modelType = "nlp", require text.

Schema refinement techniques matter here.

14. Cross-Field Validation

Example:

startDate must be before endDate.

minValue must be less than maxValue.

Most beginners ignore cross-field validation.

That’s how logic bugs enter production.

15. Versioned Schema Validation

When you version API:

/api/v1/predict
/api/v2/predict

Validation schemas must also evolve.

Never break older clients silently.

🧠 What Mastery Looks Like

You:

Validate at boundaries only.

Never trust client input.

Limit payload sizes.

Separate schema and business validation.

Handle file uploads safely.

Return structured error messages.

Understand OWASP risks.

Design validation as part of system architecture.

🧨 Common Beginner Mistakes

Validating only required fields.

Relying on frontend validation.

No payload size limit.

No file type check.

Throwing raw error objects.

Mixing validation and controller logic.

Ignoring edge cases.
