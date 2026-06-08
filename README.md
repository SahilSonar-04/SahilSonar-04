<div align="center">

```
 _____   ___   _   _  _____  _       _____  _____  _   _   ___  ______ 
/  ___| / _ \ | | | ||_   _|| |     /  ___||  _  || \ | | / _ \ | ___ \
\ `--. / /_\ \| |_| |  | |  | |     \ `--. | | | ||  \| |/ /_\ \| |_/ /
 `--. \|  _  ||  _  |  | |  | |      `--. \| | | || . ` ||  _  ||    / 
/\__/ /| | | || | | | _| |_ | |____ /\__/ /\ \_/ /| |\  || | | || |\ \ 
\____/ \_| |_/\_| |_/ \___/ \_____/ \____/  \___/ \_| \_/\_| |_/\_| \_|
```

### `CS @ IIIT Nagpur` · `Systems Engineer` · `Backend Architect` · `Game Dev`

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&pause=1000&color=00D9FF&center=true&vCenter=true&width=600&lines=Building+things+that+scale+%F0%9F%94%A7;Redis+clones%2C+webhook+systems+%26+async+pipelines;C%2B%2B+%7C+Python+%7C+FastAPI+%7C+Distributed+Systems;Published+researcher+%40+Springer+LNNS+%F0%9F%93%84" alt="Typing SVG" />

</div>

---

## `$ whoami`

```yaml
name: Sahil Sonar
location: Nagpur, India
education: B.Tech CSE @ IIIT Nagpur (2023–2027)
currently: looking for SDE / Backend Intern roles
interests:
  - Distributed Systems & Backend Engineering
  - Systems Programming (C++)
  - Full Stack (MERN / Next.js)
  - Game Development (Unity, Godot — 2D / 3D / AR-VR)
publication: Springer LNNS · Scopus Indexed · ICCS 2025
```

---

## `$ ls -la ./projects`

<table>
<tr>
<td width="50%">

### 🔴 Redis Clone
**`C++23 · ASIO · CMake`**

A Redis-compatible in-memory database from scratch — not a toy.

- 35+ commands: strings, lists, sorted sets, streams, pub/sub
- 52-bit **Morton code geohashing** for geospatial indexing
- `MULTI/EXEC` transactions with **optimistic locking** via WATCH
- **Master-replica replication** via PSYNC + RDB snapshots
- Dual persistence: RDB binary + AOF manifest replay
- `BLPOP` blocking pop · `AUTH/ACL` with SHA-256 hashing

[![GitHub](https://img.shields.io/badge/Source-000?style=flat&logo=github&logoColor=white)](https://github.com/SahilSonar-04/redis-cpp)

</td>
<td width="50%">

### 🪝 Webhook Delivery System
**`FastAPI · PostgreSQL · Redis · Celery · Docker`**

Production-grade async fan-out engine with 99%+ delivery reliability.

- Dead-letter queues · exponential backoff (5 attempts)
- **HMAC-SHA256** payload signing + idempotency key deduplication
- **Groq LLM (Llama 3.1)** for AI failure categorization
- Live status streaming via **Redis Pub/Sub + SSE**
- Auto DB-polling fallback on connection loss

[![GitHub](https://img.shields.io/badge/Source-000?style=flat&logo=github&logoColor=white)](https://github.com/SahilSonar-04/webhook-delivery-system) [![Demo](https://img.shields.io/badge/Demo-FF5733?style=flat&logo=vercel&logoColor=white)](https://www.youtube.com/watch?v=3gZGEx3DsD8)

</td>
</tr>
<tr>
<td width="50%">

### 📄 Async Doc Processing System
**`FastAPI · Celery · PostgreSQL · Redis · Next.js`**

Zero-loss 7-stage document pipeline built for resilience.

- `acks_late` + `reject_on_worker_lost` — **zero job loss on crash**
- Async SQLAlchemy with isolated per-request DB sessions
- Field-level editing + **JSON/CSV export** with idempotent upsert
- SSE job-stage broadcast with DB-polling fallback

[![GitHub](https://img.shields.io/badge/Source-000?style=flat&logo=github&logoColor=white)](https://github.com/SahilSonar-04/async-document-processing) [![Live](https://img.shields.io/badge/Live-00C853?style=flat&logo=vercel&logoColor=white)](https://async-document-processing.vercel.app/) [![Demo](https://img.shields.io/badge/Demo-FF5733?style=flat&logo=vercel&logoColor=white)](https://www.youtube.com/watch?v=G6CYUzeuFq8)

</td>
<td width="50%">

### 🎬 CineBook
**`Node.js · Express · MongoDB · WebSockets · React · Stripe`**

Real-time seat reservation system built for scale and speed.

- **WebSocket**-powered live seat updates — 500+ concurrent users, zero polling overhead
- **95% reduction** in double-booking via atomic seat-locking with MongoDB transactions + TTL-based lock expiry
- **Stripe** payments with streamlined refund flows and event-driven webhook reconciliation
- **JWT/RBAC** authentication with role-based security controls — end-to-end booking under 3 seconds

[![GitHub](https://img.shields.io/badge/Source-000?style=flat&logo=github&logoColor=white)](https://github.com/SahilSonar-04/movie-reservation-system) [![Live](https://img.shields.io/badge/Live-00C853?style=flat&logo=vercel&logoColor=white)](https://sahil-cinebook.vercel.app/)

</td>
</tr>
<tr>
<td width="50%">

### 🤖 Claude Code (from scratch)(Ongoing)
**`C++23 · OpenRouter API · CMake · vcpkg`**

A fully functional AI coding assistant built ground-up in C++.

- LLM-powered **agent loop** with OpenAI-compatible tool calling via OpenRouter
- Built-in `Read`, `Write`, and `Bash` tool execution for real filesystem & shell interaction
- Streaming conversation history across multi-turn agentic sessions
- Clean CMake + vcpkg build system with `cpr` (HTTP) and `nlohmann/json`

[![GitHub](https://img.shields.io/badge/Source-000?style=flat&logo=github&logoColor=white)](https://github.com/SahilSonar-04/claude-code-cpp)

</td>
<td width="50%">

</td>
</tr>
</table>

---

## `$ cat ./skills.json`

```json
{
  "languages":  ["C++23", "Python", "JavaScript", "TypeScript"],
  "backend":    ["FastAPI", "Node.js", "Express.js", "REST", "WebSockets"],
  "systems":    ["Distributed Systems", "Microservices", "Concurrency",
                 "Multithreading", "Caching", "Message Queues", "TCP/UDP"],
  "databases":  ["PostgreSQL", "MongoDB", "Redis", "SQL"],
  "frontend":   ["React", "Next.js", "HTML/CSS"],
  "game_dev":   ["Unity", "Godot", "C# (2D / 3D / AR-VR)"],
  "tools":      ["Docker", "Git", "Linux", "CI/CD", "CUDA", "CMake"]
}
```

---

## `$ cat ./publication.txt`

> 📄 **Transformer Networks for Transfer Learning in EEG-based Mental Workload Analysis**
>
> *Springer LNNS · Scopus Indexed · ICCS 2025*
>
> Transformer-based transfer learning pipeline for EEG workload classification.
> Pre-trained on aviation EEG · Fine-tuned on STEW/SIMKAP · **96.15% accuracy**
> Ranked **#1** via Friedman test across 6 benchmark studies.

---

## `$ cat ./achievements.md`

| 🏆 | Achievement |
|---|---|
| 🥇 | **Winner** — IIIT Nagpur Game Jam *(National Level)* |
| 🏅 | **Finalist** — AIT Pune Game Jam *(National Level)* |
| 💻 | **250+ LeetCode** problems — algorithms, DSA, complexity |
| 👥 | **Co-Lead (Technical)** — Dimensions GameDev & XR Club, IIIT Nagpur |
| 🎮 | Organized national game jam — **100+ participants, 10+ colleges** |

---

## `$ ping sahil`

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sahilsonar)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SahilSonar-04)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sonarsahil4@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com)

</div>

---

<div align="center">

*`Open to SDE & Backend internship/full-time roles`*

</div>
