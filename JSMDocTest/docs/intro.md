---
sidebar_position: 1
---

# Autenticação

A autenticação nas Api JS+ sempre requerem um Token JWT, gerado através da Api Identity.

para gerar um token JWT para autenticação nas Apis JS+ é necessário possuir um **clientId** e **clientSecret**

#### exemplo clientId e clientSecret
```json
{
 "clientId": "8c05ec01-9510-44b6-bf73-93fc46c474d4",
 "clientSecret": "_xpto-x_AAbS917i63nP"
}
```

#### exemplo de token JWT
```jwt
eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJjaWQiOiJCRTA4OUZDNS00NUZBLTQzNUItQTc2OS0wRUYzOEVGQzhENjUiLCJzZWxsZXJzIjoiOTc3YzE0OGItNzJiMC00MzU4LWJkNjctYzA0YjUzZmE3NmY0IiwidW5pcXVlX25hbWUiOiJMVk9mZmxpbmUiLCJ3ZWJzaXRlIjoiQWRtaW5BcHBsaWNhdGlvbiIsInJvbGUiOiJBZG1pbiIsIm5iZiI6MTY0NDI3MjA1MCwiZXhwIjoxNjQ0ODc2ODUwLCJpYXQiOjE2NDQyNzIwNTAsImlzcyI6InRmcDovL2lkZW50aXR5LmpzbS9hdXRob3JpdHkiLCJhdWQiOiJiYzA1MWRlMy1hZWFhLTRhYzktOGZiZi0wNWE4NmUwODNmY2YifQ.BsuVsm4TY3PlVKI6q2tKzQKU6iQoaAEA8a72NUMlHjU
```

#### exemplo da composição do token
```json
{
  "cid": "BE089FC5-45FA-435B-A769-0EF38EFC8D65",
  "sellers": "977c148b-72b0-4358-bd67-c04b53fa76f4",
  "unique_name": "LVOffline",
  "website": "AdminApplication",
  "role": "Admin",
  "nbf": 1644272050,
  "exp": 1644876850,
  "iat": 1644272050,
  "iss": "tfp://identity.jsm/authority",
  "aud": "bc051de3-aeaa-4ac9-8fbf-05a86e083fcf"
}
```