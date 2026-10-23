# Implementation Prompt

Implement only the agreed task and acceptance criteria.

Before editing:
- Inspect the relevant code and follow existing conventions.
- Identify affected files, dependencies, interfaces, and likely risks.
- Ask if a missing contract blocks implementation; otherwise state a reasonable assumption.

While implementing:
- Make the smallest coherent change.
- Preserve backward compatibility unless the task explicitly changes it.
- Validate untrusted input and handle external dependency failures safely.
- Keep secrets out of source control and logs.
- Add focused tests for expected behavior and important edge cases.
- Do not add dependencies or architecture layers without a concrete need.

After editing, report:
1. Files changed and why.
2. Commands/tests run and actual results.
3. Manual verification steps.
4. Known limitations or untested paths.
5. Any follow-up task that is truly required.

Do not claim tests passed unless they were actually run.
