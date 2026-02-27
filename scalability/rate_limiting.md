🚀 Rate Limiting in Scalability — Complete Roadmap
1️⃣ Foundations of Rate Limiting
Topics

What is rate limiting?

Why rate limiting is needed

Abuse prevention

DoS vs DDoS (concept level)

Fair usage policies

Throughput vs latency

Backpressure basics

Resources

Rate Limiting Overview (Cloudflare)
https://www.cloudflare.com/learning/bots/what-is-rate-limiting/

AWS Throttling Concepts
https://docs.aws.amazon.com/apigateway/latest/developerguide/api-gateway-request-throttling.html

System Design Primer
https://github.com/donnemartin/system-design-primer

2️⃣ Core Algorithms (Must Master)
Topics

Fixed Window Counter

Sliding Window Log

Sliding Window Counter

Token Bucket

Leaky Bucket

Comparison of algorithms

Burst handling

Time complexity & memory tradeoffs

Resources

Rate Limiting Algorithms Explained
https://konghq.com/blog/engineering/how-to-design-a-scalable-rate-limiting-algorithm/

Token Bucket vs Leaky Bucket
https://www.geeksforgeeks.org/token-bucket-algorithm/

3️⃣ Distributed Rate Limiting
Topics

Centralized vs distributed rate limiter

Consistency challenges

Race conditions

Atomic operations

Idempotency

Clock drift issues

Horizontal scaling

Resources

Designing Distributed Rate Limiter
https://www.educative.io/courses/grokking-modern-system-design-interview/rate-limiter

Redis INCR command
https://redis.io/docs/latest/commands/incr/

4️⃣ Implementing Rate Limiting with Redis
Topics

Using INCR + EXPIRE

Lua scripting for atomicity

Token bucket in Redis

Sliding window in Redis

Handling TTL properly

Preventing race conditions

Resources

Redis Rate Limiting Pattern
https://redis.io/docs/latest/solutions/use-cases/rate-limiting/

Redis Lua Scripting
https://redis.io/docs/latest/develop/interact/programmability/eval-intro/

5️⃣ API Gateway Level Rate Limiting
Topics

Rate limiting at gateway layer

Per IP limiting

Per user limiting

Per API key limiting

Global vs per-route limits

Quotas vs throttling

Resources

NGINX Rate Limiting
https://nginx.org/en/docs/http/ngx_http_limit_req_module.html

Kong API Gateway Rate Limiting
https://docs.konghq.com/hub/kong-inc/rate-limiting/

6️⃣ Cloud-Based Rate Limiting
Topics

AWS API Gateway throttling

Cloudflare rate limits

CDN-level limiting

WAF rate limiting

Resources

AWS API Gateway Throttling
https://docs.aws.amazon.com/apigateway/latest/developerguide/api-gateway-request-throttling.html

Cloudflare Rate Limiting Docs
https://developers.cloudflare.com/waf/rate-limiting-rules/

7️⃣ Advanced Concepts
Topics

Adaptive rate limiting

Dynamic limits

User tier-based limits

Priority-based rate limiting

Distributed lock for strict consistency

Handling spikes

Graceful degradation

Circuit breaker pattern (conceptual)

Resources

Circuit Breaker Pattern
https://martinfowler.com/bliki/CircuitBreaker.html

Resilience Patterns
https://learn.microsoft.com/en-us/azure/architecture/patterns/category/resiliency

8️⃣ Monitoring & Observability
Topics

Request metrics

Rejected request count

Rate limit headers

Alerting

Load testing

Monitoring spikes

Resources

Prometheus
https://prometheus.io/docs/introduction/overview/

Grafana
https://grafana.com/docs/

k6 Load Testing
https://k6.io/docs/

9️⃣ Hands-On Projects

Build fixed window limiter

Build token bucket limiter

Implement Redis-based distributed limiter

Add rate limiting to REST API

Add tier-based limits (free vs premium)

Simulate traffic spike

Implement graceful degradation

Docker (Run Redis locally)
https://hub.docker.com/_/redis

✅ Mastery Checklist

You’re strong in rate limiting when you can:

Implement token bucket from scratch

Design distributed rate limiter

Handle race conditions safely

Scale limiter horizontally

Choose correct algorithm per use case

Prevent abuse without harming UX
