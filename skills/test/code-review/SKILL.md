---
name: code-review
description: Perform a thorough code review following the team checklist. Use when reviewing code changes, pull requests, or when the user asks for a code review.
---

# Code Review Checklist

When reviewing code, evaluate every item in this checklist and provide a structured report.

## Review Process

1. **Read the diff** — Understand what changed and why
2. **Check each category** — Go through every section below
3. **Rate severity** — Flag issues as Critical, Warning, or Suggestion
4. **Summarize** — Provide an overall assessment

## Checklist Categories

### Correctness
- Does the logic handle edge cases?
- Are error paths handled properly?
- Could any input cause unexpected behavior?

### Security
- Is user input validated and sanitized?
- Are there any SQL injection, XSS, or CSRF risks?
- Are secrets hardcoded anywhere?

### Performance
- Are there unnecessary database queries or API calls?
- Could any loop cause O(n^2) or worse performance?
- Are large datasets paginated?

### Maintainability
- Are functions and variables named clearly?
- Is the code DRY (Don't Repeat Yourself)?
- Would a new team member understand this code?

### Testing
- Are there tests for the new code?
- Do tests cover edge cases and error paths?
- Are tests deterministic (no flaky tests)?

## Output Format

Structure your review as:

### Summary
[One-paragraph overall assessment]

### Critical Issues
[Must fix before merging]

### Warnings
[Should fix, but not blocking]

### Suggestions
[Nice to have improvements]

### Approved?
[YES / NO / YES WITH CONDITIONS]
