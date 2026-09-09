# Relync Backend

> High-performance REST & WebSocket API engine for the Relync ecosystem.

This repository contains the backend core for Relync. Built with Express, TypeScript, PostgreSQL, and Socket.IO, it emphasizes robust authentication, crisp role/permission authorization, reliable message persistence, and scalable realtime events.

---

## ⚡ Status

**Milestone:** `V0.1 — Foundation` (In Progress)  
*The API is under active initial setup. See the [Relync Meta Repository](https://github.com/Sief-Ali/Relync) for system specs and roadmaps.*

---

## 🛠️ Stack

* **Runtime:** Node.js + Express
* **Language:** TypeScript
* **Database:** PostgreSQL
* **Realtime:** Socket.IO
* **Documentation:** OpenAPI 3.x + Scalar
* **Testing:** Jest

---

## 🚀 Quickstart (Development)

### Prerequisites

* Node.js (v20+)
* PostgreSQL
* `pnpm` (or `npm`)

### Setup

1. **Clone the repository:**

```bash
git clone https://github.com/Sief-Ali/relync-backend.git
cd relync-backend

```

2. **Install dependencies:**

```bash
pnpm install

```

3. **Configure Environment:**

```bash
cp .env.example .env

```

4. **Run Development Server:**

```bash
pnpm dev

```
The API will start at `http://localhost:4000`.

---

## 📡 Core Endpoints (V0.1 Baseline)

| Method | Endpoint | Description | Status |
| :--- | :--- | :--- | :--- |
| `GET` | `/health` | Server health & uptime check | 🚧 In Progress |
| `GET` | `/api/docs` | Interactive Scalar OpenAPI Docs | ⏳ Planned |

---

## 📄 License

This project is currently under active pre-release development.
* **Free for developers, hobbyists, self-hosters, and open-source contributors.**
* **Commercial and business use is strictly prohibited** until official `V1.0` release.
* See [LICENSE](./LICENSE) for details.
