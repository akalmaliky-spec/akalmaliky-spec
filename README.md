# Akram Al-Maliky

**Backend Engineer** — Python · FastAPI · Distributed Systems

I design and build production-grade backend systems: reliable APIs, async job pipelines, and data-intensive services that scale. My focus is on correctness, observability, and maintainability — code that works at 3am without intervention.

Based in Dearborn, MI. Open to remote roles and contract work.

---

## Tech Stack

| Layer | Tools |
|---|---|
| **Languages** | Python 3.11+ |
| **Frameworks** | FastAPI, SQLAlchemy, Pydantic v2, Alembic |
| **Async / Jobs** | asyncio, Celery, Redis, ARQ |
| **Databases** | PostgreSQL, Redis |
| **Testing** | pytest, pytest-asyncio, factory-boy, coverage, Hypothesis |
| **CI / CD** | GitHub Actions, pre-commit, Docker, Docker Compose |
| **Code Quality** | Ruff, Black, mypy (strict), Bandit |
| **CLI** | Typer, Click, Rich |

---

## Featured Projects

### [task-management-api](https://github.com/akalmaliky-spec/task-management-api)
Production-grade REST API built with FastAPI, PostgreSQL, and Alembic. Implements JWT authentication with refresh token rotation, role-based access control, and full async request handling. Test coverage enforced via CI.

**Stack:** FastAPI · PostgreSQL · Alembic · pytest · Docker · GitHub Actions

---

### [async-job-runner](https://github.com/akalmaliky-spec/async-job-runner)
Async background job processing engine using Redis and Celery. Features configurable retry logic with exponential backoff, structured logging, dead-letter queuing, and Prometheus-compatible metrics exposure.

**Stack:** Python · Celery · Redis · Docker · pytest

---

### [repo-audit-cli](https://github.com/akalmaliky-spec/repo-audit-cli)
CLI tool for auditing Git repositories against engineering best-practice checklists: missing CI configs, absent test directories, undocumented public APIs, and security anti-patterns. Outputs structured JSON or human-readable reports.

**Stack:** Python · Typer · Rich · pytest · GitHub Actions

---

### [python-solution-starter](https://github.com/akalmaliky-spec/python-solution-starter)
Opinionated Python project template with modern packaging (pyproject.toml), pre-commit hooks, strict mypy, Ruff linting, and a complete GitHub Actions CI pipeline out of the box.

**Stack:** Python · pyproject.toml · GitHub Actions · Ruff · mypy

---

### [system-design-notes](https://github.com/akalmaliky-spec/system-design-notes)
Engineering reference covering distributed systems patterns: caching strategies, API gateway design, auth flows, database sharding, rate limiting, and async architecture trade-offs. Written for senior-level review.

---

## Engineering Principles

- **Explicit over implicit** — code should communicate intent without requiring context
- **Fail fast, fail loudly** — proper error boundaries, structured logging, no silent failures
- **Test the behavior, not the implementation** — integration tests over brittle unit mocks
- **Security is a first-class concern** — input validation, least privilege, secrets management
- **Observability by default** — structured logs, health endpoints, metrics from day one
- **Automate the gatekeeping** — linting, type checks, and security scans run in CI, not in review

---

## CI / Quality Signals

Every project in this profile enforces:

- `mypy --strict` type checking
- `ruff` + `black` formatting on commit via pre-commit
- `bandit` security linting
- `pytest` with coverage thresholds in GitHub Actions
- Branch protection with required status checks

---

## Contact

**Email:** almaliky@umich.edu  
**LinkedIn:** www.linkedin.com/in/akram-almaliky-2458023ab
**Location:** Dearborn, Michigan — Remote-friendly

---

![Python](https://img.shields.io/badge/Python-3.11+-blue?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=github-actions&logoColor=white)
![mypy](https://img.shields.io/badge/mypy-strict-success)
![Ruff](https://img.shields.io/badge/Ruff-enabled-orange)
