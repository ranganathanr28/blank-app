# Repository Guardrails for GitHub Copilot

## Coding Standards
- Use camelCase for variables and PascalCase for classes.
- Include error handling in all functions.
- Avoid silent failures.

## Architecture Boundaries
- Do not introduce new libraries or frameworks without explicit human approval.
- Follow the folder structure already present in the repository.
- Respect API contracts defined in /docs/api-spec.md.

## Security Requirements
- Never log secrets, tokens, or credentials.
- Validate all external inputs.
- Follow OWASP secure coding practices.

## Testing Expectations
- Every new feature must include unit tests.
- Tests must include meaningful assertions.

## Documentation Rules
- Update README or module-level docs when adding new features.

@include .github/instructions/security.md
@include .github/instructions/testing.md
@include .github/instructions/architecture.md
