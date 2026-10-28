# User Story Template

## User Story

**As a** [type of user],

**I need** [a feature or capability],

**So that** [the benefit or value].

## Assumptions

- [List the assumptions related to the user story.]
- [Identify any dependencies or constraints.]

## Acceptance Criteria

```gherkin
Given [a starting condition]
When [an action occurs]
Then [the expected result]
```

## Example User Story

**As a** developer,

**I need** to automate continuous integration checks,

**So that** code changes can be tested automatically before being merged.

### Assumptions

- The project is hosted on GitHub.
- GitHub Actions is used to automate the checks.

### Acceptance Criteria

```gherkin
Given the CI workflow is configured
When code is pushed to the main branch
Then the automated checks run and report their status
```
