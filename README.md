<div align="center">

# Deepak Yadav

</div>

```bash
$ whoami
Full Stack Engineer — building AI-powered products, backend to deployment

$ focus
AI Systems · Backend Engineering · Cloud Infrastructure

$ philosophy
Build products. Solve problems. Ship software.
```

---

## Who I Am

I approach software as products, not assignments — every project starts from a real problem, not a tutorial. I build AI-powered products, scalable backend systems, and cloud-native web applications, spanning resume intelligence platforms, LLM-driven recommendation engines, and logistics systems. Each product is built to solve a real problem and refined beyond the first working version through deployment, debugging, and iteration.

I care about clean architecture over clever code — validating decisions through system design before writing implementation, then iterating based on how the system behaves once real users touch it. Debugging production systems is as much a part of my work as building them: migrating auth flows, fixing OAuth redirects, optimizing queries, and hardening deployments happen alongside new features, not after. My interests include backend architecture, distributed systems, AI integration, and developer-focused tooling.

---

## Products I've Built

### 01 · Cerevix AI
**AI-powered career intelligence platform**

Combines resume intelligence, AI mock interviewing, and career analytics into a single platform — upload a resume and a job description, get an ATS score, a keyword gap analysis, and a full mock interview built around that specific role.

**Highlights**
- Gemini-driven evaluation engine with persistent interview memory
- Contextual, adaptive follow-up question generation
- Automated resume PDF generation via Puppeteer

**Biggest Challenge**
Migrated authentication from cross-origin cookies to JWT + localStorage to eliminate cross-environment session failures, and configured dynamic CORS to support Vercel preview deployments.

**Tech Stack**

![React 19](https://img.shields.io/badge/React_19-000000?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-000000?style=flat-square&logo=nodedotjs&logoColor=339933)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-000000?style=flat-square&logo=mongodb&logoColor=47A248)
![Gemini AI](https://img.shields.io/badge/Gemini_AI-000000?style=flat-square&logo=googlegemini&logoColor=8E75B2)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=FB015B)

[Live Demo](https://cerevix-ai.vercel.app) · [Repository](https://github.com/DRSTRANGE-cloud/Cerevix-AI)

### 02 · Criticizer
**AI-powered entertainment discovery platform**

A full-stack movie and TV platform combining content discovery, community reviews, watchlists, and a conversational AI assistant into one cinematic experience.

**Highlights**
- LLM-powered chatbot (Groq) with persistent conversation history and 15-intent classification
- Dual OAuth (Google + GitHub) alongside JWT-based sessions
- Real-time TMDB data sync across ratings, reviews, and watchlists

**Production Lessons**
Rebuilt the AI assistant from a rule-based system into an LLM-powered chatbot, then diagnosed and resolved four production-breaking issues — a database migration, an OAuth redirect mismatch, and a React lifecycle bug — to stabilize the live deployment.

**Tech Stack**

![React 18](https://img.shields.io/badge/React_18-000000?style=flat-square&logo=react&logoColor=61DAFB)
![FastAPI](https://img.shields.io/badge/FastAPI-000000?style=flat-square&logo=fastapi&logoColor=009688)
![MongoDB Atlas](https://img.shields.io/badge/MongoDB_Atlas-000000?style=flat-square&logo=mongodb&logoColor=47A248)
![Groq AI](https://img.shields.io/badge/Groq_AI_(LLaMA_3)-000000?style=flat-square)
![TMDB API](https://img.shields.io/badge/TMDB_API-000000?style=flat-square&logo=themoviedatabase&logoColor=01D277)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=FB015B)

[Live Demo](https://criticizer.vercel.app) · [Repository](https://github.com/DRSTRANGE-cloud/Criticizer)

### 03 · Handmade Haven
**Production-ready artisan marketplace**

A full-stack MERN marketplace connecting artisans directly with customers — product discovery, secure checkout, role-based access, and real-time order tracking from placement to delivery.

**Highlights**
- Multiple payment gateways (PayPal + Cash on Delivery) with status tracking
- Role-based access control across customer, seller, and admin flows
- AI assistant for order queries and personalized product recommendations
- Subject of a published, peer-reviewed research paper — see **Professional Highlights** below

**Architecture Decisions**
Designed cloud-hosted backend services on MongoDB Atlas supporting concurrent order lifecycle tracking across multiple user roles, from placement through delivery confirmation.

**Tech Stack**

![React](https://img.shields.io/badge/React-000000?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-000000?style=flat-square&logo=nodedotjs&logoColor=339933)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB Atlas](https://img.shields.io/badge/MongoDB_Atlas-000000?style=flat-square&logo=mongodb&logoColor=47A248)
![Stripe](https://img.shields.io/badge/Stripe-000000?style=flat-square&logo=stripe&logoColor=635BFF)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=FB015B)

[Live Demo](https://handmade-haven-live.vercel.app) · [Repository](https://github.com/DRSTRANGE-cloud/Handmade-Haven)

### 04 · OrderSphere
**Logistics platform with SLA monitoring**

A full-stack order-fulfillment platform simulating real-world logistics — multi-role dashboards, SLA breach detection, and complete audit trails, built with Flask and raw MySQL (no ORM).

**Highlights**
- 5-stage order pipeline with a full audit log recording every status change
- MySQL FULLTEXT Boolean search with proper indexing
- Automatic SLA-breach detection (48-hour threshold) with live dashboard flagging

**System Design**
Built without an ORM abstraction layer — connection pooling, indexed full-text search, and query optimization were all handled directly to support concurrent request handling at the database level.

**Tech Stack**

![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-000000?style=flat-square&logo=mysql&logoColor=4479A1)
![Werkzeug](https://img.shields.io/badge/Werkzeug_(PBKDF2)-000000?style=flat-square)
![Jinja2](https://img.shields.io/badge/Jinja2-000000?style=flat-square&logo=jinja&logoColor=B41717)

[Repository](https://github.com/DRSTRANGE-cloud/OrderSphere)

### 05 · Melofy
**Web-based music player**

A Spotify-inspired music player built entirely in vanilla JavaScript — dynamic album loading, custom playback controls, and a fully responsive glassmorphic UI.

**Highlights**
- Dynamic album and track loading from JSON metadata, zero framework dependencies
- Custom seekbar and volume control built on the native HTML5 Audio API
- DOM update optimizations to eliminate layout shift across album transitions

**Frontend Engineering**
Built to master core frontend engineering without framework overhead — direct DOM manipulation and manual UI state management in place of a component framework.

**Tech Stack**

![HTML5](https://img.shields.io/badge/HTML5-000000?style=flat-square&logo=html5&logoColor=E34F26)
![CSS3](https://img.shields.io/badge/CSS3-000000?style=flat-square&logo=css3&logoColor=1572B6)
![JavaScript](https://img.shields.io/badge/Vanilla_JavaScript-000000?style=flat-square&logo=javascript&logoColor=F7DF1E)

[Live Demo](https://melofy1.netlify.app) · [Repository](https://github.com/DRSTRANGE-cloud/Melofy)

---

## Professional Highlights

**Cloud Computing Intern** — Heuristic Academy
*June 2024 – July 2024*

- **AWS Infrastructure** — EC2, S3, IAM
- **Cloud Networking** — VPC, subnets, NAT Gateways
- **High Availability** — ELB, Auto Scaling, Route 53
- **Monitoring & Auditing** — CloudWatch, CloudTrail

**Publication**

**"Handmade Haven: A Marketplace for Unique Artisan Creations – A Review"**
*IJPREMS, Vol. 04, Issue 11, pp. 1267–1275 — November 2024*
DOI: [10.58257/IJPREMS36923](https://www.doi.org/10.58257/IJPREMS36923)

Peer-reviewed research examining the platform's architecture and its role in connecting rural artisans directly with global consumers through technology.

[Read the Paper](https://www.ijprems.com/ijprems-paper/handmade-haven-a-marketplace-for-unique-artisan-creations--a-review)

---

## Technologies I Build With

**Languages**

![JavaScript](https://img.shields.io/badge/JavaScript-000000?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![TypeScript](https://img.shields.io/badge/TypeScript-000000?style=for-the-badge&logo=typescript&logoColor=3178C6)
![Python](https://img.shields.io/badge/Python-000000?style=for-the-badge&logo=python&logoColor=3776AB)
![Java](https://img.shields.io/badge/Java-000000?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-000000?style=for-the-badge&logo=cplusplus&logoColor=00599C)

**Frontend**

![React](https://img.shields.io/badge/React-000000?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-000000?style=for-the-badge&logo=tailwindcss&logoColor=06B6D4)
![Redux](https://img.shields.io/badge/Redux_Toolkit-000000?style=for-the-badge&logo=redux&logoColor=764ABC)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-000000?style=for-the-badge&logo=framer&logoColor=0055FF)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-000000?style=for-the-badge&logo=nodedotjs&logoColor=339933)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-000000?style=for-the-badge&logo=fastapi&logoColor=009688)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)

**Database**

![MongoDB](https://img.shields.io/badge/MongoDB-000000?style=for-the-badge&logo=mongodb&logoColor=47A248)
![MySQL](https://img.shields.io/badge/MySQL-000000?style=for-the-badge&logo=mysql&logoColor=4479A1)

**Cloud**

![AWS](https://img.shields.io/badge/AWS-000000?style=for-the-badge&logo=amazonaws&logoColor=FF9900)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-000000?style=for-the-badge&logo=render&logoColor=46E3B7)

**Developer Tools**

![Git](https://img.shields.io/badge/Git-000000?style=for-the-badge&logo=git&logoColor=F05032)
![GitHub](https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-000000?style=for-the-badge&logo=postman&logoColor=FF6C37)
![Cursor](https://img.shields.io/badge/Cursor-000000?style=for-the-badge&logo=cursor&logoColor=white)

---

<div align="center">

## Let's Build Something Great

I'm always interested in discussing backend engineering, AI-powered applications, and scalable cloud systems — and open to collaborating on meaningful software.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-000000?style=for-the-badge&logo=linkedin&logoColor=0A66C2)](https://linkedin.com/in/deepakyadav100)
[![Gmail](https://img.shields.io/badge/Email-000000?style=for-the-badge&logo=gmail&logoColor=EA4335)](mailto:deepakyadav887900@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/DRSTRANGE-cloud)

<br>

*Open to full-stack and backend engineering roles.*

</div>
