# Smoke Test Checklist

Run after integration and before every demo rehearsal.

- [ ] Application starts from the documented commands.
- [ ] Health/status endpoint or equivalent works, if present.
- [ ] Main user workflow completes end to end.
- [ ] Output is understandable and matches the acceptance criteria.
- [ ] Empty input is handled.
- [ ] Invalid input is handled without crashing.
- [ ] Model / external service failure is handled visibly and safely.
- [ ] No secret appears in browser output, logs, or repository.
- [ ] App can be restarted using documented steps.
- [ ] Another teammate can follow the README.
- [ ] Changes are committed and the repository is in a known state.

Record build/commit, tester, date/time, failures, and retest result.
