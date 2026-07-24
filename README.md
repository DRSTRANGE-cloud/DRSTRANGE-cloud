<div align="center">

# Deepak Yadav

### Full Stack Engineer • AI • Backend • Cloud

Designing and shipping AI-powered software products with a focus on scalable backend systems, cloud infrastructure, and modern web experiences.

</div>

---

## At a Glance

| | |
|---|---|
| **Products shipped** | 5 deployed, production-live applications |
| **AI integration** | Google Gemini · Groq (LLaMA 3) · LLM-powered assistants |
| **Cloud & infrastructure** | AWS · Vercel · Render |
| **Security** | JWT · OAuth · IAM |
| **Research** | Published, IJPREMS, November 2024 |

---

## Engineering Mindset

I approach software as products, not assignments — every project starts from a real problem, not a tutorial. I care about clean architecture over clever code: validating decisions through system design before writing implementation, then iterating based on how the system actually behaves once real users touch it.

Debugging production systems is as much a part of my work as building them — migrating auth flows, fixing OAuth redirects, optimizing database queries, and hardening deployments happen alongside writing new features, not after.

---

## Building Beyond the Classroom

Full-stack developer building AI-powered products, scalable backend systems, and cloud-native web applications — spanning resume intelligence platforms, LLM-driven recommendation engines, and logistics systems. Each one deployed and shaped by real usage, not just coursework.

My interests include backend architecture, distributed systems, AI integration, cloud-native applications, and developer-focused tooling.

---

## Products I've Built

<br>

### 01 · Cerevix AI
**AI-powered career intelligence platform**

Combines resume intelligence, AI mock interviewing, and career analytics into a single platform — upload a resume and a job description, get an ATS score, a keyword gap analysis, and a full mock interview built around that specific role.

**Highlights**
- Gemini-driven evaluation engine with persistent interview memory
- Contextual, adaptive follow-up question generation
- Automated resume PDF generation via Puppeteer

**Engineering Challenges**
Migrated authentication from cross-origin cookies to JWT + localStorage to eliminate cross-environment session failures, and configured dynamic CORS to support Vercel preview deployments.

**Tech Stack**
`React 19` `Node.js` `Express.js` `MongoDB` `Google Gemini AI` `JWT`

[Live Demo](https://cerevix-ai.vercel.app) · [Repository](https://github.com/DRSTRANGE-cloud/Cerevix-AI)

<br>

### 02 · Criticizer
**AI-powered entertainment discovery platform**

A full-stack movie and TV platform combining content discovery, community reviews, watchlists, and a conversational AI assistant into one cinematic experience.

**Highlights**
- LLM-powered chatbot (Groq) with persistent conversation history and 15-intent classification
- Dual OAuth (Google + GitHub) alongside JWT-based sessions
- Real-time TMDB data sync across ratings, reviews, and watchlists

**Engineering Challenges**
Rebuilt the AI assistant from a rule-based system into an LLM-powered chatbot, then diagnosed and resolved four production-breaking issues — a database migration, an OAuth redirect mismatch, and a React lifecycle bug — to stabilize the live deployment.

**Tech Stack**
`React 18` `FastAPI` `MongoDB Atlas` `Groq AI (LLaMA 3)` `TMDB API` `JWT`

[Live Demo](https://criticizer.vercel.app) · [Repository](https://github.com/DRSTRANGE-cloud/Criticizer)

<br>

### 03 · Handmade Haven
**Production-ready artisan marketplace**

A full-stack MERN marketplace connecting artisans directly with customers — product discovery, secure checkout, role-based access, and real-time order tracking from placement to delivery.

**Highlights**
- Multiple payment gateways (PayPal + Cash on Delivery) with status tracking
- Role-based access control across customer, seller, and admin flows
- AI assistant for order queries and personalized product recommendations
- Subject of a published, peer-reviewed research paper — see **Publication** below

**Engineering Challenges**
Designed cloud-hosted backend services on MongoDB Atlas supporting concurrent order lifecycle tracking across multiple user roles, from placement through delivery confirmation.

**Tech Stack**
`React` `Node.js` `Express.js` `MongoDB Atlas` `Stripe` `JWT`

[Live Demo](https://handmade-haven-live.vercel.app) · [Repository](https://github.com/DRSTRANGE-cloud/Handmade-Haven)

<br>

### 04 · OrderSphere
**Logistics platform with SLA monitoring**

A full-stack order-fulfillment platform simulating real-world logistics — multi-role dashboards, SLA breach detection, and complete audit trails, built with Flask and raw MySQL (no ORM).

**Highlights**
- 5-stage order pipeline with a full audit log recording every status change
- MySQL FULLTEXT Boolean search with proper indexing
- Automatic SLA-breach detection (48-hour threshold) with live dashboard flagging

**Engineering Challenges**
Built without an ORM abstraction layer — connection pooling, indexed full-text search, and query optimization were all handled directly to support concurrent request handling at the database level.

**Tech Stack**
`Flask` `MySQL` `Werkzeug (PBKDF2)` `Jinja2`

[Repository](https://github.com/DRSTRANGE-cloud/OrderSphere)

<br>

### 05 · Melofy
**Web-based music player**

A Spotify-inspired music player built entirely in vanilla JavaScript — dynamic album loading, custom playback controls, and a fully responsive glassmorphic UI.

**Highlights**
- Dynamic album and track loading from JSON metadata, zero framework dependencies
- Custom seekbar and volume control built on the native HTML5 Audio API
- DOM update optimizations to eliminate layout shift across album transitions

**Engineering Challenges**
Built to master core frontend engineering without framework overhead — direct DOM manipulation and manual UI state management in place of a component framework.

**Tech Stack**
`HTML5` `CSS3` `Vanilla JavaScript`

[Live Demo](https://melofy1.netlify.app) · [Repository](https://github.com/DRSTRANGE-cloud/Melofy)

---

## Tech Arsenal

| Category | Technologies |
|---|---|
| Languages | JavaScript · TypeScript · Python · Java · C++ |
| Frontend | React · Next.js · Tailwind CSS · Redux Toolkit · Framer Motion |
| Backend | Node.js · Express.js · FastAPI · Flask |
| Database | MongoDB · MySQL |
| Cloud | AWS · Vercel · Render |
| Tools | Git · GitHub · Postman · Cursor |

---

## Experience

**Cloud Computing Intern** — Heuristic Academy
*June 2024 – July 2024*

- AWS Infrastructure — EC2, S3, IAM
- Cloud Networking — VPC, subnets, NAT Gateways
- High Availability — ELB, Auto Scaling, Route 53
- Monitoring & Auditing — CloudWatch, CloudTrail

---

## Publication

**"Handmade Haven: A Marketplace for Unique Artisan Creations – A Review"**
*IJPREMS, Vol. 04, Issue 11, pp. 1267–1275 — November 2024*
DOI: [10.58257/IJPREMS36923](https://www.doi.org/10.58257/IJPREMS36923)

Peer-reviewed research examining the platform's architecture and its role in connecting rural artisans directly with global consumers through technology.

[Read the Paper](https://www.ijprems.com/ijprems-paper/handmade-haven-a-marketplace-for-unique-artisan-creations--a-review)

---

## GitHub Stats

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=DRSTRANGE-cloud&show_icons=true&hide_border=true&bg_color=00000000&title_color=58A6FF&text_color=8B949E&icon_color=58A6FF" width="49%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DRSTRANGE-cloud&layout=compact&hide_border=true&bg_color=00000000&title_color=58A6FF&text_color=8B949E" width="49%" />
</div>

---

<div align="center">

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-000000?style=flat-square&logo=linkedin&logoColor=0A66C2)](https://linkedin.com/in/deepakyadav100)
[![Gmail](https://img.shields.io/badge/Email-000000?style=flat-square&logo=gmail&logoColor=EA4335)](mailto:deepakyadav887900@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-000000?style=flat-square&logo=github&logoColor=white)](https://github.com/DRSTRANGE-cloud)

<br>

*Open to full-stack and backend engineering roles — let's build something.*

</div>
