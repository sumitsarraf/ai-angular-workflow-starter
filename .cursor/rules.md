# Cursor AI Development Rules (Angular Project)

## Core Principles
- Never rewrite full files unless explicitly asked
- Always prefer minimal, targeted changes
- Do not break existing functionality
- Treat code as production-grade

## Code Safety
- Preserve all existing logic unless modification is required
- Avoid refactoring unrelated parts
- Maintain backward compatibility

## Angular Guidelines
- Follow Angular 19+ best practices
- Use standalone components when applicable
- Keep components modular and clean

## Change Strategy
- Show diff-style changes when possible
- Explain what is being changed and why
- Ask before large structural changes

## Documentation Rules
- Update `/docs/changes.md` for every meaningful change
- NEVER overwrite documentation files
- Only append entries

## PR Behavior
- Act like a senior developer raising a PR
- Include summary, risks, and testing notes
