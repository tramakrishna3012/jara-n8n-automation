# Retry Policy

- Retry transient HTTP errors (429, 502, 503, 504).
- Use exponential backoff (e.g., 5s, 15s, 45s).
- Cap retries to 3 attempts per request.
- Log and alert on final failure.
