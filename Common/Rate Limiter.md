**Standards:**

RFCs:

X-RateLimit-Limit - configured rate limit (constant).
X-RateLimit-Remaining - number of remaining tokens in current interval.
X-RateLimit-Reset - UTC time when the limit resets.
Retry-After - Time at which to retry

**Samples:**
1. https://github.com/sethvargo/go-limiter
