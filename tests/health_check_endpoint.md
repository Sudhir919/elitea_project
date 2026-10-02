# Health Check Endpoint

## Scenario

Verify that the application health endpoint returns a successful response.

## Test

- Request: `GET /health`
- Expected response: HTTP 200 with JSON response `{"status":"UP"}`
- Observed response: HTTP 200 with JSON response `{"status":"UP"}`

## Execution Result

Passed