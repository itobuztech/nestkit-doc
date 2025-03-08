---
title: Rate Limit
weight: 2
---
# Rate Limit 
Rate limit implemented by Nest Js ThrottlerModule

## Implementation
Rate limiting has been implemented throughout the application to enhance security and prevent brute force attacks. By limiting the number of requests a client can make within a specific time period, the system effectively prevents:

- Brute force attacks on authentication endpoints
- API abuse and scraping attempts
- Denial of Service (DoS) attacks
- Excessive resource consumption

## Configuration
The rate limiting is applied globally and can be customized per route as needed.

### Environment Variables
Rate limit default options can be customized through the following environment variables:

```
# Rate Limit
THROTTLE_TTL=60000      # Time window in milliseconds (default: 60000 ms = 60 seconds)
THROTTLE_LIMIT=50       # Maximum number of requests within the TTL window (default: 50)
RATE_LIMIT_ENABLED=true # Whether rate limiting is enabled (default: true)
```

Please check the documentation for additional customization https://docs.nestjs.com/security/rate-limiting

