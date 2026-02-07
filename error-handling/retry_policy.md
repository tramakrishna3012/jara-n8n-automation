# Retry Policy

## Recommended Defaults
- Retry transient HTTP errors: 429, 502, 503, 504.
- Use exponential backoff (e.g., 5s, 15s, 45s).
- Cap retries to 3 attempts per request.
- Log and alert on final failure.

## n8n Node Settings
- Enable "Retry On Fail" for HTTP Request nodes.
- Set "Max Tries" to 3.
- Set "Wait Between Tries" to 5000ms and use exponential backoff in the backend.
- Send error context to the global error workflow.
