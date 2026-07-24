<div align="center">

# Deepak Yadav

### Engineering AI-powered products — from backend architecture to production deployment.

Full Stack Engineer specializing in scalable systems, cloud infrastructure, and applied AI.

</div>

---

## At a Glance

<div align="center">

| 5 | 3 | 3 | 1 |
|:---:|:---:|:---:|:---:|
| Products Shipped | AI-Powered Apps | Cloud Platforms | Published Paper |

</div>

---

## Engineering Mindset

I approach software as products, not assignments — every project starts from a real problem, not a tutorial. I care about clean architecture over clever code: validating decisions through system design before writing implementation, then iterating based on how the system actually behaves once real users touch it.

Debugging production systems is as much a part of my work as building them — migrating auth flows, fixing OAuth redirects, optimizing database queries, and hardening deployments happen alongside writing new features, not after.

---

## Building Beyond the Classroom

Full-stack developer building AI-powered products, scalable backend systems, and cloud-native web applications — spanning resume intelligence platforms, LLM-driven recommendation engines, and logistics systems. Each product is built to solve a real problem and refined beyond the first working version through deployment, debugging, and iteration.

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

**Languages**

![JavaScript](https://img.shields.io/badge/JavaScript-000000?style=flat-square&logo=javascript&logoColor=F7DF1E)
![TypeScript](https://img.shields.io/badge/TypeScript-000000?style=flat-square&logo=typescript&logoColor=3178C6)
![Python](https://img.shields.io/badge/Python-000000?style=flat-square&logo=python&logoColor=3776AB)
![Java](https://img.shields.io/badge/Java-000000?style=flat-square&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-000000?style=flat-square&logo=cplusplus&logoColor=00599C)

**Frontend**

![React](https://img.shields.io/badge/React-000000?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-000000?style=flat-square&logo=tailwindcss&logoColor=06B6D4)
![Redux](https://img.shields.io/badge/Redux_Toolkit-000000?style=flat-square&logo=redux&logoColor=764ABC)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-000000?style=flat-square&logo=framer&logoColor=0055FF)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-000000?style=flat-square&logo=nodedotjs&logoColor=339933)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-000000?style=flat-square&logo=fastapi&logoColor=009688)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)

**Database**

![MongoDB](https://img.shields.io/badge/MongoDB-000000?style=flat-square&logo=mongodb&logoColor=47A248)
![MySQL](https://img.shields.io/badge/MySQL-000000?style=flat-square&logo=mysql&logoColor=4479A1)

**Cloud**

![AWS](https://img.shields.io/badge/AWS-000000?style=flat-square&logo=amazonaws&logoColor=FF9900)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-000000?style=flat-square&logo=render&logoColor=46E3B7)

**Developer Tools**

![Git](https://img.shields.io/badge/Git-000000?style=flat-square&logo=git&logoColor=F05032)
![GitHub](https://img.shields.io/badge/GitHub-000000?style=flat-square&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-000000?style=flat-square&logo=postman&logoColor=FF6C37)
![Cursor](https://img.shields.io/badge/Cursor-000000?style=flat-square&logo=cursor&logoColor=white)

---

## Experience

**Cloud Computing Intern** — Heuristic Academy
*June 2024 – July 2024*

- **AWS Infrastructure** — EC2, S3, IAM
- **Cloud Networking** — VPC, subnets, NAT Gateways
- **High Availability** — ELB, Auto Scaling, Route 53
- **Monitoring & Auditing** — CloudWatch, CloudTrail

---

## Publication

**"Handmade Haven: A Marketplace for Unique Artisan Creations – A Review"**
*IJPREMS, Vol. 04, Issue 11, pp. 1267–1275 — November 2024*
DOI: [10.58257/IJPREMS36923](https://www.doi.org/10.58257/IJPREMS36923)

Peer-reviewed research examining the platform's architecture and its role in connecting rural artisans directly with global consumers through technology.

[Read the Paper](https://www.ijprems.com/ijprems-paper/handmade-haven-a-marketplace-for-unique-artisan-creations--a-review)

---

<div align="center">

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-000000?style=flat-square&logo=linkedin&logoColor=0A66C2)](https://linkedin.com/in/deepakyadav100)
[![Gmail](https://img.shields.io/badge/Email-000000?style=flat-square&logo=gmail&logoColor=EA4335)](mailto:deepakyadav887900@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-000000?style=flat-square&logo=github&logoColor=white)](https://github.com/DRSTRANGE-cloud)

<br>

*Open to full-stack and backend engineering roles.*

</div>
