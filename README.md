# OpenCode Skills Collection

A comprehensive collection of 24 professional skills for [OpenCode](https://opencode.ai) — an interactive CLI tool for software engineering tasks.

## Skills Overview

| # | Skill | Description | Language |
|---|-------|-------------|----------|
| 1 | **accessibility** | WCAG 2.1 AA, semantic HTML, ARIA patterns, keyboard navigation | EN |
| 2 | **api-design** | REST, GraphQL, OpenAPI 3.1, versioning, pagination | EN |
| 3 | **architecture** | SOLID, Clean Architecture, design patterns, microservices | FR |
| 4 | **backoffice-design** | RBAC, admin dashboards, data density, workflow efficiency | EN |
| 5 | **banner-design** | Multi-format banners for social, ads, web, print | EN |
| 6 | **brand** | Brand voice, visual identity, messaging frameworks | EN |
| 7 | **ci-cd-automation** | CI/CD pipelines, GitHub Actions, Docker, DevOps | FR |
| 8 | **coding-standards** | Clean code, professional conventions, best practices | FR |
| 9 | **data-tables** | Complex tables: sorting, filtering, pagination, bulk actions | EN |
| 10 | **database** | Schema design, indexing, migrations, ORM, NoSQL | EN |
| 11 | **design** | Unified design: logos (55 styles), CIP, slides, banners, icons | EN |
| 12 | **design-system** | Token architecture, component specs, Chart.js, slides | EN |
| 13 | **design-system-shadcn** | shadcn/ui architecture, composition, multi-brand theming | EN |
| 14 | **documentation** | Docs-as-code, API reference, technical writing | EN |
| 15 | **form-design** | Validation, error handling, wizards, auto-save | EN |
| 16 | **git-workflow** | Branching strategies, conventional commits, collaboration | FR |
| 17 | **monitoring-observability** | Logging, metrics, distributed tracing, alerting | EN |
| 18 | **performance** | Core Web Vitals, bundle analysis, caching, monitoring | FR |
| 19 | **security** | OWASP Top 10, secrets management, auth, encryption | FR |
| 20 | **slides** | Strategic HTML presentations with Chart.js | EN |
| 21 | **state-management** | React patterns, Zustand, TanStack Query, URL state | EN |
| 22 | **testing** | TDD, unit/integration/E2E tests, Vitest, Playwright | FR |
| 23 | **ui-styling** | shadcn/ui + Tailwind CSS, responsive, dark mode | EN |
| 24 | **ui-ux-pro-max** | Design intelligence: 79 styles, 192 palettes, 74 fonts | EN |

## Installation

Copy the desired skill folders to your OpenCode skills directory:

```bash
# Linux/macOS
cp -r skills/<skill-name> ~/.config/opencode/skills/

# Windows
xcopy /E /I skills\<skill-name> %USERPROFILE%\.config\opencode\skills\<skill-name>
```

Or install all skills at once:

```bash
# Linux/macOS
cp -r skills/* ~/.config/opencode/skills/

# Windows
xcopy /E /I skills\* %USERPROFILE%\.config\opencode\skills\
```

## Directory Structure

```
opencode-skills/
├── README.md
├── skills/
│   ├── accessibility/
│   │   └── SKILL.md
│   ├── api-design/
│   │   └── SKILL.md
│   ├── architecture/
│   │   └── SKILL.md
│   ├── backoffice-design/
│   │   └── SKILL.md
│   ├── banner-design/
│   │   └── SKILL.md
│   ├── brand/
│   │   └── SKILL.md
│   ├── ci-cd-automation/
│   │   └── SKILL.md
│   ├── coding-standards/
│   │   └── SKILL.md
│   ├── data-tables/
│   │   └── SKILL.md
│   ├── database/
│   │   └── SKILL.md
│   ├── design/
│   │   └── SKILL.md
│   ├── design-system/
│   │   └── SKILL.md
│   ├── design-system-shadcn/
│   │   └── SKILL.md
│   ├── documentation/
│   │   └── SKILL.md
│   ├── form-design/
│   │   └── SKILL.md
│   ├── git-workflow/
│   │   └── SKILL.md
│   ├── monitoring-observability/
│   │   └── SKILL.md
│   ├── performance/
│   │   └── SKILL.md
│   ├── security/
│   │   └── SKILL.md
│   ├── slides/
│   │   └── SKILL.md
│   ├── state-management/
│   │   └── SKILL.md
│   ├── testing/
│   │   └── SKILL.md
│   ├── ui-styling/
│   │   └── SKILL.md
│   └── ui-ux-pro-max/
│       └── SKILL.md
└── LICENSE
```

## Skill Categories

### Frontend Development
- `accessibility` — WCAG compliance and inclusive design
- `backoffice-design` — Admin panel and dashboard design
- `data-tables` — Complex data table components
- `form-design` — Form validation and UX patterns
- `state-management` — React state patterns and libraries
- `ui-styling` — shadcn/ui + Tailwind CSS styling
- `ui-ux-pro-max` — Design intelligence and best practices

### Design & Branding
- `banner-design` — Multi-format banner creation
- `brand` — Brand identity and consistency
- `design` — Unified design system (logos, CIP, slides, icons)
- `design-system` — Token architecture and component specs
- `design-system-shadcn` — shadcn/ui design system architecture

### Backend & Architecture
- `api-design` — REST, GraphQL, OpenAPI specifications
- `architecture` — SOLID, Clean Architecture, microservices
- `database` — Schema design, indexing, migrations
- `monitoring-observability` — Logging, metrics, tracing

### DevOps & Quality
- `ci-cd-automation` — CI/CD pipelines and automation
- `coding-standards` — Clean code conventions
- `git-workflow` — Git branching and commit conventions
- `performance` — Web performance optimization
- `security` — Application security (OWASP)
- `testing` — TDD, unit/integration/E2E testing

### Documentation & Content
- `documentation` — Technical documentation
- `slides` — Strategic HTML presentations

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-skill`)
3. Commit your changes (`git commit -m 'feat: add amazing skill'`)
4. Push to the branch (`git push origin feature/amazing-skill`)
5. Open a Pull Request

## License

MIT License — see [LICENSE](LICENSE) for details.
