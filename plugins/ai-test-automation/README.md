# AI Test Automation Plugin

This plugin scaffold helps you replace repetitive manual testing with AI-assisted test runs.

## What this plugin can do
- Create test plans from feature requirements.
- Generate and run regression test commands.
- Summarize failures with probable root causes.
- Propose bug reports and retest checklists.

## Suggested workflow
1. Define your acceptance criteria for a feature.
2. Ask the plugin agent to generate test cases.
3. Run the generated test commands (`npm test`, `playwright test`, etc.).
4. Let the plugin summarize failures and suggest fixes.
5. Re-run only affected tests for fast validation.

## Next setup steps
1. Edit `.codex-plugin/plugin.json` and replace all `[TODO: ...]` fields.
2. Add agent instructions in `skills/testing-agent/SKILL.md`.
3. Add executable scripts in `scripts/` for your stack.
4. Add hook config in `hooks.json` if you want automated triggers.

## Example prompts
- "Generate a regression suite for checkout and payment flow."
- "Run smoke tests and summarize failures by severity."
- "Convert the last failed test output into GitHub issue drafts."
