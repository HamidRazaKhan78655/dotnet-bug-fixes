# dotnet-bug-fixes

This repository documents **real-world .NET bugs** commonly found in production systems and how they were fixed.

The focus is on **clarity and practicality**:
- What the bug was
- Why it happened
- What impact it had
- How it was fixed

All examples are based on patterns seen in **ASP.NET Core, Web APIs, EF Core, and Blazor** applications.

---

## Scope

The bugs documented here fall into the following areas:

- **Security & Authorization**
  - Missing or incorrect authorization
  - IDOR (Insecure Direct Object Reference)
  - Role and claim misuse
  - Tenant isolation issues

- **Web APIs**
  - Missing validation
  - Over-posting
  - Improper error handling
  - Unsafe assumptions in request data

- **Entity Framework Core**
  - N+1 query problems
  - Incorrect tracking behavior
  - Performance issues
  - Data consistency bugs

- **Blazor**
  - Null reference exceptions
  - State synchronization issues
  - Lifecycle and rendering bugs

- **Performance & Reliability**
  - Async deadlocks
  - Blocking calls
  - Caching mistakes

---

## Structure

Each bug is documented as a **standalone Markdown file** and follows a consistent format:

- Context
- Problem
- Root cause
- Impact
- Reproduction steps
- Fix
- Result
- Notes

This mirrors how bugs are typically reported in **production environments and security programs**.

---

## Why This Repository Exists

Bugs are often caused not by lack of knowledge, but by:
- Incorrect assumptions
- Missing checks
- Edge cases in real workflows

This repository exists to **capture those mistakes and their fixes**, so they can be recognized and avoided in future systems.

---

## Disclaimer

- Code snippets are simplified for clarity
- Examples may not represent complete applications
- Sensitive details are intentionally omitted

---

## Usage

You are free to:
- Read and learn from the examples
- Apply similar fixes in your own projects
- Reference patterns when reviewing or debugging .NET systems

---

## Author

Maintained by a .NET developer focusing on **backend systems, APIs, and security-aware design**.
