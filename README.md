# Learning Python Tooling: From Spaghetti Code to Professional Quality

## What This Repository Is

This is a **learning journey** and **knowledge repository** for mastering Python tooling to write professional-quality code. After 10 years of writing inconsistent, unmaintainable code, I decided to level up and this is my approach.

## The Problem

- **Inconsistent code formatting** - Every file looks different
- **No automated quality checks** - Bugs slip through unnoticed  
- **Manual testing** - Time-consuming and error-prone
- **No type safety** - Runtime errors that could be caught earlier
- **Security vulnerabilities** - Common issues that tools can find

## The Solution

I decided to follow the **Pareto Principle approach** - focusing on the 20% of tools that provide 80% of code quality improvement:

1. **uv** - An extremely fast Python package and project manager
2. **Ruff** - Formatting + linting in one tool
3. **Pre-commit hooks** - Automation that prevents bad commits
4. **mypy** - Static type checking to catch bugs early
5. **pytest** - Automated testing for confidence
6. **Bandit** - Security linting to prevent vulnerabilities

This is a highly opinionated list of libraries which I am using based on my knowledge, experience, and most of all convenience. I am not going to cover every Python package manager because, in my experience, Python packaging ecosystem is very scattered with too many tools doing the same thing. So I decided to go with the one that seems to have gotten it and also which is fast.

## Repository Structure

```
learning-python-tooling/
├── ROADMAP.md                    # Learning path and topics
├── README.md                     # This file
├── phase-1-foundation/           # uv, Ruff, pre-commit
│   ├── uv/                       # Package management examples
│   ├── ruff/                     # Formatting and linting examples
│   └── pre-commit/               # Automation examples
├── phase-2-type-safety/          # mypy and type annotations
│   ├── mypy/                     # Type checking examples
│   └── type-annotations/         # Best practices and patterns
├── phase-3-testing-docs/         # pytest and documentation
│   ├── pytest/                   # Testing examples and strategies
│   └── documentation/            # Sphinx, docstrings, READMEs
├── phase-4-security-performance/ # Bandit and profiling
│   ├── bandit/                   # Security linting examples
│   └── profiling/                # Performance analysis examples
├── phase-5-integration/          # CI/CD and project structure
│   ├── ci-cd/                    # GitHub Actions examples
│   └── project-structure/        # Professional configuration
└── blog-posts/                   # Learning journey documentation
```

## How to Follow This Journey

### Prerequisites
- Python 3.12+ installed
- VSCode
- Basic Git knowledge
- Some Python experience

### Setup Instructions

1. **Clone this repository**
   ```bash
   git clone <your-repo-url>
   cd learning-python-tooling
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

3. **Follow the roadmap**
   - Start with Phase 1 in `ROADMAP.md`
   - Work through each phase directory
   - Document your learning in `blog-posts/`

### Learning Approach

**Week 1-2: Foundation**
- Install and configure uv for package management
- Install and configure Ruff
- Set up pre-commit hooks
- Format and lint your existing code

**Week 3-4: Type Safety**  
- Learn mypy and type annotations
- Add types to your existing code
- Understand gradual typing

**Week 5-6: Testing & Documentation**
- Write tests with pytest
- Document your code properly
- Test your existing code

**Week 7-8: Security & Performance**
- Use Bandit for security checks
- Basic profiling with cProfile
- Optimize your code

**Week 9-10: Integration**
- Set up CI/CD with GitHub Actions
- Organize project structure
- Professional configuration

## Blog Your Journey

I will be blogging my learning along the way, covering what I learned, challenges faced, and lessons learned. This reinforces my learning and creates a reference I can return to.

## The End Goal

By the end of this journey, I will have:
- **Consistent, readable code** that follows standards
- **Automated quality checks** that catch issues early
- **Confidence to refactor** without breaking things
- **Professional development workflow** that scales
- **Portfolio of learning** that demonstrates growth

## Remember

This isn't about installing tools - it's about **changing how I write code**. Each tool should become part of my muscle memory, not something I have to think about.

**Start with Phase 1. Don't rush. Master each tool before moving to the next.**

---

*"The best time to plant a tree was 20 years ago. The second best time is now."*

My 10 years of Python experience is my foundation. Now it's time to build professional-quality code on top of it. 