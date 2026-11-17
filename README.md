**Best with:** Java 21 · Spring Boot · MySQL · Docker · GitHub Actions  
**Familiar with:** TypeScript · React · React Native for Vega · Python · agentic AI · Amazon Bedrock · DuckDB · PostgreSQL / Supabase · Kafka · RabbitMQ

> 💡 **TL;DR** · I am a software engineer. The work starts above the code: I gather the requirements, talk with the client, prepare the infrastructure and design the solution. I am fullstack, and I build agentic AI. Since 2 November 2026 I do this at LambdaLoopers. At STEL Order, from October 2025 to October 2026, I went from intern to a permanent contract in three months and shipped a module from scratch that customers use in production. At HackSpain 2026 my team built X-Ray in under 36 hours. It is a financial health score for SMEs, and its credit limit engine cut the line before 70 of 81 deterioration events.

---

## About Francisco

I am Francisco Moreno Sánchez, a software engineer from Murcia, Spain. Since 2 November 2026 I work at [LambdaLoopers](https://lambdaloopers.com/), a technology partner in Barcelona that builds digital solutions for companies. I take a piece of work from the client's requirement to a running system: the conversation, the infrastructure, the design and the code. I am fullstack, and I build agentic AI as well as classical services. From October 2025 to October 2026 I worked at [STEL Order](https://www.stelorder.com/), a management platform that thousands of small and medium businesses use every day. I started as an intern in October 2025 and received a permanent contract in January 2026. I built Java 21 microservices, added features to a long-lived monolith, and worked on the accounting module. I finish my Computer Science degree at the University of Murcia in 2027. I work in Spanish, English and French at professional level.

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
| **Grabbit** · research agent for Slush investors | First idea, investor interviews, Cala briefings, team coordination, web app and pitch video • React + TypeScript; the agent is Gemini with tool calls, on data from the Cala graph | [Live demo](https://www.grabbit.cloud) • [Pitch](https://youtu.be/63DRjFkbU_A) • [Code](https://github.com/JJavierBS/Grabbit) · Junction 2026, Espoo, 13 to 15 November. The investor names funds they trust. The agent asks a few questions with numbers from the graph, ranks the Slush startups a few funding rounds away, and puts a source on every fact. |
| **FireDrift** · what to watch on Fire TV | Butler character, persona and gestures, push to talk, and the demo video • React Native for Vega + TypeScript; a Strands persona on Amazon Bedrock | [Demo video](https://youtu.be/6VNLfnK9X84) • [Code](https://github.com/juanlo7/FireDrift-AmazonDeveloper) · Amazon Developer Hackathon 2026, Fire TV track. One cover at a time from the remote. The butler proposes a title and TMDB has to confirm it before it reaches the screen. Judging is expected in December. |
| **BrewLog** · coffee extraction log, paused | Solo dev • React 19 + TypeScript + Dexie.js + Workbox | [Live app](https://brew-log-sigma.vercel.app) • [Code](https://github.com/wall3n/BrewLog) · offline-first PWA, no account and no server, data stays on the device. The project is paused. The demo stays up. |

**How X-Ray works, in short.** The score separates level (where the company is today) from trajectory (where it goes). Each indicator uses fixed anchors instead of percentiles, so a company the system never saw gets a score on the same scale. A test asserts on every entity-month that the contributions add up to the final score. A second test makes sure a month reads only data dated up to the end of that month. Every anchor, weight and threshold is in one config file that you can edit from the UI.

**How Grabbit works, in short.** You give a vague thesis and name who you trust. The agent asks two or three questions first, each with a count from Cala's funding graph, then keeps the Slush startups that sit a few rounds away from those investors, including a second ring of their usual co-investors. Every value carries a source badge. An absent field reads "Not published", never zero. Correct the report in plain words and the agent rewrites its own instructions and says so. After you leave, a watcher diffs the shortlist and alerts you when a startup moves. The model writes prose with placeholders. The server fills each number from a sourced fact, so the model never invents one.

**How FireDrift works, in short.** The feed is one title at a time. Like, skip and time on a cover change taste weights. The ranking runs in AWS Lambda and does not call a model. The butler is a Strands agent on Amazon Bedrock (Claude Haiku 4.5, with Nova 2 Lite as a fallback). It proposes `{title, year, type}`. Nothing reaches the screen unless TMDB resolves it, and the metadata comes from TMDB. Ask for something lighter and it changes the weights through a tool call, with Undo. If the agent, the voice or a cap fails, chips backed by the algorithm take over, and the feed is unaffected.

**A smaller build.** [techxdir](https://github.com/Pedrodeluna/techxdir) is a hackathon prototype and a side project, a digital badge for tech events, co-written with [@Pedrodeluna](https://github.com/Pedrodeluna) and [@elashera](https://github.com/elashera). I wrote the passwordless sign-in, the Postgres schema with row level security and the profile edge function. [Prototype](https://techxdir-web-nu.vercel.app).

**Work I cannot show.** The STEL Order code is proprietary. Besides the label module, I worked on a commercial document engine: an R&D project that generates invoices and statements from dynamic templates, with PDF/A output. It was still in development when I left, and it has no production figures.

### Experience (TL;DR)

- **Software Engineer / [LambdaLoopers](https://lambdaloopers.com/)** · *Nov 2026 to present.* Client work from the requirement to the running system: the conversation, the infrastructure, the solution design and the implementation. Fullstack, including agentic AI.
- **Software Engineer / STEL Order** · *Jan 2026 to Oct 2026.* Java 21 microservices, the accounting module, the product label module and features on a monolith with zero-downtime deploys. Spring Boot, Spring Data JPA, MySQL, Docker, GitHub Actions.
- **Software Engineer, Intern / STEL Order** · *Oct 2025 to Dec 2025.* Built a REST service from scratch: authentication, role-based access, Flyway migrations and container deployment. Wrote the CI/CD pipeline: build, integration tests and automated image publication. Spring Security, JWT, Flyway, Testcontainers, JUnit 5.
- **BSc Computer Science / University of Murcia** · *2023 to 2027.*
- **Hackathons** · HackSpain 2026 (X-Ray, Embat track, team Byte_Me). Junction 2026 in Espoo, Finland, 13 to 15 November (Grabbit). Amazon Developer Hackathon 2026 (FireDrift, Fire TV; judging expected in December).

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

- I am from Murcia, Spain, and I am an EU citizen.
- I make coffee at home and I log every extraction. That is why BrewLog exists. The app is paused, and the demo is still up.
- My portfolio has no framework and no bundler, and it has three languages. I like to see how far plain HTML, CSS and JavaScript go.

### My vision

The work I care about runs from the client's requirement to a system that is running: the conversation, the infrastructure, the design and the code. I hold it to one test, at a company and in a hackathon. A claim has to be checkable, and a number has to have a source.

---

**Contact:** [franciscomorenosanchezfms@gmail.com](mailto:franciscomorenosanchezfms@gmail.com) · [LinkedIn](https://www.linkedin.com/in/francisco-moreno-sanchez-fms) · [GitHub](https://github.com/wall3n)
