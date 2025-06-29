# Python Tooling Learning Roadmap

## Overview
This roadmap follows the **Pareto Principle (80/20 rule)** - focusing on the 20% of tools that provide 80% of code quality improvement. Each tool builds on the previous one, creating a systematic approach to writing better Python code.

## Phase 1: Foundation (Week 1-2)
**Goal: Establish basic code quality automation**

### 1.1 uv - Fast Python Package Manager
- **Why**: Modern, fast alternative to pip/poetry for dependency management
- **Impact**: Faster package installation and project setup
- **Topics**:
  - Installation and basic usage
  - Creating and managing virtual environments
  - Dependency management with pyproject.toml
  - Integration with development workflow

### 1.2 Ruff - The Swiss Army Knife
- **Why**: Single tool that handles formatting AND linting
- **Impact**: Immediate code consistency + catches real problems
- **Topics**:
  - Installation and configuration
  - Basic formatting rules
  - Common linting issues and fixes
  - Integration with Cursor/VSCode

### 1.3 Pre-commit Hooks
- **Why**: Automation prevents me from committing bad code
- **Impact**: Forces good habits, catches issues before they're permanent
- **Topics**:
  - Setting up pre-commit framework
  - Configuring Ruff in pre-commit
  - Understanding the commit workflow

## Phase 2: Type Safety (Week 3-4)
**Goal: Catch bugs before they happen**

### 2.1 mypy - Static Type Checking
- **Why**: Catches type-related bugs that would crash at runtime
- **Impact**: Reduces debugging time significantly
- **Topics**:
  - Basic type annotations
  - mypy configuration
  - Common type errors and fixes
  - Gradual typing approach

### 2.2 Type Annotations Best Practices
- **Why**: Good type hints serve as documentation
- **Impact**: Code becomes self-documenting
- **Topics**:
  - When to use types vs when to skip
  - Type hints for functions, classes, variables
  - Using typing module for complex types

## Phase 3: Testing & Documentation (Week 5-6)
**Goal: Prove my code works and document it properly**

### 3.1 pytest - Testing Framework
- **Why**: Automated testing catches regressions
- **Impact**: Confidence to refactor and add features
- **Topics**:
  - Writing basic tests
  - pytest fixtures and parametrization
  - Test organization and structure
  - Running tests in CI

### 3.2 Testing Strategy
- **Why**: Not all code needs the same level of testing
- **Impact**: Focus testing effort where it matters most
- **Topics**:
  - Unit vs integration tests
  - Test coverage (when it matters)
  - Testing best practices

### 3.3 Documentation Tools
- **Why**: Good documentation makes code maintainable and usable
- **Impact**: Others (and future me) can understand and use my code
- **Topics**:
  - Docstring conventions (Google, NumPy, reStructuredText)
  - Sphinx for generating documentation
  - Type hints as documentation
  - README and API documentation
  - Documentation testing with doctest

## Phase 4: Security & Performance (Week 7-8)
**Goal: Write secure, efficient code**

### 4.1 Bandit - Security Linting
- **Why**: Catches common security vulnerabilities
- **Impact**: Prevents security issues before they're exploited
- **Topics**:
  - Common Python security issues
  - Bandit configuration
  - Security best practices

### 4.2 Basic Profiling
- **Why**: Identify performance bottlenecks
- **Impact**: Write faster code without guessing
- **Topics**:
  - Using cProfile
  - Identifying slow code
  - Performance optimization basics

## Phase 5: Advanced Integration (Week 9-10)
**Goal: Professional-grade development workflow**

### 5.1 CI/CD Integration
- **Why**: Automated quality checks on every change
- **Impact**: Consistent quality across team/self
- **Topics**:
  - GitHub Actions setup
  - Running all tools in CI
  - Quality gates

### 5.2 Project Structure & Configuration
- **Why**: Professional project organization
- **Impact**: Scalable, maintainable codebases
- **Topics**:
  - pyproject.toml configuration
  - Project structure best practices
  - Dependency management

## Success Metrics
- **Code Quality**: Consistent formatting, no linting errors
- **Bug Reduction**: Type errors caught before runtime
- **Confidence**: Tests pass, code is secure
- **Efficiency**: Automated workflow, less manual checking
- **Documentation**: Clear, comprehensive docs that stay current

## Tools Not Covered (Deliberately)
- **Black**: Ruff handles formatting better
- **Pylint**: Ruff is faster and more modern
- **Flake8**: Ruff includes all its functionality
- **Complex profiling tools**: Start with basics first
- **pip/poetry**: uv is faster and more modern

## Next Steps After This Roadmap
- Advanced testing patterns
- Performance optimization
- Code complexity analysis
- Advanced type patterns
- API documentation with OpenAPI/Swagger

---

**Remember**: This roadmap focuses on **immediate impact**. Each tool should be mastered before moving to the next. Quality over quantity. 