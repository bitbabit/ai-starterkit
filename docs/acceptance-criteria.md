# MVP Acceptance Criteria

The MVP is not complete until the critical user journey works end to end.

## Core workflow
- [ ] A user can complete the primary task without developer intervention.
- [ ] Expected output is shown in a useful, understandable form.
- [ ] Empty, invalid, or malformed input is handled.
- [ ] API/model/database failure has a visible, safe failure path.
- [ ] A clean setup and startup have been tested.
- [ ] Core behavior has focused automated or repeatable manual tests.
- [ ] No secrets are committed.
- [ ] Demo data is safe and allowed by event rules.
- [ ] README explains setup, configuration, run, test, limitations, and demo flow.

## Quality gate
- [ ] Another teammate can run the application from the README.
- [ ] No known blocker remains in the main user journey.
- [ ] Team agrees the MVP is stable enough to demonstrate.

## Only after all applicable boxes above are checked
Consider enhancements such as caching, RAG, performance tuning, observability, advanced security hardening, scalability, additional UI polish, or a local model. Add one enhancement at a time and re-test the core workflow.
