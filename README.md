<!-- ─────────────  HERO + TAGLINE ───────────── -->
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?color=FFA500&size=28&lines=Building+Reliable+Software;Scaling+Complex+Systems;Crafting+Solutions+Users+Love" alt="Typing Text" />
</p>

<p align="center">
  <em>Engineering for impact, writing code that lasts, scales, and delights.</em>
</p>

---

<!-- ─────────────  CORE THEMES ───────────── -->
### My Engineering Philosophy

| Principle               | Why It Matters                                           | How I Apply It |
|-------------------------|-----------------------------------------------------------|----------------|
| **Scalable Architecture** | Systems should grow, not collapse under load.             | Modular designs, clear boundaries, horizontal-first thinking. |
| **Code as Communication** | Code must be readable and self-evident.                  | Naming discipline, refactoring, concise abstractions. |
| **Performance Awareness** | Optimize where it matters — not prematurely.             | Baseline profiling, measure-before-tuning, avoid clever slow hacks. |
| **Testing & CI/CD**       | Confidence before deployment is non-negotiable.         | Unit tests, integration tests, pipelines that fail loudly. |
| **User-Focused Thinking** | Features solve human problems, not checklist items.     | Talking to users, reducing friction, minimizing cognitive load. |


---

<!-- ─────────────  TECH ECOSYSTEM ───────────── -->
### Technical Fluency
<p align="center">
  <img src="https://techstack-generator.vercel.app/python-icon.svg" width="50" alt="Python" />
  <img src="https://techstack-generator.vercel.app/js-icon.svg" width="50" alt="JavaScript" />
  <img src="https://techstack-generator.vercel.app/django-icon.svg" width="50" alt="Django" />
  <img src="https://techstack-generator.vercel.app/java-icon.svg" width="50" alt="Java" />
  <img src="https://techstack-generator.vercel.app/react-icon.svg" width="50" alt="React" />
  <img src="https://techstack-generator.vercel.app/docker-icon.svg" width="50" alt="Docker" />
  <img src="https://techstack-generator.vercel.app/graphql-icon.svg" width="50" alt="GraphQL" />
  <img src="https://techstack-generator.vercel.app/jest-icon.svg" width="50" alt="Jest" />
</p>

> Focused on building full-stack, highly maintainable, and production-ready systems.  

---

<!-- ─────────────  PROJECT SNAPSHOT ───────────── -->
### System Architecture
```mermaid
flowchart TD
    subgraph Frontend
        A[React / Next.js/ Angular.js]
        B[Tailwind / Styled Components]
    end

    subgraph Backend
        C[Node.js / Python APIs]
        D[GraphQL / REST]
        E[Microservices]
    end

    subgraph AI & Data
        F[ML Models /MCPs]
        G[Data Pipelines]
        H[Cache / DB / PostgreSQL / Vector DBs]
    end

    subgraph DevOps
        I[Docker / Kubernetes]
        J[CI/CD Pipelines]
        K[Monitoring & Logging]
    end

    A --> D
    B --> D
    D --> E
    E --> F
    F --> G
    G --> H
    E --> I
    I --> J
    J --> K
