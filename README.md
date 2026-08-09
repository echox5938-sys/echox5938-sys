## Hi, I'm Sahil

I'm working toward **Solutions Architect**, aimed long-term at cloud security research. Most of what I
build is local-first and runs on my own hardware. The design constraint is that data doesn't leave the
machine unless exactly one component is allowed to send it.

**Stack:** Python · FastAPI · React · SQLite / SQLCipher · Ollama · AWS · Terraform · Linux (Fedora)

---

### Lyra - a local-first AI harness

**[Lyra](https://github.com/echox5938-sys/Lyra)** is the harness: React + Vite + Tailwind frontend,
FastAPI backend, SQLCipher-encrypted SQLite, inference through a local Ollama instance. The encryption
key is derived with Argon2id and lives only in process memory after unlock.

Two sub-projects complete it:

- **LyraMini** - the retrieval half. A read-only CLI over an
  Obsidian vault: scans, flags orphans and duplicates, ranked search on SQLite FTS5. Zero writes and zero
  LLM calls by design. Lyra answers, LyraMini only finds.
- **Aladfar** - the one component permitted to make off-machine calls, so the rest of the system stays
  provably local. Scheduled briefs and web search live here. *In design.*

### Aquila

**[Aquila](https://github.com/echox5938-sys/Aquila)** - a Telegram bot that turns any link into a
summarized note in my vault. Video transcription, article extraction, and a local vision model for image
carousels.

---

### Currently

- CIS associate degree at RCSJ
- Studying for **AWS Solutions Architect Associate** (SAA-C03)
- Cert path after that: Terraform Associate → Security+ → AWS SAP-C02 → AWS Security Specialty
- Learning the other half on my own time: x86-64, memory corruption, IAM privilege escalation,
  container escapes

📫 echox5938@gmail.com

💼 [linkedin.com/in/sahil-siddiquie-895962414](linkedin.com/in/sahil-siddiquie-895962414)
