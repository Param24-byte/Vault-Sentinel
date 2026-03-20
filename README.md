# 🛡️ Vault Sentinel
> Because every door in your bank deserves a guardian.

Vault Sentinel is a machine learning integrated **Zombie API detection, protection and removal platform** built for Indian financial institutions. It follows a 3-layer approach — Layer 1 discovers and scores Zombie/Dormant APIs using Traffic, Static and ML scoring; Layer 2 inserts a dedicated defence layer between flagged APIs and the backend; Layer 3 eliminates threats using Auto-Quarantine, HoneyTrap and OWASP Top 10 Scanner.

---

## The Problem
Banks accumulate hundreds of APIs over years. When systems are replaced, old APIs get abandoned but never shut down. These **Zombie APIs** run silently — unpatched, unmonitored and unprotected — costing **Rs 35+ Crore per breach** with a **6-month average detection delay**.

---

## Features
- **3-Part Scoring Engine** — Traffic + Static + ML composite risk score (0–100)
- **OWASP Top 10 Scanner** — Automated pass/fail checks across all 10 API security rules
- **Auto-Quarantine** — Blocks dangerous endpoints at gateway level in under 0.3 seconds
- **HoneyTrap System** — Decoy APIs that catch attackers with zero false positives
- **Live Simulation** — Real hacker attack demo running in a controlled local sandbox
- **Compliance Reports** — One-click RBI IT Framework, PCI-DSS 4.0 and DPDP Act 2023 PDF

---

## Tech Stack
| Layer | Stack |
|-------|-------|
| Landing Page | Next.js 14 · TypeScript · TailwindCSS · Framer Motion |
| Dashboard | React 18 · TypeScript · D3.js · Socket.io · Recharts |
| Backend | Python · FastAPI · Uvicorn · Pandas · Celery |
| Database | PostgreSQL · Redis · SQLAlchemy · Alembic |
| ML / AI | scikit-learn · SHAP · Gemini AI · Faker · NVD CVE API |
| Cybersecurity | OWASP Engine · httpx · HoneyTrap Server · Quarantine Middleware |

---

## Getting Started
```bash
# Clone the repository
git clone https://github.com/your-username/vault-sentinel.git
cd vault-sentinel

# Open prototype directly
open index.html

# Or serve locally
python -m http.server 3000
```

---

## Team
| Member | Role |
|--------|------|
| Member 1 | Frontend — Next.js · React · D3.js |
| Member 2 | Backend — FastAPI · PostgreSQL · Redis |
| Member 3 | ML/AI — scikit-learn · Gemini AI |
| Member 4 | Cybersecurity — OWASP · HoneyTrap · RBI Compliance |

---

**PS9 · PSBs Banking Hackathon 2026 · Union Bank of India**
