# CodeWithoutCloud

**CodeWithoutCloud** is my personal programming-learning repository.

The goal is simple:

> **Write the code myself. Understand what I build. Learn by doing.**

This repository is not primarily about building projects or applications. It is a collection of small **artifacts** built to understand programming, software engineering, and practical development.

---

## Core Principle

### No AI-Written Code

I do not use AI to write the implementation for me.

The code in this repository should be written by me, even when the implementation is small, difficult, or takes longer than expected.

AI can be used as a:

- Teacher
    
- Reviewer
    
- Debugging assistant
    
- Explanation tool
    
- Design discussion partner
    
- Source of alternative approaches
    

But **the implementation is mine**.

The purpose is not to produce code as quickly as possible. The purpose is to rebuild programming ability through practice.

---

## How I Learn

For each artifact, the general workflow is:

```text
Idea
  ↓
Research
  ↓
Think / Design
  ↓
Implement a minimum version myself
  ↓
Test it
  ↓
AI Review
  ↓
Understand the feedback
  ↓
Improve
  ↓
Version the improvements
  ↓
Document the learning
```

### 1. Research

Before implementing something, I can freely search Google and other documentation/resources.

Research is part of programming.

I may use:

- Google
    
- Official documentation
    
- MDN
    
- Node.js documentation
    
- Linux documentation
    
- RFCs
    
- Books
    
- Blog posts
    
- Stack Overflow
    
- GitHub repositories
    
- Other technical resources
    

The important distinction is:

> **I research how things work; I do not outsource the syntax/implementation.**

---

### 2. Discuss With AI

I can discuss the problem with AI before, during, or after implementation.

For example, I can ask:

- "Explain how this works."
    
- "What should I consider before implementing this?"
    
- "What are the security risks?"
    
- "What edge cases should I test?"
    
- "Why does this approach work?"
    
- "What alternatives exist?"
    
- "Explain this error."
    
- "Review my implementation."
    

AI discussion is treated as part of the learning process, not as a replacement for writing the code.

---

### 3. Build the Minimum Basic Version

I first implement the smallest useful version myself.

The first version does not need to be perfect.

It should demonstrate that I understand the basic problem and can produce a working implementation without AI-generated code.

For example:

```text
v0.1
    ↓
Basic functionality works
    ↓
Test
    ↓
Review
```

Features are intentionally kept small.

---

## AI Review

After a basic implementation works, I can ask AI to review it.

The review may cover:

- Bugs
    
- Security vulnerabilities
    
- Bad assumptions
    
- Edge cases
    
- Error handling
    
- Resource management
    
- Performance problems
    
- Code quality
    
- Maintainability
    
- API/design decisions
    
- Platform-specific concerns
    
- Missing tests
    
- Possible improvements
    

The AI review is **not automatically accepted**.

I must understand the feedback before making changes.

> **AI suggests. I investigate. I decide. I implement.**

---

## Review History

Every meaningful AI review should be documented in the artifact's repository.

A review should record things such as:

```text
Review date
Artifact version
What was reviewed
Problems identified
Security issues
Suggestions
What I accepted
What I rejected
Why I made those decisions
Changes implemented
```

This creates a visible history of how the artifact evolved.

Example:

```text
v0.1
Basic implementation

AI Review #1
- Found path traversal vulnerability
- Missing input validation
- Error handling could expose internal information

v0.2
- Fixed path traversal
- Added input validation
- Improved error handling
```

The review itself becomes part of the artifact.

---

# Version Management

Each artifact should maintain its improvement history.

A `TODO.md` file is used to track planned improvements, discovered problems, and review-driven work.

For example:

```text
TODO.md

## Security
- [x] Validate user-provided paths
- [ ] Handle symbolic links safely

## Reliability
- [x] Handle missing files
- [ ] Improve error reporting

## Improvements
- [ ] Add recursive directory support
- [ ] Add tests
```

Completed work should be marked accordingly.

The artifact's version should change when meaningful improvements are made.

Example:

```text
v0.1.0 → Initial working implementation

v0.1.1 → Security fixes

v0.2.0 → New functionality

v0.2.1 → Bug fixes
```

Versioning is used to show the evolution of the artifact rather than simply tracking releases.

---

# Improvement Philosophy

The first goal is **correctness and safety**, not feature count.

When reviewing an existing artifact, improvement should generally happen in this order:

```text
1. Understandability
       ↓
2. Bugs
       ↓
3. Security vulnerabilities
       ↓
4. Reliability / error handling
       ↓
5. Tests
       ↓
6. Performance
       ↓
7. Features
       ↓
8. Polish
```

A tiny artifact with good fundamentals is more valuable for learning than a large artifact containing features I do not understand.

---

# What I Want This Repository to Show

This repository should show my progression from:

```text
Using code
    ↓
Understanding code
    ↓
Writing code
    ↓
Debugging code
    ↓
Reviewing code
    ↓
Improving code
    ↓
Designing systems
```

The artifacts may be small.

That is intentional.

The value is in the reasoning, implementation, review, and evolution behind them.

---

## Rules

1. **I write the implementation myself.**
    
2. **I can use Google and technical documentation freely.**
    
3. **I can discuss programming problems with AI.**
    
4. **I can ask AI to explain concepts and review my code.**
    
5. **I do not copy AI-generated implementations as my own work.**
    
6. **I implement the minimum working version before requesting a full review.**
    
7. **I investigate AI review suggestions before implementing them.**
    
8. **Vulnerabilities should be addressed before adding features.**
    
9. **Important AI reviews are documented in the artifact repository.**
    
10. **Improvements are tracked through `TODO.md`.**
    
11. **Meaningful changes are versioned.**
    
12. **Every artifact should remain understandable to me.**
    

---

# The Standard

The question is not:

> "Can AI build this?"

The question is:

> **"Can I understand the problem, write the implementation, explain why it works, identify its weaknesses, and improve it?"**

That is what **** is for.
