# Sprint Goal
Sprint Goal: Implement basic login functionality.

# Mini-ADR
Decision: Use PostgreSQL
Reason: Reliable transactions
Consequence: Improved data consistency

# Mini-API Description
Endpoint: POST /login
Request: { email, password }
Success: 200 OK
Fail: 401 Unauthorized
Description: Authenticates a user
