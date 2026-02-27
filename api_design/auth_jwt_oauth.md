Authentication — JWT & OAuth Roadmap (With Free Resources)
Phase 1 — Foundations
1. HTTP, Cookies, Sessions

Learn:

Stateless HTTP

Cookies (HttpOnly, Secure, SameSite)

Sessions vs Tokens

Resources:

MDN HTTP Overview
https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview

MDN Cookies
https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies

2. Password Hashing

Learn:

Hashing vs Encryption

bcrypt

Salting

Password verification flow

Resources:

bcrypt npm
https://www.npmjs.com/package/bcrypt

Net Ninja – Password Hashing (YouTube search)
https://www.youtube.com/results?search_query=net+ninja+bcrypt

Phase 2 — JWT (Core Skill)
3. JWT Fundamentals

Learn:

JWT structure (Header.Payload.Signature)

Base64 encoding

HMAC vs RSA

Signing vs encryption

Token expiration

Resources:

JWT Debugger
https://jwt.io

freeCodeCamp JWT Guide
https://www.freecodecamp.org/news/jwt-authentication-tutorial/

4. Implement JWT (Node + Express)

Learn:

jsonwebtoken library

Creating access tokens

Verifying tokens

Middleware protection

Expiry strategy

Resources:

jsonwebtoken npm
https://www.npmjs.com/package/jsonwebtoken

Express Middleware Docs
https://expressjs.com/en/guide/using-middleware.html

Phase 3 — Refresh Token Architecture

Learn:

Access token vs Refresh token

Token rotation

Secure cookie storage

Logout invalidation

Token revocation

Resources:

JWT Refresh Token Flow (YouTube search)
https://www.youtube.com/results?search_query=jwt+refresh+token+node+express

OWASP JWT Cheat Sheet
https://cheatsheetseries.owasp.org/cheatsheets/JSON_Web_Token_for_Java_Cheat_Sheet.html

Phase 4 — OAuth 2.0
5. OAuth Fundamentals

Learn:

Authorization Code Flow

Client ID / Client Secret

Redirect URI

Scopes

Access token vs ID token

Grant types

Resources:

OAuth 2.0 Simplified
https://aaronparecki.com/oauth-2-simplified/

OAuth 2.0 Spec
https://oauth.net/2/

6. Implement OAuth Login

Learn:

Google OAuth setup

GitHub OAuth setup

Callback handling

Creating local user after OAuth

Issuing your own JWT after OAuth login

Resources:

Passport.js
https://www.passportjs.org/

Auth.js (NextAuth)
https://authjs.dev/

Google OAuth Docs
https://developers.google.com/identity/protocols/oauth2

Phase 5 — Authorization (Access Control)
7. Role-Based Access Control (RBAC)

Learn:

Roles (admin, user, premium)

Middleware-based role checks

Permission mapping

Resources:

RBAC Guide (YouTube search)
https://www.youtube.com/results?search_query=rbac+node+express

OWASP Access Control
https://owasp.org/www-project-top-ten/

Phase 6 — Security Hardening

Learn:

Token storage best practices

XSS basics

CSRF basics

Rate limiting

Secure headers (Helmet)

CORS configuration

Resources:

OWASP Top 10
https://owasp.org/www-project-top-ten/

Helmet
https://helmetjs.github.io/

express-rate-limit
https://github.com/express-rate-limit/express-rate-limit

CORS Middleware
https://github.com/expressjs/cors

Phase 7 — Production-Level Patterns

Learn:

Centralized auth service pattern

Microservice token verification

Logging failed logins

Brute-force protection

Token blacklisting (Redis)

Resources:

Redis Docs
https://redis.io/docs/

Node Logging (Pino)
https://getpino.io/#/

Execution Order

Password hashing with bcrypt

Basic JWT login system

Protected routes with middleware

Add refresh token system

Add logout + token invalidation

Add RBAC

Add rate limiting + Helmet

Implement Google OAuth

Issue JWT after OAuth login

Add Redis-backed token blacklist
