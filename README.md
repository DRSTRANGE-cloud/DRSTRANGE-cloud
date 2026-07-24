<div align="center">

# Deepak Yadav

### Full Stack Engineer

Building intelligent software products that solve real-world problems.

</div>

<br>

## Engineering Mindset

I approach software as products, not assignments — every project I ship starts from a real problem, not a tutorial. My focus sits at the intersection of **backend architecture**, **AI integration**, and **cloud deployment**: designing systems that stay reliable once real users, real data, and real edge cases show up.

I care about clean architecture over clever code, and about debugging production systems as much as building them — migrating auth flows, fixing OAuth redirects, optimizing database queries, and hardening deployments are as much a part of my work as writing new features.

<br>

## About Me

Full-stack developer building AI-powered products, scalable backend systems, and cloud-native web applications. My work spans resume intelligence platforms, LLM-driven recommendation engines, and logistics systems — each one deployed, load-tested by real usage, and iterated on past the first working version.

Currently focused on backend architecture, system design, and applied AI integration in production software.

<br>

## Products I've Built

<br>

### 01 · Cerevix AI
**AI-powered career intelligence platform**

Combines resume intelligence, AI mock interviewing, and career analytics into a single platform — upload a resume and a job description, get an ATS score, a keyword gap analysis, and a full mock interview built around that specific role.

Built to replace generic interview prep with feedback tied to an actual job description, not templated advice. Engineered a Gemini-driven evaluation system with persistent interview memory and contextual follow-up questions, migrated authentication from cross-origin cookies to JWT + localStorage to eliminate cross-environment session failures, configured dynamic CORS for Vercel preview deployments, and automated resume PDF generation with Puppeteer.

`React 19` `Node.js` `Express.js` `MongoDB` `Google Gemini AI` `JWT`

[Live Demo](https://cerevix-ai.vercel.app) · [Repository](https://github.com/DRSTRANGE-cloud/Cerevix-AI)

<br>

### 02 · Criticizer
**AI-powered entertainment discovery platform**

A full-stack movie and TV platform combining content discovery, community reviews, watchlists, and a conversational AI assistant into one cinematic experience.

Rebuilt the AI assistant from a rule-based system into an LLM-powered chatbot using Groq, with persistent conversation history and 15-intent classification. Diagnosed and resolved four production-breaking issues — a database migration, an OAuth redirect mismatch, and a React lifecycle bug — to stabilize the live deployment, and implemented dual OAuth (Google + GitHub) alongside JWT-based sessions.

`React 18` `FastAPI` `MongoDB Atlas` `Groq AI (LLaMA 3)` `TMDB API` `JWT`

[Live Demo](https://criticizer.vercel.app) · [Repository](https://github.com/DRSTRANGE-cloud/Criticizer)

<br>

### 03 · Handmade Haven
**Production-ready artisan marketplace**

A full-stack MERN marketplace connecting artisans directly with customers — product discovery, secure checkout, role-based access, and real-time order tracking from placement to delivery.

Integrated multiple payment gateways (PayPal and Cash on Delivery) with status tracking, built role-based access control across customer, seller, and admin flows, and developed an AI assistant for order queries and personalized product recommendations layered into the shopping experience. Subject of a published research paper — see **Research** below.

`React` `Node.js` `Express.js` `MongoDB Atlas` `Stripe` `JWT`

[Live Demo](https://handmade-haven-live.vercel.app) · [Repository](https://github.com/DRSTRANGE-cloud/Handmade-Haven)

<br>

### 04 · OrderSphere
**Logistics platform with SLA monitoring**

A full-stack order-fulfillment platform simulating real-world logistics — multi-role dashboards, SLA breach detection, and complete audit trails, built with Flask and raw MySQL (no ORM).

Designed a 5-stage order pipeline with a full audit log recording every status change by actor and timestamp, implemented MySQL FULLTEXT Boolean search with proper indexing to avoid N+1 query patterns, built automatic SLA-breach detection with live dashboard flagging, and used connection pooling to handle concurrent requests without an ORM abstraction layer.

`Flask` `MySQL` `Werkzeug (PBKDF2)` `Jinja2`

[Repository](https://github.com/DRSTRANGE-cloud/OrderSphere)

<br>

### 05 · Melofy
**Web-based music player**

A Spotify-inspired music player built entirely in vanilla JavaScript — dynamic album loading, custom playback controls, and a fully responsive glassmorphic UI.

Built to master core frontend engineering without framework overhead: dynamic album and track loading from JSON metadata, a custom seekbar and volume control built on the native HTML5 Audio API, and DOM update optimizations to eliminate layout shift across album transitions.

`HTML5` `CSS3` `Vanilla JavaScript`

[Live Demo](https://melofy1.netlify.app) · [Repository](https://github.com/DRSTRANGE-cloud/Melofy)

<br>

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

<br>

## Experience

**Cloud Computing Intern** — Heuristic Academy
*June 2024 – July 2024*

Hands-on AWS training across EC2, S3, IAM, VPC, ELB, Auto Scaling, RDS, CloudWatch, and Route 53 — configuring secure networking, highly available architectures, and infrastructure monitoring following AWS best practices.

<br>

## Research

**"Handmade Haven: A Marketplace for Artisan Creations"**
*IJPREMS, Vol. 04, Issue 11 — November 2024*

Published research examining the platform's architecture and its role in connecting artisan sellers with a digital marketplace.

<br>

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-000000?style=flat-square&logo=linkedin&logoColor=0A66C2)](https://linkedin.com/in/deepakyadav100)
[![Gmail](https://img.shields.io/badge/Email-000000?style=flat-square&logo=gmail&logoColor=EA4335)](mailto:deepakyadav887900@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-000000?style=flat-square&logo=github&logoColor=white)](https://github.com/DRSTRANGE-cloud)

</div>
