# GitHub Advanced Security (GHAS) Summary

## Code Scanning
Automated analysis of code to identify security vulnerabilities and coding errors during development. Uses static analysis (SAST) to scan code as it's written.

## Secret Scanning
Scans repositories for accidentally committed secrets like API keys, passwords, and tokens. Prevents sensitive data exposure by alerting developers and automatically revoking exposed secrets.

## Dependency Review
Analyzes project dependencies for known vulnerabilities, checking your dependency graph against security advisories.

## Shift-Left Security Importance
Shift-left means addressing security earlier in the development lifecycle. This is important because:
- Fixing security issues early is cheaper and faster
- Reduces risk of vulnerabilities reaching production
- Creates security awareness among developers
- Enables continuous security in CI/CD pipelines
