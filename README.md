**Best with:** Java 21 · Spring Boot · MySQL · Docker · GitHub Actions  
**Familiar with:** TypeScript · React · DuckDB · PostgreSQL / Supabase · Kafka · RabbitMQ

> 💡 **TL;DR** · I am a backend engineer. I write Java for software that keeps a company's books: invoicing, commercial documents and accounting. At STEL Order I went from intern to a permanent contract in three months. I shipped a module from scratch that customers use in production today. At HackSpain 2026 my team built X-Ray in under 36 hours. It is a financial health score for SMEs, and its credit limit engine cut the line before 70 of 81 deterioration events. I want to do this work at a startup where one wrong number matters.

---

## About Francisco

I am Francisco Moreno Sánchez, a software engineer from Murcia, Spain. Since October 2025 I work at [STEL Order](https://www.stelorder.com/), a management platform that thousands of small and medium businesses use every day. I build Java 21 microservices and add features to a long-lived monolith. Right now I build the accounting module. I finish my Computer Science degree at the University of Murcia in 2027. I work in Spanish, English and French at professional level.

Portfolio: [wall3n.github.io](https://wall3n.github.io/) · CV: [English PDF](https://wall3n.github.io/assets/cv/francisco-moreno-sanchez-cv-en.pdf)

### Main Achievements

- **Intern to permanent contract in three months.** STEL Order hired me as an intern in October 2025 and gave me a permanent contract in January 2026.
- **Product label module, built from scratch and in production.** A canvas editor where customers design their own product labels from a template library. I chose the architecture on day one. Customers use it today.
- **X-Ray at HackSpain 2026, Embat track.** A monthly financial health score for 250 corporate groups, read from 2.5 million bank transactions, 898,000 invoices and 2,239 debt products. The limit engine cut the credit line before 70 of 81 deterioration events (86 %), with a mean lead of 4.5 months. The [methodology page](https://hackspain-2026-embat-track.vercel.app/methodology) also shows the signal that does not beat chance.
- **AI coding assistants in the backend team.** I led their adoption in the team's daily work and automated the technical onboarding of new team members.
- **Second prize, Metaworking 2023.** A national university competition for entrepreneurship and innovation, organised by Universia.

### Most-Prideful Builds

| Project | My role & stack | Impact / Demo |
|---------|-----------------|---------------|
| **X-Ray** · SME financial health score | Pipeline, scoring engine, deployment and much of the frontend • Java 21 + Spring Boot 3 + DuckDB + React 19 | [Live demo](https://hackspain-2026-embat-track.vercel.app/) • [API (Swagger)](https://hackspain-2026-embat-track-uei8.onrender.com/swagger-ui.html) • [Code](https://github.com/JJavierBS/Hackspain-2026---Embat-track) · 86 % of deterioration events caught, 4.5 months mean lead, built in under 36 h |
| **BrewLog** · coffee extraction log | Solo dev • React 19 + TypeScript + Dexie.js + Workbox | [Live app](https://brew-log-sigma.vercel.app) • [Code](https://github.com/wall3n/BrewLog) · offline-first PWA, no account and no server, data stays on the device |
| **techxdir** · digital badge for tech events | Co-author with [@Pedrodeluna](https://github.com/Pedrodeluna) and [@elashera](https://github.com/elashera) • React 19 + Supabase + Postgres RLS + Deno | [Prototype](https://techxdir-web-nu.vercel.app) • [Code](https://github.com/Pedrodeluna/techxdir) · I wrote the passwordless sign-in, the Postgres schema with row level security and the profile edge function |

**How X-Ray works, in short.** The score separates level (where the company is today) from trajectory (where it goes). Each indicator uses fixed anchors instead of percentiles, so a company the system never saw gets a score on the same scale. A test asserts on every entity-month that the contributions add up to the final score. A second test makes sure a month reads only data dated up to the end of that month. Every anchor, weight and threshold is in one config file that you can edit from the UI.

**Work I cannot show.** The STEL Order code is proprietary. Besides the label module, I work on a commercial document engine: an R&D project that generates invoices and statements from dynamic templates, with PDF/A output. It is in development and has no production figures yet.

### Experience (TL;DR)

- **Software Engineer / STEL Order** · *Jan 2026 to present.* Java 21 microservices, the accounting module, the product label module and features on a monolith with zero-downtime deploys. Spring Boot, Spring Data JPA, MySQL, Docker, GitHub Actions.
- **Software Engineer, Intern / STEL Order** · *Oct 2025 to Dec 2025.* Built a REST service from scratch: authentication, role-based access, Flyway migrations and container deployment. Wrote the CI/CD pipeline: build, integration tests and automated image publication. Spring Security, JWT, Flyway, Testcontainers, JUnit 5.
- **BSc Computer Science / University of Murcia** · *2023 to 2027.*
- **Hackathons** · HackSpain 2026 (X-Ray, Embat track, team Byte_Me). Next: Junction 2026 in Espoo, Finland, 13 to 15 November.

---

## How I Work

- **Gets me pumped:** a problem where the numbers must be right, a team that reviews code with care, and users who touch what I shipped the same month.
- **Disappoints me:** claims nobody can check, and metrics that only show what went well.
- **Strengths:** I test what I claim. On X-Ray the tests prove the score adds up and that no month reads future data. I learn a new domain fast, and I write the docs so the next person does not have to ask me.
- **Improvement points:** I have one year of production experience. I have not yet taken a system through years of growth. I also tend to polish a design before I show it, and I am learning to share it earlier.
- **Comms style:** written and async first, with short messages that start with the decision. I am in CET and I am comfortable in Spanish, English or French.

---

## Other

### Some personal stuff

- I am from Murcia, Spain, and I am an EU citizen. I work remote or hybrid and I can relocate inside the EU.
- I make coffee at home and I log every extraction. That is why BrewLog exists.
- My portfolio has no framework and no bundler, and it has three languages. I like to see how far plain HTML, CSS and JavaScript go.

### My vision

I want to join an early-stage team in Spain or Europe that builds financial software: fintech, banking, accounting or ERP. A startup gives me what a large platform cannot give a junior engineer: ownership of a whole system, and a short loop between a decision and its result. In five years I want to be the engineer a team trusts with the part of the product where money moves. Exponential gives me a direct line to the teams that build that kind of product.

---

**Contact:** [franciscomorenosanchezfms@gmail.com](mailto:franciscomorenosanchezfms@gmail.com) · [LinkedIn](https://www.linkedin.com/in/francisco-moreno-sanchez-fms) · [GitHub](https://github.com/wall3n)
