# Engineering Handbook

## Summary
This handbook explains how we build, ship, and maintain the Group Scholar platform.

## Principles
- Reliability over novelty
- Small, reviewable pull requests
- Automate anything we repeat twice

## Development workflow
- Create a lightweight design note for new features
- Implement behind a feature flag when scope is unclear
- Write tests for critical logic and edge cases

## Quality standards
- Document API contracts before implementation
- Add observability for new services
- Keep technical debt visible in the backlog

## Environments
- Local for iteration and debugging
- Staging for stakeholder review
- Production for stable releases
