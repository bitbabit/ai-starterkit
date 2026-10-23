# Edge Cases

Adapt these to the actual challenge; remove irrelevant cases.

| Case | Expected behavior | Priority | Result |
|---|---|---|---|
| Empty input | Clear validation message | High | Not run |
| Malformed input | Reject safely | High | Not run |
| Very large input | Enforce limit or fail safely | High | Not run |
| Dependency timeout | Bounded wait and useful error | High | Not run |
| Dependency returns 4xx/5xx | Safe error; no secret leakage | High | Not run |
| Dependency returns malformed data | Validate before use | High | Not run |
| No data / no retrieval results | Honest empty state | Medium | Not run |
| Duplicate submission | Defined idempotency behavior | Medium | Not run |
| Refresh / restart | State behavior is understood | Medium | Not run |
| AI hallucination / unsupported claim | Clearly limit or verify output | High for AI tasks | Not run |
