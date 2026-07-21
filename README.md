<div align="center">

# `GET /anuj-singh-rana`

**Full-Stack Developer** · Node.js · React.js · Distributed Systems
📍 Dehradun, India · 🎓 B.Tech CS, Graphic Era University (May 2026)

</div>

---

### `GET /anuj/status`
\`\`\`json
{
  "role": "Full-Stack Developer",
  "seeking": "SDE / Full-Stack roles",
  "availability": "immediate",
  "contact": "anujrana9264@gmail.com"
}
\`\`\`

---

### `GET /anuj/projects/notifyhq`
**Multi-tenant notification infrastructure API**
\`Node.js\` \`Express\` \`PostgreSQL\` \`Redis\` \`BullMQ\` \`WebSockets\` \`Docker\` \`Nginx\`

\`\`\`json
{
  "description": "SaaS notification service — in-app, email, webhook delivery via REST API",
  "architecture": {
    "queueing": "BullMQ + Redis, 10 concurrent jobs, exponential backoff retry",
    "rate_limit": "Nginx, 100 req/s per tenant API key",
    "realtime": "WebSockets, per-tenant rooms, JWT-authenticated",
    "deployment": "Docker Compose, horizontally scaled (--scale app=3)"
  },
  "tests": "26 integration tests (Jest + Supertest)",
  "repo": "github.com/Anuj8171/notifyhq"
}
\`\`\`

---

### `GET /anuj/projects/e2ee-chat`
**End-to-end encrypted chat application**
\`React.js\` \`Socket.io\` \`TweetNaCl\` \`OAuth 2.0\`

\`\`\`json
{
  "description": "Real-time messaging — server never sees plaintext",
  "security": "TweetNaCl asymmetric key exchange, bcrypt, OAuth 2.0 + JWT",
  "benchmark": "10,000 req/sec, sub-100ms message delivery",
  "repo": "github.com/Anuj8171/E2EE-Chat-App"
}
\`\`\`

---

### `GET /anuj/projects/sync-engine`
**Two-way sync automation system**
\`Python\` \`PyAirtable\` \`SQLite\`

\`\`\`json
{
  "description": "Bi-directional Trello <-> Airtable sync engine",
  "reliability": "conflict resolution, idempotency, retry logic",
  "throughput": "500+ sync events/min, zero data loss",
  "repo": "github.com/Anuj8171/automation-two-way-sync"
}
\`\`\`

---

### `GET /anuj/stack`
\`\`\`json
{
  "languages": ["JavaScript (ES6+)", "Python", "C++", "Java", "SQL"],
  "backend": ["Node.js", "Express.js", "REST APIs", "WebSockets", "BullMQ", "JWT"],
  "frontend": ["React.js", "Next.js", "Tailwind CSS", "Zustand"],
  "databases": ["PostgreSQL", "Redis", "MongoDB", "SQLite", "Prisma ORM"],
  "devops": ["Docker", "Nginx", "AWS (EC2, S3, ECS, Amplify)", "Git"]
}
\`\`\`

---

### `POST /anuj/contact`
\`\`\`json
{
  "email": "anujrana9264@gmail.com",
  "phone": "+91-8171299264",
  "github": "github.com/Anuj8171"
}
\`\`\`

> `200 OK` — response guaranteed within 24h

<div align="center">
<sub>404 Not Found — the perfect codebase. Still iterating.</sub>
</div>
