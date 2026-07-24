# Tuxmint Open Source

[![My Awesome Stats](https://awesome-github-stats.azurewebsites.net/user-stats/hermes-archham?cardType=level-alternate&theme=github-dark&fontFamily=Alfa%20Slab%20One&preferLogin=false)](https://git.io/awesome-stats-card)
[![My Awesome Stats](https://awesome-github-stats.azurewebsites.net/user-stats/archham?cardType=level-alternate&theme=github-dark&fontFamily=Alfa%20Slab%20One&preferLogin=false)](https://git.io/awesome-stats-card)

**Tuxmint Open Source** is a public workspace for practical infrastructure, automation, security, and agent-assisted engineering projects.

This organization exists to make useful engineering work easier to inspect, reuse, verify, and improve together. It is where public-facing Tuxmint projects can be documented transparently without exposing private infrastructure, customer data, or operational secrets.

## What We Work On

Our current work focuses on small, maintainable tools and documentation for real-world operations:

- Linux and self-hosted service operations
- Automation and repeatable deployment workflows
- Security-conscious infrastructure tooling
- Public-safe validation evidence and compatibility reporting
- Operator-focused documentation and runbooks
- Human-agent collaboration patterns with Hermes Agent

The goal is not to publish experiments for their own sake. The goal is to turn repeated operational lessons into clear, testable, reusable artifacts.

## Featured Projects

- [`misp-docker-lifecycle-manager`](https://github.com/Tuxmint-Open-Source/misp-docker-lifecycle-manager) — a non-invasive lifecycle manager for official MISP Docker deployments.
- [`hermes-team-policy-template`](https://github.com/Tuxmint-Open-Source/hermes-team-policy-template) — a reusable team policy template for running Hermes Agent collaboratively.

## How We Work

### Verify Before Claiming

Public claims should be backed by evidence. When a project says something works, we aim to support that with tests, command output, validation notes, release checks, compatibility matrices, or other reproducible evidence.

### Keep Documentation Useful

A README should help a real operator understand what a project does, when to use it, how to start safely, and where the limits are. We prefer clear front-door documentation over scattered notes.

### Separate Public Knowledge From Private Operations

This organization is public by design. We publish reusable patterns, sanitized examples, documentation, and open-source code.

We do **not** publish:

- secrets, credentials, or tokens
- private hostnames, IP addresses, access paths, or topology
- customer data or private operational logs
- undisclosed vulnerability details
- security posture details that would help an attacker
- unreviewed internal notes presented as public facts

### Prefer Maintainable Solutions

Simple, readable, and testable is better than clever and fragile. Automation should be understandable by the next maintainer, not only by the person who wrote it.

### Be Honest About Status

We distinguish between ideas, work in progress, released features, and validated compatibility. If validation is pending, partial, or tied to a specific version pair, the documentation should say so clearly.

## Working With Hermes Agent

Hermes Agent is used as an engineering assistant for investigation, drafting, automation, review, and validation support.

Hermes helps by:

- researching upstream documentation and project behavior
- drafting and improving public documentation
- writing scripts, tests, workflows, and runbooks
- checking assumptions against real tool output
- turning repeated lessons into reusable procedures
- keeping public wording sanitized and evidence-based

Hermes does not replace human judgment. Maintainers remain responsible for intent, review, risk decisions, and final publication.

## Collaboration Principles

We want contributors, users, and maintainers to be able to understand not only the code, but also the operating model behind it:

1. **Make the useful path obvious.** New users should know where to start.
2. **Keep claims reviewable.** Link to evidence where possible.
3. **Respect operational privacy.** Public examples must be safe to share.
4. **Document limits honestly.** Unknowns and pending validation are normal.
5. **Improve the next run.** If something was hard, capture the lesson.

## What Belongs Here

Good public content for this organization includes:

- reusable open-source tools
- operator guides and runbooks
- sanitized deployment examples
- public-safe validation reports
- compatibility matrices
- issue templates and roadmaps
- helper scripts with clear safety boundaries
- lessons learned that do not expose private infrastructure

## Long-Term Direction

Tuxmint Open Source should become a practical public home for reliable, transparent, operator-friendly engineering work.

We aim for projects that are:

- clear enough to review
- safe enough to share
- small enough to maintain
- tested enough to trust
- honest about what is and is not validated

## Working Motto

> Build clearly.  
> Validate honestly.  
> Share only what is safe.  
> Leave the next maintainer better prepared.
