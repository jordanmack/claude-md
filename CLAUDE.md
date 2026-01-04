## Problem Solving & Debugging

- CRITICAL: Always debug to find and fix the root issue when encountering problems; never use workarounds.
- CRITICAL: Always design systems to fail fast with descriptive, context-rich error messages.
- CRITICAL: Never make assumptions about code behavior; verify by reading the actual implementation.
- Always treat compiler warnings like errors and fix them immediately unless directed otherwise.
- Always verify changes work as expected before moving to the next task.
- Always stop and reassess the strategy with the user after three failed attempts at the same approach.
- Never use sed as a fallback when normal editing fails; diagnose and fix the editing issue directly.

## Code Style & Quality

- CRITICAL: Always change only what is necessary to achieve the goal; never rewrite working code unnecessarily.
- CRITICAL: Always avoid premature abstractions and over-engineering; engineer at the appropriate level for the project scope, and prompt the user if unclear.
- Always prioritize well-structured, readable code over brevity.
- Always document why important design decisions are made in concise code comments and official documentation (if it exists).
- Always write generated text as complete sentences with ending punctuation, or use title case for labels.
- Always write text that is clear, concise, and direct without marketing fluff or jargon.
- Always prefer tabs over spaces for new projects.
- Always end text files with an empty line.
- Always place new files in locations consistent with the existing project structure.

## Learning & Integration

- Always study existing code to understand conventions, patterns, and style before implementing new features so you can match them.
- Never introduce new tools or libraries without strong justification.

## Testing

- Always prefer test-driven development when planning new features.
- Never disable tests to make them pass; fix the underlying issue.

## Git Workflow

- Always make Git commits in logical groups rather than one large commit.
- Always write Git commit messages as a concise sentence starting with a verb and ending with proper punctuation.
- Never commit code with compilation failures, warnings, or errors.

## Tooling & Environment

- Always verify the dev server is not running before starting a new instance.
- Always use Bun instead of NPM when possible.
- Never use killall on "node" because it will kill servers you did not start.

## Planning & Communication

- CRITICAL: Always research and plan thoroughly until 99% confidence before presenting plans, recommendations, or starting integration.
- CRITICAL: Always provide a concise plan summary with questions, concerns, and recommendations, then wait for confirmation before implementing.
- Always include a recommended answer when asking a question.
- Always suggest creating a specification file when planning a new project.
- Always spawn agents to run tasks in parallel when safe and beneficial for speed.
