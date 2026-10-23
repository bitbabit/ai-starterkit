# Code Review Prompt

Review this change as a pragmatic senior engineer under a 24-hour deadline.

Prioritize findings in this order:
1. Correctness / data loss / broken critical workflow
2. Security, secret exposure, authorization, unsafe input, sensitive logging
3. Failure handling, timeouts, retries, resource leaks
4. Performance issues that matter for expected usage
5. Maintainability, SOLID boundaries, duplicated logic
6. Style and polish

For every finding, provide severity, file/line if available, concrete failure scenario, and the smallest useful fix. Separate verified bugs from concerns or suggestions. Do not invent line numbers. Avoid requesting broad refactors unrelated to the change. End with a short ship/block recommendation and the tests needed.
