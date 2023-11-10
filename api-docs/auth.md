---
layout: default
title: Authorization
permalink: /auth/
---

# Authorization

All API requests require the use of an Authenticated API key which should be provided in the header.

## Request URL

```bash
--header 'x-authenticated-api-key: {api_key}'
```

| Parameter | In | Type | Required |
| :--- | :--- | :--- | :--- |
| x-authenticated-api-key | header | string | true |

## Responses

| Status Code | Meaning | Description | 
| :--- | :--- |:--- |
| 200 | OK | Success |
| 401 | UNAUTHORIZED | Api Key is missing or invalid |
| 500 | INTERNAL SERVER ERROR | Something went wrong |


