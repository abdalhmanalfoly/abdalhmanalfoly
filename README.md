
<h1 align="center">
  <span style="color:#58A6FF;">Abdalrhman Foly</span>
</h1>


<p align="center">
  <b>Backend Engineering | Full-Stack Development | ML && AI </b>
</p>

<p align="center">
  Computer Science Student at Sphinx University
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Software%20Engineering-Expertise-2563EB?style=for-the-badge&logo=codefactor&logoColor=white" />
  <img src="https://img.shields.io/badge/Backend-Development-16A34A?style=for-the-badge&logo=serverfault&logoColor=white" />
  <img src="https://img.shields.io/badge/AI-Engineering-9333EA?style=for-the-badge&logo=openai&logoColor=white" />
</p>

<p align="center">
  <a href="https://portfolio-me-main.vercel.app/">
    <img src="https://img.shields.io/badge/🌐_Portfolio-Visit_My_Website-0EA5E9?style=for-the-badge" />
  </a>
  <a href="https://github.com/abdalhmanalfoly">
    <img src="https://img.shields.io/badge/GitHub-Follow_Me-181717?style=for-the-badge&logo=github" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/abdalhmanalfoly?tab=repositories">
    <img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2Fabdalhmanalfoly&query=%24.public_repos&label=Public%20Repositories&logo=github&style=for-the-badge&color=blue" />
  </a>

 <img src="https://komarev.com/ghpvc/?username=abdalhmanalfoly&label=Profile%20Views&color=0e75b6&style=for-the-badge" /> 
</p>


---


## About Me

I'm a third-year Computer Science student at the **Faculty of Computers and Artificial Intelligence, Sphinx University**. I started in frontend development, then moved toward what interests me most: backend systems, APIs, databases, and putting AI models inside real applications.

I learn by building complete systems rather than isolated exercises, and I try to document honestly what works, what is tested, and what is still unverified.

---

## Technical Focus

| Area | What I work on |
|---|---|
| **Backend Engineering** | REST APIs, JWT authentication, role-based access control, real-time communication, relational and NoSQL data modeling |
| **Full-Stack Development** | Next.js / React frontends integrated with Node.js and Python backends |
| **AI Engineering** *(growing)* | Retrieval-Augmented Generation, embeddings and vector search with pgvector, LLM API integration |
| **Computer Vision** | Real-time webcam and multi-camera pipelines with MediaPipe and OpenCV |

---

## Tech Stack

**Languages**

<img src="https://skillicons.dev/icons?i=py,js,ts,html,css" alt="Python, JavaScript, TypeScript, HTML, CSS" />

**Backend**

<img src="https://skillicons.dev/icons?i=nodejs,express,fastapi" alt="Node.js, Express, FastAPI" />

`JWT` · `bcrypt` · `RBAC` · `Socket.IO / WebSockets` · `Zod`

**Frontend**

<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,redux" alt="React, Next.js, Tailwind CSS, Redux" />

`Zustand` · `Shadcn UI`

**Databases**

<img src="https://skillicons.dev/icons?i=mysql,postgres,mongodb,sqlite,supabase" alt="MySQL, PostgreSQL, MongoDB, SQLite, Supabase" />

`pgvector` · `Drizzle ORM` · `Neon`

**Tools and Deployment**

<img src="https://skillicons.dev/icons?i=git,github,docker,postman,vercel,vscode" alt="Git, GitHub, Docker, Postman, Vercel, VS Code" />

---

## Backend & Full-Stack Development

- Modular REST API design with middleware, input validation, and structured error handling
- Authentication flows with JWT, bcrypt password hashing, and role-based access control
- Real-time features with Socket.IO: live messaging, typing indicators, read receipts
- Frontend–backend integration with React and Next.js, including dashboards and admin panels
- Relational schema design with MySQL and PostgreSQL, plus MongoDB for document data

---

## AI & Machine Learning

I build AI features as part of larger software systems, with Python and FastAPI as my main tools.

- **Hands-on:** a RAG backend (PDF ingestion, chunking, embeddings, pgvector search, cited answers), pretrained-model integration, and basic ML experiments with Scikit-learn
- **Foundations:** the Transformer architecture and attention mechanism, studied theoretically rather than implemented from scratch
- **Next:** LLM engineering, retrieval evaluation, and tool-calling AI agents

---

## Featured Projects

### [AI Research Assistant](https://github.com/abdalhmanalfoly/ai-research-assistant-openfreemodel)
A RAG backend that answers questions over a corpus of research PDFs and returns citations with paper title, DOI/URL, and PDF page number. Retrieved chunks get app-assigned IDs and the model's citations are validated against them, so unknown references are stripped. Scanned PDFs fall back to local OCR.

`Python` `FastAPI` `PostgreSQL` `pgvector` `Alembic` `OpenRouter` `RapidOCR` `Docker Compose` `pytest`

> **Status:** unit tests and mocked-provider tests pass. The README lists what has not yet been verified end to end (a real database run, live OpenRouter calls, and retrieval-threshold calibration).

### [SAGA 3D](https://github.com/abdalhmanalfoly/SAGA3D-full-version-) — Spatial Agentic Geometric Animation
An experimental gesture-interaction system: browser-based sensors detect hand landmarks with MediaPipe and stream them to a FastAPI host over WebSockets, which handles sensor registration, multi-camera 3D fusion, and gesture recognition. A Godot 4.3 adapter consumes the result for a grab, move, and release demo. The repository documents the protocol, coordinate systems, and 400+ automated tests.

`Python` `FastAPI` `WebSockets` `MediaPipe` `Computer Vision` `Godot`

> **Status:** experimental. Calibration with real physical cameras and real-world validation are still pending.

### [Egypt Transportation Optimization Simulator](https://github.com/abdalhmanalfoly/Logistics-Simulation-Python-PySide6-Operations-Research)
A desktop application that solves transportation problems with Vogel's Approximation Method and MODI optimization, then animates the resulting logistics plan on a map of Egypt. The simulation state is a pure function of time, so play, pause, step, and scrub always match the underlying math. Includes 46 automated tests.

`Python` `PySide6` `Operations Research` `pytest`

### [Real-Time Chat](https://github.com/abdalhmanalfoly/websocketsChat)
A chat application with live messaging, typing indicators, read receipts, and message persistence.

`Node.js` `Express` `Socket.IO` `MongoDB`

### [MERN Authentication System](https://github.com/abdalhmanalfoly/full-mern-stack-auth-sys)
Sign-up with email OTP verification, cookie-based sessions with JWT, protected routes, and a password-strength indicator. The password-reset page is still in progress.

`MongoDB` `Express` `React` `Node.js` `Zustand` `Tailwind CSS`

**Also built, in private repositories:** a university dining management backend (Node.js, Express, MySQL, JWT, Socket.IO, role-based access) and backend and admin-dashboard work on a student housing platform (Next.js, Express, MySQL).

---

## GitHub Statistics

Optional: uncomment after checking that the stats service is up when you view the profile.

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=abdalhmanalfoly&show_icons=true&hide_border=true" alt="GitHub stats" />
</p>


See my [repositories](https://github.com/abdalhmanalfoly?tab=repositories) for current activity.

---

## Current Learning Journey

- **NestJS** for structured, scalable backend architecture
- **Docker** beyond local development, toward production deployment
- **LLM engineering:** embeddings, retrieval quality, and context management
- **AI agents:** tool calling and multi-step workflows

---

## Contact

- Portfolio: [portfolio-me-main.vercel.app](https://portfolio-me-main.vercel.app/)
- GitHub: [@abdalhmanalfoly](https://github.com/abdalhmanalfoly)
