# API Contracts

Write down the contract before parallel implementation.

## Endpoint / operation
- Name:
- Method / transport:
- Purpose:
- Authentication / authorization:
- Request content type:
- Timeout / rate limit:

### Request example
```json
{
  "example": "replace with actual fields"
}
```

### Response example
```json
{
  "success": true,
  "data": {}
}
```

### Error contract
| Condition | Status / code | User-safe message | Retryable? |
|---|---|---|---|
| Invalid input | | | No |
| Unauthorized | | | No |
| Dependency timeout | | | Maybe |
| Unexpected failure | | | No |

Document field types, required fields, size limits, pagination, idempotency, and versioning if relevant. Never place secrets or real personal data in examples.
