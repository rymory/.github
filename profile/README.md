## Rymory

**Open identity infrastructure for the open web.**

Rymory is a federation-ready identity layer — born from real production infrastructure built since 2017. One account, any application, any ecosystem.

Designed for interoperable applications, distributed systems and modern digital trust.
No single company controls the protocol. Governance is open by design.

---

### Repositories

| Repo | Description |
|---|---|
| [rymory-core](https://github.com/rymory/rymory-core) | Identity backend — authenticate, account, role, project (Go) |
| [rymory-gateway](https://github.com/rymory/rymory-gateway) | Edge proxy — JWT, cookie, rate limiting, CORS (Go + Cloudflare) |
| [goutils](https://github.com/rymory/goutils) | Shared Go utilities — JWT, DB, response helpers |

---

### Architecture

```
id.rymory.org          ← single sign-on entry point
      │
      ├── notes.lemoras.com
      ├── drive.lemoras.com
      ├── [any third-party app]
      │
account.rymory.org     ← account management
```

---

**License:** AGPL v3 + Commercial Exception
**Trademarks:** "Rymory" registered with TÜRKPATENT
**Author:** [Onur Yaşar](https://onuryasar.org) · onxorg@proton.me
**Github:** [Onur Yaşar](https://github.com/onurid) · @onurid

→ [rymory.org](https://rymory.org)


