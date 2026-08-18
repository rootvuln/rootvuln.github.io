# RootVuln AppSec

> A personal Application Security knowledge base, research journal, and security portfolio.

🌐 **Website:** https://rootvuln.github.io/

---

## About

**RootVuln AppSec** is my personal knowledge base for learning, practicing, researching, and documenting Application Security.

I built this project to keep my security knowledge organized and easy to revisit while also making useful notes and research publicly available to other security learners.

The goal isn't to create a collection of copied tutorials.

These are my working notes — concepts I've studied, things I've tested, lessons from labs, security observations, and research that I want to be able to return to later.

---

## What You'll Find Here

### Web Security

Notes and research covering areas such as:

- Cross-Site Scripting (XSS)
- SQL Injection
- Server-Side Request Forgery (SSRF)
- Local File Inclusion (LFI)
- File Upload Vulnerabilities
- Web Cache Poisoning
- Web Cache Deception
- HTTP Request Smuggling

### API Security

- API Testing
- Authentication
- Authorization
- OAuth 2.0
- IDOR / BOLA

### Methodology

- Reconnaissance
- Testing Methodology
- Vulnerability Reporting

### Labs

Practical learning and observations from:

- TryHackMe
- PortSwigger Web Security Academy

### Research

A collection of security research, observations, and things worth revisiting.

### Writeups

Practical security writeups documenting interesting findings, testing approaches, and lessons learned.

---

## Current Work

The knowledge base is actively being built.

Some sections may currently display **Coming Soon** while I work through the topics and prepare the notes.

Published material is added progressively as I learn and document each subject.

---

## Philosophy

I believe security knowledge becomes much more valuable when you can:

1. Understand the underlying concept.
2. Recognize it during testing.
3. Reproduce it in an authorized environment.
4. Understand why the vulnerability exists.
5. Understand its impact.
6. Document what you learned.

This project is built around that process.

> **Learn → Practice → Test → Understand → Document**

---

## Learning Areas

My current focus is primarily around:

- Web Application Security
- API Security
- Vulnerability Research
- Bug Bounty Methodology
- Security Testing
- Offensive Security
- Security Research
- Practical Labs

---

## Tech Stack

This site is built with:

- MkDocs
- Material for MkDocs
- Markdown
- GitHub Pages

---

## Project Structure

```text
rootvuln.github.io/
│
├── docs/
│   ├── web-security/
│   ├── api-security/
│   ├── methodology/
│   ├── labs/
│   ├── research/
│   ├── writeups/
│   ├── assets/
│   ├── stylesheets/
│   └── index.md
│
├── overrides/
│   └── partials/
│
├── mkdocs.yml
└── README.md
```

The `docs/` directory contains the actual knowledge base.

Theme customization and site behavior are kept separately from the security notes.

---

## Running Locally

Clone the repository:

```bash
git clone https://github.com/rootvuln/rootvuln.github.io.git
cd rootvuln.github.io
```

Install the required dependencies:

```bash
pip install mkdocs-material
```

Start the development server:

```bash
mkdocs serve
```

Then open:

```
http://127.0.0.1:8000/
```

---

## Why I Built This

Cybersecurity is a field where it's easy to learn something today and forget parts of it months later.

Writing things down gives me a searchable reference that I can return to whenever I need it.

At the same time, publishing the notes allows other learners to benefit from the things I've already worked through.

So this project serves two purposes:

**For me:**
A long-term security knowledge base.

**For others:**
A collection of practical notes and observations from my learning journey.

---

## Disclaimer

The security techniques and concepts documented here are intended for:

- Learning
- CTFs
- Security labs
- Authorized penetration testing
- Bug bounty programs where testing is explicitly permitted

Do not use information from this repository against systems you do not have permission to test.

Always follow the scope and rules of the target program.

---

## Status

🚧 Actively maintained

New topics, notes, research, and writeups will be added as I continue learning and testing.

---

## Author

**Vineet Kumar**

Cybersecurity Student
Web Application Security Enthusiast
Bug Bounty Learner

🌐 Website: https://rootvuln.github.io/

---

> Knowledge is the ultimate power.
>
> Learn it. Practice it. Document it.
>
