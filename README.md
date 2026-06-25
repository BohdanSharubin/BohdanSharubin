# Hey, I'm Bohdan 👋

**Backend Developer** focused on building scalable server-side applications.
My primary stack is **Node.js** — I enjoy designing clean REST APIs, working with databases, and structuring code that's easy to maintain and extend. I'm also expanding into **Java**, where I build desktop and backend applications using the JVM ecosystem.

---

## 🛠️ Tech Stack

### Primary — Node.js Backend
<p>
  <img src="https://skillicons.dev/icons?i=nodejs,express,js,ts,mongodb,postgres,prisma" />
</p>

### Secondary — Java
<p>
  <img src="https://skillicons.dev/icons?i=java,maven,junit" />
</p>

### Tools & DevOps
<p>
  <img src="https://skillicons.dev/icons?i=git,github,githubactions,bash" />
</p>

---

## 📌 Pinned Projects

### 🟢 Node.js — REST API & Fullstack Development

#### [state-authorities-app](https://github.com/BohdanSharubin/state-authorities-app)
A production-ready fullstack monorepo platform designed for tracking state authority directory metadata and automating government news aggregation. 

- **Fullstack Infrastructure:** Connected a modular Express backend to a React frontend, implementing robust directory navigation and a comprehensive administrative control panel with full CRUD operations for state agencies.
- **Automated Ingestion Workers:** Developed specialized crawlers (including a Cabinet of Ministers of Ukraine - KMU parser) paired with a **Gemini AI-driven News Service** featuring layout-adaptive, self-healing CSS selectors.
- **Database Optimization:** Eliminated redundant write cycles by replacing heavy transaction `upsert` queries with pre-validated lookups (`Set` mapping algorithms) before executing batch inserts into PostgreSQL.
- **Memory & Telemetry Hardening:** Optimized cloud runtime stability on Render within a 512MB RAM budget by constraining the V8 engine (`--max-old-space-size=384`) and configuring unbuffered real-time logging via Winston.
- **Security & Standards:** Migrated data layers onto **Prisma v7**, restricted mass CSV data import/export routes behind strict token-validation layers, and enforced **Biome** for strict code quality linting.

**Stack:** `TypeScript` · `Node.js` · `Express.js` · `React` · `Prisma v7` · `PostgreSQL (Neon)` · `Gemini API` · `Puppeteer` · `Winston` · `Biome`

---

#### [online-store](https://github.com/BohdanSharubin/online-store)
A full-featured e-commerce REST API built with **Node.js + Express.js + MongoDB**.
 
- JWT authentication via **HttpOnly cookies** & role-based authorization (user / admin)
- **CORS** configured for cross-origin requests
- Full CRUD for products with pagination and category filtering
- Service layer separating business logic from controllers
- Joi validation, centralized error handling, `asyncHandler` middleware
- Clean architecture: Routes → Controllers → Services → Models
- **Static HTML pages:** login, registration, add product, product list

**Stack:** `Node.js v24` · `Express.js v5` · `Mongoose` · `JWT` · `Joi` · `bcryptjs` · `cookie-parser` · `cors`

---

#### [posts-comments-api](https://github.com/BohdanSharubin/posts-comments-api)
A RESTful API for managing posts and their comments (1:N relationship).

- Full CRUD for posts and comments
- Pagination and search functionality
- Request validation via `express-validator`
- Centralized error handling with custom error classes

**Stack:** `Node.js` · `Express.js` · `MongoDB` · `Mongoose` · `express-validator` · `dotenv`

---

#### [web-technologies](https://github.com/BohdanSharubin/web-technologies)
University course project covering modern web technologies.

**Stack:** `TypeScript` · `HTML5` · `CSS3` · `Javascript(ES6+)`

---

#### [ukraine-law-parser](https://github.com/BohdanSharubin/ukraine-law-parser)
A parser for Ukrainian legislative documents.

**Stack:** `TypeScript` · `Node.js` · `Express.js` · `Axios` · `PostgreSQL 16` · `Cheerio` · `PDF-parse` · `Prisma`

---

#### [postgres-fk-benchmark](https://github.com/BohdanSharubin/postgres-fk-benchmark)
Benchmarking foreign key performance in PostgreSQL — a performance research project.

**Stack:** `Shell` · `PostgreSQL` · `Docker`

---

### 🟠 Java — Desktop Application

#### [movie-desktop-cms](https://github.com/BohdanSharubin/movie-desktop-cms)
A desktop CMS for managing movie data, built as a team student project. I served as **Team Lead** — responsible for architecture, code reviews, and coordination.

- Full CRUD for movies (browse, search, add, edit, delete)
- Layered architecture: UI → Controllers → Services → DAO → DB
- PostgreSQL for persistent storage
- CI/CD via GitHub Actions (build, tests, Javadoc deploy to GitHub Pages)
- UML documentation: use-case diagram, class diagram, ER diagram

**Stack:** `Java 17` · `JavaFX` · `PostgreSQL 16` · `Maven` · `JUnit 5` · `GitHub Actions`

---

## 📫 Connect

[![GitHub](https://img.shields.io/badge/GitHub-BohdanSharubin-181717?style=flat&logo=github)](https://github.com/BohdanSharubin)

```
