# CircuitBreaker
# Bulkhead
# RateLimiter

**State:**

1. Key - arbitrary user defined 
2. 

**Standards:**

RFCs:

1. X-RateLimit-Limit - configured rate limit (constant).
2. X-RateLimit-Remaining - number of remaining tokens in current interval.
3. X-RateLimit-Reset - UTC time when the limit resets.
4. Retry-After - Time at which to retry

**Samples:**
1. https://github.com/vladimir-bukhtoyarov/bucket4j
2. https://github.com/sethvargo/go-limiter

# Retry
