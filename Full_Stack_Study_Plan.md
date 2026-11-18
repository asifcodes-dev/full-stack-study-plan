# Full Stack Developer Study Plan (Basic to Advanced)

**Track:** React + TypeScript (frontend) · Java + Spring Boot (backend) · SQL/NoSQL · Docker/K8s/AWS · System Design
**Length:** 26 weeks (about 6 months) at 2–3 hours on weekdays and 4–5 hours on weekends
**Why this stack:** most of your folder is Java (Java complete, Collections, Streams, Spring Boot, SOLID, OOPs, 70 DSA Java solutions), so Java/Spring Boot is your strongest backend path. Node.js is covered as a second backend in Phase 4.

---

## How to use your folder

Your files fall into four groups:

| Group | Files | Use |
|---|---|---|
| **Core (study these)** | Java, Spring Boot, JS, TypeScript, Angular, NodeJs, SQL/Postgres/Mongo/Redis, Rest Api, Git, Linux, Docker, Kubernetes, AWS, Kafka, Elasticsearch, System Design, DSA sheets | The main curriculum below |
| **Interview revision** | `600 + questions\*` and the duplicates in the root, `Top 30 ReachJs question`, `50 Oops question`, `Java Tricky`, `Git interview` | End-of-week self-test |
| **Bonus (later)** | GenAi, AI Agent For Developers, Mcp for dev, Vector database notes, Ai handbook, Playwright, Selenium, Rest Assured, Postman, Performance Testing, Jira | Phases 5–6 |
| **Not needed for full stack** | Calculus, Integral, Limit Continuity, Linear algebra, Trigonometry, Engineering/Discrete Maths, Compiler Design, Theory of Computation, Computer Graphics, Digital, 8086, ESP32 & LoRa, CCNP, Data Mining, Deep Learning, Machine Learning, Excel, Time & Work, Ratio & Proportion, TCS NQT | Skip, or only for college exams and aptitude tests |

**Gaps in your folder (use the free resources listed):**
- HTML/CSS: you only have interview questions → [MDN Learn](https://developer.mozilla.org/en-US/docs/Learn), [web.dev Learn CSS](https://web.dev/learn/css)
- React: only interview questions → [react.dev/learn](https://react.dev/learn)
- Express.js, authentication (JWT/OAuth2), web security (OWASP), CI/CD (GitHub Actions), Next.js → links in each phase

**Daily routine:** 60% build, 25% read your notes, 15% DSA (1–2 problems).
**Weekly routine:** Sunday = revise the week with the matching file in `600 + questions` and push the week's code to GitHub.

---

## Phase 0 — Foundations (Weeks 1–2)

| Week | Topics | Your files | Build |
|---|---|---|---|
| 1 | How the web works (HTTP, DNS, client/server), terminal, Linux commands, file permissions | `Linux pdf`, `Computer Networks notes 1` (only the HTTP/TCP/DNS parts) | Install VS Code, Git, Node LTS, JDK 21, IntelliJ, Docker Desktop |
| 2 | Git: init, commit, branch, merge, rebase, PRs, resolving conflicts, GitHub | `Git Notes`, `Git top 20 concepts`, `Git interview`, `Git_GitHub_Interview_Questions` | Create a GitHub profile and a `learning-log` repo; commit every day from now on |

---

## Phase 1 — Frontend Basics (Weeks 3–7)

| Week | Topics | Your files / resources | Build |
|---|---|---|---|
| 3 | HTML5 semantics, forms, accessibility basics, CSS box model, selectors, specificity | MDN, `HTML_CSS_Interview_Questions` | Personal profile page |
| 4 | Flexbox, Grid, responsive design, media queries, CSS variables; Tailwind intro | web.dev Learn CSS | Responsive landing page (mobile first) |
| 5 | JavaScript core: types, scope, hoisting, closures, `this`, arrays/objects, ES6+ (destructuring, spread, modules) | `Java script 2`, `JavaScript_Interview_Questions` | Todo app in vanilla JS |
| 6 | DOM, events, event loop, promises, async/await, `fetch`, localStorage, error handling | `Java script 2` | Weather app using a public API |
| 7 | TypeScript: types, interfaces, generics, unions, narrowing, utility types, `tsconfig` | `Typescript`, `Typescript 2` | Convert the weather app to TypeScript |

**Checkpoint:** deploy both apps free on GitHub Pages, Netlify or Vercel.

---

## Phase 2 — Backend with Java + Spring Boot (Weeks 8–13)

| Week | Topics | Your files | Build |
|---|---|---|---|
| 8 | Java basics: syntax, OOP (class, object, inheritance, polymorphism, abstraction, interfaces), exceptions | `Java complete`, `Java Interface Abstraction`, `50 Oops question`, `Java Star Pattern` | Bank account console app |
| 9 | Collections (List, Set, Map, HashMap internals), generics, Streams, lambdas, Optional | `Collections`, `Java collection Shortcuts`, `Java Stream and Lambda expressions`, `Java Tricky` | Student records manager using Streams |
| 10 | JVM memory model, garbage collection, multithreading basics, SOLID, design patterns (Singleton, Factory, Builder, Strategy) | `JEV Model`, `SOLID Principle`, `Java_Interview_Questions` | Refactor week-8 app using SOLID |
| 11 | REST principles, HTTP methods and status codes; Spring Boot: IoC/DI, beans, controllers, services, validation, exception handling | `Rest Api`, `Spring boot 30 concepts`, `Postman Notes` | CRUD REST API (in-memory), tested in Postman |
| 12 | Spring Data JPA + Hibernate, entities, relationships, pagination, DTOs, profiles/config | `Spring boot 30 concepts`, `SpringBoot_Interview_Questions` | Connect the API to PostgreSQL |
| 13 | Spring Security, JWT authentication, roles, CORS, password hashing; testing with JUnit 5 + Mockito | [spring.io/guides](https://spring.io/guides), [OWASP Top 10](https://owasp.org/www-project-top-ten/) | Add login/signup and protected routes |

---

## Phase 3 — Databases (Weeks 14–16)
*(Start the SQL part alongside Week 12.)*

| Week | Topics | Your files | Build |
|---|---|---|---|
| 14 | SQL: SELECT, JOINs, GROUP BY, HAVING, subqueries, CTEs, window functions | `Sql Sheet`, `Sql cheat sheet`, `Sql important cheat sheet`, `Sql part 2`, `Advance SQL concepts`, `SQL_Interview_Questions` | Solve 30 problems on LeetCode SQL 50 |
| 15 | DBMS theory: normalization, ACID, transactions, isolation levels, indexing, query plans; PostgreSQL specifics | `DBMS`, `Crafted_Note Dbms`, `ACID properties`, `Db indexing`, `PostgreSql` | Design the schema for your capstone (ER diagram) |
| 16 | NoSQL: MongoDB (documents, aggregation); Redis (caching, TTL, sessions, rate limiting) | `Mongo db`, `Redis` | Add Redis caching to the Spring Boot API |

Skip `Copy of Sql part 2` (duplicate).

---

## Phase 4 — Modern Frontend + Full Stack Integration (Weeks 17–20)

| Week | Topics | Your files / resources | Build |
|---|---|---|---|
| 17 | React: components, JSX, props, state, `useState`, `useEffect`, lists/keys, forms | react.dev, `Top 30 ReachJs question`, `React_NodeJS_Interview` | Rebuild the todo app in React + TS (Vite) |
| 18 | React Router, `useContext`, custom hooks, `useMemo`/`useCallback`, TanStack Query, Zustand or Redux Toolkit | react.dev | Dashboard that consumes your Spring Boot API |
| 19 | **Full stack project 1:** React + Spring Boot + PostgreSQL + JWT auth, deployed | — | e.g. Expense tracker or Job board |
| 20 | Node.js + Express (second backend): event loop, modules, middleware, REST, Mongoose; Next.js basics | `NodeJs`, [expressjs.com](https://expressjs.com), [nextjs.org/learn](https://nextjs.org/learn) | Same API rebuilt in Express + MongoDB |

**Optional:** `Angular.pdf`, only if a target company uses Angular. Learn one framework (React) deeply first.

---

## Phase 5 — DevOps, Cloud, Testing (Weeks 21–23)

| Week | Topics | Your files | Build |
|---|---|---|---|
| 21 | Docker: images, Dockerfile, volumes, networks, docker-compose; CI/CD with GitHub Actions | `Docker notes`, `Docker Revision notes`, `Docker top 10 concept`, `Docker_Interview_Questions` | Dockerize project 1 (frontend + API + DB in compose); CI that runs tests on each push |
| 22 | AWS: EC2, S3, RDS, IAM, VPC basics, Load Balancer; Kubernetes: pods, deployments, services, ingress | `Aws notes`, `Cloud computing`, `Kubernates Notes` | Deploy project 1 on AWS (EC2 + RDS, or free tier); run it on a local K8s with minikube |
| 23 | Testing: unit/integration, API testing, E2E with Playwright; Agile/Jira workflow | `Playwright`, `Playwright cheat sheet`, `Rest Assured`, `Postman Notes`, `Manual testing`, `Jira notes` | Add Playwright E2E tests to project 1 |

Selenium and Performance Testing notes are optional (more useful for QA roles).

---

## Phase 6 — Advanced: System Design, Scale, AI (Weeks 24–26)

| Week | Topics | Your files | Build |
|---|---|---|---|
| 24 | System design: scalability, load balancing, caching, CDN, sharding, replication, CAP theorem, microservices, API gateway, rate limiting | `System design part 1`, `System design part 2`, `System Design 1.png` (Zomato), `System design 2.png`, `System_Design_Interview_Questions` | Draw designs for URL shortener, Zomato and a chat app |
| 25 | Messaging and search: Kafka, RabbitMQ, event-driven architecture, Elasticsearch; WebSockets | `Kafka cheat sheet`, `Kafka RabitMQ`, `Elastic search` | **Capstone:** split project 1 into 2–3 microservices with Kafka + notifications |
| 26 | AI for developers: LLM APIs, RAG, vector databases, AI agents, MCP; using AI coding tools well | `GenAi`, `AI Agent For Developers`, `Mcp for dev`, `Vector database notes`, `Ai handbook` | Add an AI feature (e.g. "chat with your data" using RAG) to the capstone |

---

## DSA track (runs in parallel, every day, 30–45 min)

| Weeks | Topic | Your files |
|---|---|---|
| 1–4 | Time complexity, arrays, strings, patterns | `Time complexity`, `Array & String problems`, `Java Star Pattern`, `Python Pattern` |
| 5–8 | Recursion, sorting, searching, two pointers, sliding window | `Recursion`, `Sorting And Searching`, `Coding Pattern` |
| 9–13 | Stack, queue, linked list, hashing | `Stack & Quoue` |
| 14–19 | Trees, BST, heaps, graphs (BFS/DFS, shortest path) | `Tree & Graph`, `Tree and Graph` |
| 20–26 | DP, greedy, backtracking; mixed practice | `DSASheet`, `70 DSA Java Interview Solutions`, `DSA_Interview_Questions` |

Target: **about 200 problems** by week 26 (follow DSASheet order; use LeetCode or GeeksforGeeks).

---

## Portfolio by the end

1. Responsive landing page + vanilla JS apps (Phase 1)
2. Full stack app: React + Spring Boot + PostgreSQL + JWT, Dockerized, CI/CD, deployed on AWS
3. Node/Express + MongoDB version of an API
4. Microservices capstone with Kafka, Redis, Elasticsearch search and an AI/RAG feature
5. GitHub with daily commits, READMEs and architecture diagrams

## Interview prep (Weeks 25–26, and keep going)

- Go through every file in `600 + questions` once more: JavaScript → React_NodeJS → Java → SpringBoot → SQL → Git → Docker → System Design → DSA
- 2 mock interviews per week (Pramp or with friends)
- Python notes (`Python *`) are optional, only for Python-based roles or the AI week
