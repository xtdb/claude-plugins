# XTDB Claude Code Plugins

Plugin marketplace for [Claude Code](https://docs.anthropic.com/en/docs/claude-code), maintained by the XTDB team.

## Installation

```
/plugin marketplace add xtdb/claude-plugins
/plugin install gradle-tests
```

## Plugins

- **gradle-tests** — specialized Gradle test runner that relays test failures without the build cruft.
  Delegates `./gradlew` execution and returns stack traces, assertion diffs and captured output verbatim, with Gradle's build scaffolding stripped, so the parent agent stays focused on diagnosis and fixes.
  Works in any Gradle project.
