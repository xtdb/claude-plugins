# XTDB Claude Code Plugins

Plugin marketplace for [Claude Code](https://docs.anthropic.com/en/docs/claude-code), maintained by the XTDB team.

## Installation

```
/plugin marketplace add xtdb/claude-plugins
/plugin install gradle-tests
```

## Plugins

- **gradle-tests** — specialized Gradle test runner and failure-report parser.
  Delegates `./gradlew` execution and HTML report parsing so the parent agent stays focused on diagnosis and fixes.
  Works in any Gradle project.
