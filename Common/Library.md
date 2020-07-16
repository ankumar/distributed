# CircuitBreaker
# Bulkhead
# RateLimiter

**State:**

1. Key - arbitrary user defined 
2. 

**Standards:**

RFCs:

| Header | Description  |
| ------ | ------------ |
| X-RateLimit-Limit | how many request the client can do |
| X-RateLimit-Remaining | how many request remain to the client in the timewindow |
| X-RateLimit-Reset | how many seconds must pass before the rate limit resets |
| Retry-After | if the max has been reached, the millisecond the client must wait before perform new requests |

**Samples:**
1. https://github.com/vladimir-bukhtoyarov/bucket4j
2. https://github.com/sethvargo/go-limiter

# Retry
