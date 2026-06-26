# Practica

Practica is a publishing project for two connected books about using software agents well:

- **Effective Agents**: a guide for human programmers who want to use agents efficiently to build production-quality software with higher precision, stronger verification, and clearer engineering intent.
- **Machina Practica**: a set of rules, skills, and project-injection patterns that make agents more effective at delivering exact, reliable code inside real repositories.

The books share one premise: agents are most useful when humans give them clear operating constraints, strong feedback loops, and a project environment that makes increasing quality the default path.

## The Books

### Effective Agents

**Effective Agents** is written for programmers, tech leads, and engineering teams adopting coding agents in serious software work. It focuses on how to plan, delegate, supervise, review, and integrate agent contributions while raising the standard for correctness, maintainability, and production readiness.

The goal is not merely to ship more code. The goal is to help teams build systems that do exactly what the engineering team intends them to do, with no tolerance for avoidable imprecision or failure.

Expected topics include:

- How to turn vague goals into agent-ready tasks.
- How to design prompts, constraints, and checkpoints that preserve engineering judgment.
- How to review agent output for behavior, architecture, security, and test coverage.
- How to use agents across the software lifecycle: discovery, implementation, debugging, refactoring, documentation, and release work.
- How to build team norms that make agent-assisted development a quality multiplier.

### Machina Practica

**Machina Practica** is written for agents and for the humans configuring them. It is a practical rulebook: a collection of project-ready instructions, skills, checklists, and repository conventions that can be injected into new or existing projects.

Expected topics include:

- Baseline operating rules for coding agents.
- Skills for common engineering workflows.
- Project bootstrapping guidance for tests, CI, documentation, and dependency hygiene.
- Review and verification checklists.
- Patterns for making repository context easy for agents to discover and use.

## Repository Shape

This repository will hold source material for both books and any reusable agent instructions they produce. The early structure is intentionally small. As the books grow, the repository is expected to evolve toward:

```text
books/
  effective-agents/
  machina-practica/
skills/
  ...
templates/
  ...
```

Changes should favor readable prose, concrete examples, and artifacts that can be tested in real projects. The work should consistently point toward one standard: software that matches its intended behavior exactly.

## Contributing

Contributions should improve the books as practical engineering references for teams trying to build better, more exact systems. Good changes usually do one of the following:

- Clarify a concept that helps humans use agents more effectively to raise quality.
- Add a rule, skill, or checklist that improves agent precision in real codebases.
- Replace abstract advice with a concrete workflow or example.
- Tighten language so instructions are easier to follow under pressure.

For now, open pull requests with focused changes and include a short explanation of the intended reader or agent behavior being improved.

## Status

Practica is at the beginning of its editorial life. The first milestone is to establish the vision, outline both books, and begin collecting field-tested practices that help agent-assisted teams build more exact, more reliable software.
