# Coding

## Debug systematically

```text
Help me diagnose this issue. Expected behavior: [EXPECTED]. Actual behavior: [ACTUAL]. Environment: [VERSIONS]. Relevant code and error: [CODE AND ERROR]. List plausible causes in order, suggest the smallest checks to distinguish them, and propose a fix with a test. State assumptions; do not claim to have run anything you cannot run.
```

## Review a change

```text
Review this change for correctness, security, maintainability, and missing tests: [DIFF]. Focus on actionable problems introduced by the change. For each finding, explain the trigger, impact, and suggested fix. If context is insufficient, identify what you need.
```

## Plan an implementation

```text
I need to implement [FEATURE] in [SYSTEM]. Constraints: [CONSTRAINTS]. Propose a small implementation plan, identify trade-offs and edge cases, and suggest meaningful verification. Ask about any missing detail that would change the design.
```

## Design meaningful tests

```text
Design tests for [BEHAVIOR OR CODE]. The expected contract is [REQUIREMENTS]; the environment is [LANGUAGE AND TEST FRAMEWORK]. Identify high-value normal, boundary, and failure cases, including relevant security or concurrency cases. Provide example tests that check observable behavior and explain any assumptions. Do not claim to have run them.
```

## Explain unfamiliar code

```text
Explain this code to someone familiar with [BACKGROUND]: [CODE]. Describe its purpose, inputs, outputs, control flow, and important side effects. Walk through a small example and identify potential failure points. Mark anything that depends on code or configuration not provided.
```
