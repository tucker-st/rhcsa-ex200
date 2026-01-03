# Contributing Guidelines

Thank you for your interest in contributing to this RHCSA (EX200) practice repository.

This project is intended to remain **educational, exam-safe, and professionally usable**.  
All contributions must follow the guidelines below.

---

## Purpose of This Repository

This repository exists to provide:

- Hands-on RHCSA (EX200) practice
- Exam-aligned, outcome-based labs
- Professional-quality Linux administration examples
- NDA-safe educational content

It is **not** intended to replicate, disclose, or reverse-engineer Red Hat exam content.

---

## What Contributions Are Welcome

Contributions that are **encouraged** include:

- Typo fixes and clarity improvements
- Improved validation steps
- Additional troubleshooting notes
- Safer or clearer command usage
- RHEL-version-neutral improvements
- Bug fixes in auto-grading scripts
- Documentation improvements

All contributions should:
- Improve correctness
- Improve clarity
- Improve exam realism

---

## What Contributions Are NOT Accepted

The following will **not** be accepted:

- Exam questions, answers, or verbatim tasks
- Content copied from Red Hat training or exams
- NDA-protected or proprietary material
- “Shortcut” solutions that bypass learning
- Automation that removes hands-on practice
- GUI-based solutions
- Docker-based solutions (Podman only)

If unsure, **do not submit** the content.

---

## Exam Safety and NDA Compliance

Contributors must ensure that:

- All content is **original**
- No confidential exam information is used
- No copyrighted training material is copied
- Tasks are **conceptual**, not verbatim exam replicas

This repository intentionally avoids:
- Exact exam wording
- Exact task sequences
- Point values or grading logic

---

## Style Guidelines

Please follow these conventions:

### Markdown
- GitHub-flavored Markdown only
- No embedded HTML
- Clear headings and sections
- Code blocks for commands only

### Shell Commands
- Prefer full paths where appropriate
- Use exam-safe tools only
- Avoid aliases
- Avoid unnecessary flags

### Scripts
- Must be Bash (`#!/bin/bash`)
- Must be idempotent where possible
- Must not modify system state unintentionally
- Must be readable and well-commented

---

## Auto-Grading Scripts

If contributing to auto-grading:

- Scripts must be **read-only**
- No configuration changes allowed
- Clear PASS / FAIL output required
- False FAIL scenarios must be documented

---

## Commit Guidelines

- Use clear, descriptive commit messages
- One logical change per commit
- No binary files unless necessary

Example:
```
Improve SELinux validation in Lab 05
```

---

## Pull Request Process

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test manually
5. Submit a pull request with:
   - What changed
   - Why it improves the repository
   - Any exam-scope considerations

Incomplete or unclear PRs may be rejected.

---

## Maintainer Discretion

The maintainer reserves the right to:
- Reject contributions that conflict with exam safety
- Modify submissions for consistency
- Request changes before merging

This ensures the repository remains **clean, accurate, and trustworthy**.

---

## Code of Conduct

Be professional and respectful.

This repository is intended for:
- Learners
- Professionals
- Educators

Harassment, disrespect, or exam cheating advocacy will not be tolerated.

---

## Final Note

The goal is not to “pass an exam once” —  
the goal is to **build real administrative skill**.

If your contribution helps someone become a better Linux administrator,  
it belongs here.

Thank you for contributing.
