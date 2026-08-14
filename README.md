# Hi, I'm Brian Le 👋

**Software Engineer & CS Student at the University of Waikato (New Zealand).**  
I focus on backend systems, data engineering, and high-performance application architectures. I learn by building mental models from first principles and shipping real things to production.

- 🌿 **Research Fellow (Nov 2026 – Feb 2027):** Engineering industrial process simulation software (Python/Django) at **Ahuora Smart Energy Systems**.
- 🎬 **Featured Build:** [**Movie Explorer**](https://cubewin07.github.io/movie-explorer) — production social platform featuring real-time WebSockets, multi-level caching (Caffeine + Upstash Redis), and Prometheus observability.
- 🎨 **Self-Hosted Tools:** [**customReadmeSVG**](https://github.com/cubewin07/customReadmeSVG) — serverless GraphQL card engine generating the live dynamic metrics below.

---

### ⚡ Live Metrics
*Generated on-the-fly by my [`customReadmeSVG`](https://github.com/cubewin07/customReadmeSVG) engine on Netlify Edge.*

<p align="center">
  <img src="https://lucent-sprite-e50312.netlify.app/cubewin07/stats?theme=tokyonight" alt="GitHub Stats" width="48%" />
  &nbsp;
  <img src="https://lucent-sprite-e50312.netlify.app/cubewin07/languages?theme=tokyonight" alt="Top Languages" width="48%" />
</p>

---

### 🚀 Key Projects

#### 🎬 [Movie Explorer](https://cubewin07.github.io/movie-explorer) · [Live Demo](https://cubewin07.github.io/movie-explorer)
`Java 21` · `Spring Boot 3` · `React 19` · `PostgreSQL` · `Redis` · `Caffeine` · `Flyway` · `STOMP WebSockets`
- **Multi-Level Caching:** L1 in-memory (Caffeine + Kryo serialization) + L2 distributed (Upstash Redis) with automated eviction hooks.
- **Real-Time Messaging:** Bi-directional STOMP over WebSockets for chat feeds, live presence, and unread notification tracking.
- **Production Architecture:** Flyway migrations for zero-downtime DB versioning, JWT RBAC security, and Prometheus + Actuator telemetry.

#### 🎨 [customReadmeSVG](https://github.com/cubewin07/customReadmeSVG) · [Live Demo](https://lucent-sprite-e50312.netlify.app/)
`Node.js` · `Vite` · `GitHub GraphQL API` · `Netlify Serverless`
- Dynamic SVG generator deployed on Netlify Edge with a pluggable card architecture, multi-theme engine, and memory caching to respect rate limits.

#### 🤖 AgentOS & AI Infrastructure
`TypeScript` · `Spring Boot 3` · `Docker` · `Ollama` · `GitHub App API`
- **AgentOS:** VPS control-plane for isolated developer agent orchestration (collaborative build with Hien Tran).
- **AI Code Reviewer:** Event-driven Spring Boot webhook service with GitHub App auth dispatching automated reviews via local LLMs.

---

### 🛠 Core Stack

- **Backend & Systems:** Java (Spring Boot 3, Spring Security, JPA/Hibernate, WebSockets), Python (Django), C# (.NET), C++
- **Frontend & Web:** React 19, JavaScript / TypeScript, TanStack Query, TailwindCSS
- **Data & DevOps:** PostgreSQL (Supabase), Redis, Flyway, Docker, Prometheus, Linux/VPS

---

### 🧠 Principles & Mental Models

- **Mental Models First:** Build a concrete understanding of runtime internals, OS mechanics, and data flow before implementing or delegating.
- **Intent-Level Verification:** Stress-test architectural intent and edge cases rather than accepting surface-level syntax or AI-generated output blindly.
- **Active Recall & Deep Work:** Retain and master CS fundamentals through deliberate practice, structured spaced repetition, and focused deep work.
- **Production Rigor:** Design with failure in mind from day one — network partitions, cache invalidations, and connection saturation.

---

### 📬 Connect

[tanthang071208@gmail.com](mailto:tanthang071208@gmail.com) · [github.com/cubewin07](https://github.com/cubewin07) · [Portfolio](https://cubewin07.github.io/movie-explorer) · Hamilton, New Zealand 🇳🇿
