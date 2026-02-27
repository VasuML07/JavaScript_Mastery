CI/CD — Roadmap + Free Resources
Phase 1 — Foundations
1. What CI/CD Is

Learn:

CI (Continuous Integration)

CD (Continuous Delivery vs Deployment)

Pipelines

Build → Test → Deploy flow

Resources:

GitHub Docs – CI/CD Overview
https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions

Atlassian CI/CD Guide
https://www.atlassian.com/continuous-delivery/ci-vs-cd

2. Git Mastery (Mandatory)

Learn:

Branching strategy (main, dev, feature branches)

Pull Requests

Merge conflicts

Rebase vs merge

Tags & releases

Resources:

Pro Git Book (Free)
https://git-scm.com/book/en/v2

Atlassian Git Tutorials
https://www.atlassian.com/git/tutorials

Phase 2 — GitHub Actions (Primary Tool)
3. GitHub Actions Basics

Learn:

Workflows (.github/workflows/)

YAML syntax

Jobs & steps

Triggers (push, pull_request)

Runners

Resources:

GitHub Actions Docs
https://docs.github.com/en/actions

GitHub Actions Quickstart
https://docs.github.com/en/actions/quickstart

4. Build & Test Pipeline

Learn:

Install dependencies

Run linting

Run tests

Fail builds on errors

Resources:

Node.js CI Example
https://docs.github.com/en/actions/automating-builds-and-tests/building-and-testing-nodejs

Jest Docs
https://jestjs.io/docs/getting-started

Phase 3 — Docker Integration
5. Docker Basics

Learn:

Dockerfile

Image vs container

Multi-stage builds

.dockerignore

Resources:

Docker Getting Started
https://docs.docker.com/get-started/

Docker Docs
https://docs.docker.com/

6. CI + Docker Build

Learn:

Build Docker image in pipeline

Push image to registry (Docker Hub / GHCR)

Tagging versions

Resources:

GitHub Actions Docker Guide
https://docs.github.com/en/actions/publishing-packages/publishing-docker-images

Phase 4 — Deployment Automation
7. Automated Deployment

Learn:

Deploy on push to main

Environment variables in CI

Secrets management

Staging vs production

Resources:

GitHub Secrets
https://docs.github.com/en/actions/security-guides/encrypted-secrets

Vercel Deployment Docs
https://vercel.com/docs

Render Deployment Docs
https://render.com/docs

8. Environment Management

Learn:

Separate configs (dev, staging, prod)

Secure secrets storage

Never commit .env files

Resources:

dotenv
https://github.com/motdotla/dotenv

12-Factor App
https://12factor.net/

Phase 5 — Advanced CI/CD
9. Testing Strategy in CI

Learn:

Unit tests

Integration tests

API tests

Coverage reports

Resources:

Supertest
https://github.com/visionmedia/supertest

Jest Coverage
https://jestjs.io/docs/code-coverage

10. Branch Protection Rules

Learn:

Required status checks

Required reviews

Prevent direct push to main

Resources:

GitHub Branch Protection
https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches

11. Rollbacks & Versioning

Learn:

Semantic Versioning (SemVer)

Git tags

Release workflows

Rollback strategy

Resources:

SemVer
https://semver.org/

Git Tags Guide
https://git-scm.com/book/en/v2/Git-Basics-Tagging

Phase 6 — Monitoring & Observability
12. Post-Deployment Monitoring

Learn:

Logging

Error tracking

Health checks

Uptime monitoring

Resources:

Sentry
https://sentry.io/

Health Check Pattern
https://microservices.io/patterns/observability/health-check-api.html

Execution Order

Master Git branching strategy

Create basic GitHub Actions workflow

Add build + test pipeline

Add Docker build to CI

Push image to registry

Deploy automatically on main branch

Configure secrets securely

Add branch protection rules

Add integration tests in CI

Implement version tagging + rollback strategy
