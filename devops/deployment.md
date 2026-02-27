Deployment — Roadmap + Free Resources
Phase 1 — Deployment Fundamentals
1. How Deployment Actually Works

Learn:

Build → Package → Ship → Run

Server vs Serverless

IaaS vs PaaS

Runtime environments

Resources:

AWS Cloud Basics
https://aws.amazon.com/what-is-cloud-computing/

Azure Cloud Concepts
https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/get-started/

2. Linux Basics (Non-Negotiable)

Learn:

SSH

File system navigation

Permissions

Process management

Basic bash commands

Resources:

Linux Journey
https://linuxjourney.com/

DigitalOcean Linux Guide
https://www.digitalocean.com/community/tutorials

Phase 2 — Node App Deployment (Beginner → Intermediate)
3. Deploy Without Docker (Basic Hosting)

Learn:

Deploying to:

Render

Railway

Vercel (for Next.js)

Environment variables

Build commands

Resources:

Render Docs
https://render.com/docs

Railway Docs
https://docs.railway.app/

Vercel Docs
https://vercel.com/docs

4. Environment Configuration

Learn:

.env management

Production vs development configs

Secure secret storage

Resources:

12 Factor App
https://12factor.net/config

dotenv
https://github.com/motdotla/dotenv

Phase 3 — Docker-Based Deployment (Professional Standard)
5. Dockerizing Your App

Learn:

Writing Dockerfile

Multi-stage builds

.dockerignore

Exposing ports

Running containers

Resources:

Docker Docs
https://docs.docker.com/get-started/

Docker Node Guide
https://docs.docker.com/language/nodejs/

6. Docker Compose (Multi-Service Setup)

Learn:

docker-compose.yml

Running app + Redis

Running app + database

Resources:

Docker Compose Docs
https://docs.docker.com/compose/

Phase 4 — Production Server Deployment (Serious Level)
7. VPS Deployment (Manual)

Learn:

Buy VPS (DigitalOcean / AWS EC2)

SSH into server

Install Node & Nginx

Reverse proxy setup

Firewall basics

Resources:

DigitalOcean VPS Guide
https://www.digitalocean.com/community/tutorials

NGINX Reverse Proxy Guide
https://docs.nginx.com/nginx/admin-guide/web-server/reverse-proxy/

8. Process Management

Learn:

PM2

Restart policies

Log management

Resources:

PM2 Docs
https://pm2.keymetrics.io/

Phase 5 — Advanced Production Concepts
9. Reverse Proxy & Load Balancing

Learn:

What NGINX does

SSL termination

HTTP → HTTPS redirect

Load balancing basics

Resources:

NGINX Docs
https://nginx.org/en/docs/

Let’s Encrypt (Free SSL)
https://letsencrypt.org/

10. Horizontal Scaling

Learn:

Stateless backend design

Multiple instances

Load balancer

Sticky sessions

Resources:

AWS Load Balancer Guide
https://docs.aws.amazon.com/elasticloadbalancing/

11. Health Checks

Learn:

/health endpoint

Readiness vs liveness

Auto-restart strategies

Resources:

Health Check Pattern
https://microservices.io/patterns/observability/health-check-api.html

Phase 6 — Container Orchestration (Advanced)
12. Kubernetes Basics (Optional Advanced)

Learn:

Pods

Services

Deployments

Scaling

ConfigMaps & Secrets

Resources:

Kubernetes Basics
https://kubernetes.io/docs/tutorials/kubernetes-basics/

Kubernetes Docs
https://kubernetes.io/docs/home/

Phase 7 — ML-Specific Deployment Patterns
13. Separate Services

Learn:

API service

Model inference service

Queue worker

Redis cache

Resource:

Docker Microservices Guide
https://docs.docker.com/compose/

14. Async Job-Based Inference

Learn:

Background workers

Queue systems (BullMQ / Redis)

Polling endpoints

Resources:

BullMQ
https://docs.bullmq.io/

Redis Docs
https://redis.io/docs/

Execution Order

Deploy Node app on Render/Railway

Manage environment variables properly

Dockerize app

Deploy Docker container

Deploy on VPS manually

Add NGINX reverse proxy

Add SSL (Let’s Encrypt)

Add PM2 for process management

Implement health checks

Add Redis + queue system

Learn basic Kubernetes
