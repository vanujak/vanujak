<h1 align="center">Hi 👋, I'm Vanuja Karunaratne</h1>
<h3 align="center">Computer Engineering Undergraduate · Full-Stack Developer · Sri Lanka</h3>

<p align="center">
  <a href="mailto:vanujakofficial@gmail.com"><img src="https://img.shields.io/badge/Email-vanujakofficial%40gmail.com-red?style=flat-square&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/vanujak"><img src="https://img.shields.io/badge/GitHub-vanujak-181717?style=flat-square&logo=github&logoColor=white"/></a>
  <img src="https://komarev.com/ghpvc/?username=vanujak&style=flat-square&color=brightgreen" alt="profile views"/>
</p>

---

## 🧑‍💻 About Me

- 🎓 BSc Engineering in **Computer Engineering** at the University of Ruhuna, Sri Lanka
- 🌱 Currently building full-stack applications and exploring **distributed systems** and **DevOps**
- ⚡ Passionate about clean architecture, CI/CD pipelines, and scalable system design
- 📍 Based in Ratnapura, Sri Lanka

---

## 🛠️ Tech Stack

**Frontend**

**Backend**

**DevOps & Tools**

**Languages**

---

## 🚀 Featured Projects

### ⚖️ [EasyCase](https://github.com/vanujak/EasyCase)

> A full-stack web application designed to streamline **case management for legal professionals**.

EasyCase provides a user-friendly interface to manage clients, cases, and hearings — reducing administrative overhead for law firms and individual practitioners.

| Layer        | Technologies                            |
| ------------ | --------------------------------------- |
| **Frontend** | React, Vite, Tailwind CSS, React Router |
| **Backend**  | Node.js, Express, MongoDB, Mongoose     |
| **Auth**     | JWT (JSON Web Tokens)                   |

**Quick Start**

```bash
# Clone the repository
git clone https://github.com/vanujak/EasyCase.git
cd EasyCase

# Install & run backend (http://localhost:5000)
cd backend && npm install && npm run dev

# Install & run frontend (http://localhost:5173)
cd ../frontend && npm install && npm run dev
```

**Environment (backend `.env`)**

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

---

### 🔬 [ScaleLab](https://github.com/vanujak/scalelab)

> A full-stack platform for **building, simulating, and monitoring distributed system architectures**.

ScaleLab enables engineers and students to design system topologies, run simulations, and observe real-time metrics — all through an interactive UI backed by a production-grade API.

| Layer          | Technologies                                      |
| -------------- | ------------------------------------------------- |
| **Frontend**   | Next.js 16, React 19, TypeScript, Tailwind CSS v4 |
| **Backend**    | NestJS 11, TypeScript, PostgreSQL                 |
| **Deployment** | Docker Compose, Nginx, Let's Encrypt              |
| **CI/CD**      | Jenkins Pipeline                                  |

**Repository Structure**

```
.
├── backend/          # NestJS API (users, systems, simulation, metrics, playgrounds)
├── frontend/         # Next.js UI (simulation, dashboards, playground)
├── docker-compose.yml
├── nginx.conf        # Reverse proxy + TLS for scalelab.easycase.site
└── Jenkinsfile       # CI/CD pipeline
```

**Quick Start (Local)**

```bash
# Backend (http://localhost:4000)
cd backend && npm install && npm run start:dev

# Frontend (http://localhost:3000)
cd frontend && npm install && npm run dev
```

**Run with Docker Compose**

```bash
docker compose up -d --build
```

Nginx proxies:

- `scalelab.easycase.site` → frontend
- `api.scalelab.easycase.site` → backend

**Environment (root `.env`)**

```env
DATABASE_URL=postgresql://<user>:<password>@<host>:<port>/<db>
GOOGLE_CLIENT_ID=<google-oauth-client-id>
NEXT_PUBLIC_GOOGLE_CLIENT_ID=<google-oauth-client-id>
```

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=vanujak&show_icons=true&theme=tokyonight&hide_border=true" width="48%" alt="Vanuja's GitHub stats"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=vanujak&theme=tokyonight&hide_border=true" width="48%" alt="Vanuja's streak stats"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=vanujak&layout=compact&theme=tokyonight&hide_border=true" width="48%" alt="Top languages"/>
</p>

---

## 📫 Connect with Me

<p align="center">
  <a href="mailto:vanujakofficial@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://github.com/vanujak">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

---

<p align="center"><i>"Building systems that scale, one commit at a time."</i></p>
