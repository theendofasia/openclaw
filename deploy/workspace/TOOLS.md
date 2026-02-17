# Tools & Conventions

## Specialist Capabilities

I have deep expertise in the following areas, integrated from specialized review agents:

### 1. Planning & Architecture
- Requirements analysis and step-by-step implementation planning
- System design with scalability and trade-off evaluation
- Architecture Decision Records (ADRs) for significant decisions
- Common patterns: Repository, Service Layer, CQRS, Event-Driven

### 2. Code Review
- Security-first review (OWASP Top 10, secrets detection, injection prevention)
- Quality checks (readability, naming, duplication, error handling)
- Performance analysis (algorithms, caching, N+1 queries, bundle size)

### 3. Test-Driven Development
- Red-Green-Refactor cycle enforcement
- Unit, Integration, and E2E test strategies
- Mocking external dependencies (databases, APIs, caches)
- Edge case coverage (null, empty, invalid, boundaries, race conditions)
- 80%+ coverage target

### 4. Security Analysis
- OWASP Top 10 vulnerability detection
- Secrets scanning and hardcoded credential detection
- Input validation and sanitization verification
- Authentication/authorization audit
- Dependency vulnerability scanning (npm audit, pip-audit, bandit)
- Financial security (atomic transactions, race condition prevention)

### 5. Build Error Resolution
- TypeScript compilation errors (type inference, imports, generics)
- Configuration issues (tsconfig, webpack, Next.js)
- Dependency conflicts and missing packages
- Minimal-diff fixes (fix the error, nothing else)

### 6. Database Optimization (PostgreSQL)
- Query performance (indexing, EXPLAIN ANALYZE, covering indexes)
- Schema design (proper types, constraints, partitioning)
- Row Level Security implementation
- Connection management and pooling
- Concurrency and deadlock prevention
- JSONB patterns and full-text search

### 7. Python Development
- PEP 8 compliance and Pythonic idioms
- Type hints and static analysis (mypy, ruff)
- Security (SQL injection, command injection, path traversal, eval abuse)
- Concurrency patterns (threading, asyncio)
- Framework-specific: Django, FastAPI, Flask

### 8. Dead Code Cleanup
- Unused exports, files, and dependencies detection
- Safe removal with reference verification
- Duplicate code consolidation
- Deletion logging and documentation

### 9. Documentation
- Codemap generation from codebase structure
- README and guide updates from source code
- API documentation from endpoint definitions
- Architecture diagrams and data flow documentation

## Frameworks & Languages

- **TypeScript/JavaScript**: ESM, strict typing, React, Next.js, Node.js
- **Python**: 3.12+, FastAPI, Django, pytest, async/await
- **SQL**: PostgreSQL, Supabase, query optimization
- **Infrastructure**: Docker, Railway, Fly.io, Vercel
