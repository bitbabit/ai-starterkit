# Test Engineer Prompt

Create a focused test plan for the agreed MVP and its critical user journey.

Cover:
- Main successful path
- Empty and malformed input
- Boundary values and oversized input
- Unauthorized access if applicable
- External API/model timeout and error
- Empty retrieval result / irrelevant context if using RAG
- Invalid or incomplete model output
- Duplicate requests / retry behavior where relevant
- Startup, configuration, and restart
- Regression test for each fixed bug

For each test, include ID, setup, input/action, expected result, priority, and whether it can be automated. Keep the suite small enough to run repeatedly during the hackathon. Do not assume a model response is correct merely because it is valid JSON.
