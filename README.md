<div align="center">
  <img src="./header.svg" width="100%" alt="Elmurodov Sardor"/>
</div>

<div align="center">

**Elmurodov Sardor, full-stack developer: web sites and mobile apps (React / Next.js, Flutter)**

<a href="mailto:sardor007elmurodov@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://t.me/SardorDev2010"><img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"/></a>
<a href="https://github.com/Sardor-Dev-2010"><img src="https://img.shields.io/badge/GitHub-07111F?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>

</div>

---

## About

I build two things: web sites and mobile apps. Both get the same treatment: interface, API, database, deployment.

**Web sites.** React and Next.js in front, Django REST and PostgreSQL behind them. Admin panels, SaaS dashboards, e-commerce and catalog sites.

**Mobile apps.** Flutter for Android, iOS, web and Windows, running against the same Django REST APIs. Telegram bots when a product needs one.

Either way I am the person who writes the frontend, the API and the queries, then puts the result on a real domain.

**Web stack:** React, Next.js, TypeScript, Tailwind CSS, Django REST Framework, PostgreSQL

**Mobile stack:** Flutter, Dart, Telegram bots (aiogram)

**Also:** UI/UX in Figma, LLM integration

---

## Case studies

### EVZAP, an online store in four languages

**[Live demo](https://evzap-parts.uz)** · source repo: private

<img src="./assets/evzap.jpg" alt="EVZAP storefront" width="100%"/>

**Problem.** Ready-made SaaS stores cost a lot, ship features nobody asked for, and fight you when you want a different design.

**Solution.** A Flask app with a single entry point. The catalog and the cart live in the session, so a buyer never has to create an account to place an order.

What I built:

- Catalog, cart and orders, with the cart stored in the session
- Four languages (Uzbek, Russian, English, Cyrillic) switched through Flask-Babel
- Admin panel inside the same app, with two-factor sign-in (pyotp plus QR code) and flask-bcrypt password hashing
- A Telegram bot on aiogram that reads the same database and receives orders
- Rate limiting with Flask-Limiter and CSRF protection with Flask-WTF

**Tech:** Flask 3, SQLAlchemy, Flask-Migrate, PostgreSQL, Tailwind CSS, pytest, gunicorn.

**Where it stands.** The store runs at evzap-parts.uz. The code is covered by pytest and deploys through a Procfile.

---

### This portfolio, a full-stack site with its own CMS

**[Live demo](https://sardordev-delta.vercel.app)** · source repo: private

<img src="./assets/portfolio-live.jpg" alt="Portfolio homepage" width="100%"/>

**Problem.** A portfolio assembled from a template proves nothing about how you work. I wanted the site itself to be the proof: frontend, API, admin panel, tests.

**Solution.** Next.js in front, Django REST behind it, and an admin panel so projects and case studies are edited from the browser instead of hard-coded into components.

What I built:

- Next.js 16 (App Router) with React 19, a Three.js 3D hero and framer-motion transitions
- Django REST API over PostgreSQL, with seeded projects and case studies
- Admin CMS for editing projects, skills and copy, then publishing
- Three locales (uz, en, ru) switchable on every page
- A contact form that posts through the API with server-side validation
- 26 pytest cases on the API, and a production build that runs clean

**Tech:** Next.js 16, React 19, TypeScript, Tailwind CSS, Three.js, Django REST Framework, PostgreSQL. Frontend on Vercel, API on Render.

**Where it stands.** Live at sardordev-delta.vercel.app.

---

### Geoekofauna, a species catalog for Uzbekistan

**[Live demo](https://geoecofauna.uz)** · source repo: private

<img src="./assets/geoekofauna.jpg" alt="Geoekofauna catalog" width="100%"/>

**Problem.** Species data sat inside PDFs and scattered documents. People needed one place where they could browse it and search it.

**Solution.** A React catalog in front, an API on Cloudflare Workers behind it, and one D1 database shared by the site and the Telegram bot.

What I built:

- React 19, Vite and Tailwind CSS 4 frontend, with an i18n module for language switching
- Cloudflare Workers API (auth.js, db.js, index.js) talking to a D1 (SQLite) database
- Parsing scripts that clean up the source PDFs and load them into D1
- Telegram login: the user confirms in the bot, the site verifies the signature
- Species cards, filters and PDF reports assembled on the frontend

**Where it stands.** Live at geoecofauna.uz. The backend deploys to Workers, so there is no server to keep running.

---

## More projects

| Project | What it is | Live | Source |
|---------|------------|------|--------|
| **BolaJon OS** | Kids learning app: one Flutter codebase for Android, iOS, web and Windows, Django REST backend, parent dashboard, Google OAuth | [bolajon-os.vercel.app](https://bolajon-os.vercel.app/) | private |
| **FixIt** | Platform for finding technicians in Toshkent: describe the problem, compare offers, pick someone | [fixit-chi-weld.vercel.app](https://fixit-chi-weld.vercel.app) | private |
| **Sehrli Qalpoqcha** | Real-time invisibility cloak experiment with OpenCV | none | private |
| **Aziz Academy** | Python coursework: over 1,000 exercise files across the modules I completed | none | [public](https://github.com/Sardor-Dev-2010/aziz-academy-topshiriqlar) |

<sub>Client code stays private. Every demo above is open to anyone who wants to click it.</sub>

---

## Public code

The public repository worth reading is [aziz-academy-topshiriqlar](https://github.com/Sardor-Dev-2010/aziz-academy-topshiriqlar): over 1,000 Python exercise files from my coursework, with a changelog, contribution guide and security policy. There is also [sardorbuilder-content](https://github.com/Sardor-Dev-2010/sardorbuilder-content), the image assets behind the @sardorbuilder Instagram account.

If you want to see code from the private projects, ask and I will walk you through the architecture on a call.

---

## Get in touch

<div align="center">

<a href="mailto:sardor007elmurodov@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://t.me/SardorDev2010"><img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"/></a>

<br/><br/>

<i>Open to freelance work, internships and full-time offers.</i>

</div>

<br/>
<div align="center">
  <img src="./footer.svg" width="100%" alt="Footer"/>
</div>