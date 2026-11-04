## Hi 👋, I'm Priyanshu Kumar Thakur (Gravion)

I work on **web application and API security** — building and breaking web services, then explaining
the fix. My day-to-day focus is **OWASP Top 10** and **OWASP API Top 10**: finding authorization
flaws (BOLA / IDOR), authentication and session-handling weaknesses, injection, and unsafe
business logic, then writing reports that engineers can act on.

I also build **dependency-light developer tooling** in Node.js — auditing the inputs, memories and
dependencies that agents and AI applications consume — and I contribute bug fixes upstream to
projects I use.

### 🔐 What I do

- **Web application security assessment** — manual testing of OWASP Top 10 issues, with reproducible
  evidence and remediation guidance.
- **API security testing** — BOLA / cross-tenant detection, rate-limit probing, header and TLS
  posture reviews.
- **Secure code review** — review PRs and small services for access-control, session, and
  injection flaws.
- **Security automation** — small, dependency-light tools that integrate into engineering
  workflows (header checks, TLS posture, log normalization).
- **Supply-chain and data auditing** — tooling that checks agent skill packages, agent memory
  stores and preference datasets for the defects that matter before they reach production.
- **Reporting & triage** — structured findings in JSON + Markdown so engineering teams can route
  work without re-formatting.

### 🧰 Skills I can back with working code

- **Web security:** OWASP Top 10 (IDOR / BOLA, XSS, broken auth & session, business-logic flaws),
  header hygiene, TLS posture.
- **API security:** OWASP API Top 10 (BOLA, broken auth, mass assignment, rate-limiting),
  REST/JSON services.
- **Tooling:** Node.js, Python, Bash; HTTP / TLS / JSON parsing; CI-friendly command-line tools.
- **Platform fundamentals:** Linux, networking, HTTP/HTTPS, JWT/OAuth concepts, basic cloud
  IAM (AWS / Azure).
- **Currently developing:** Active Directory attack-path concepts in a local lab, detection-rule
  authoring against sample datasets, deeper Windows internals.

### 📂 Repositories I want to be known for

**Security tooling**

- **[webapp-security-toolkit](https://github.com/gravion-ux/webapp-security-toolkit)** —
  authorized-only web/API security assessment toolkit. Header analysis, TLS posture, scope
  enforcement, structured findings. 44-test suite, MIT licensed.
- **[web-security-labs](https://github.com/gravion-ux/web-security-labs)** — four OWASP-style
  labs (IDOR, XSS, broken-auth, logic-flaw), each with a vulnerable and a secure variant and
  a 22-test regression suite. Loopback-only by design.
- **[api-security-testing](https://github.com/gravion-ux/api-security-testing)** — read-only
  BOLA / cross-tenant detector and a rate-limit probe, backed by a local mock API for
  reproducible demos. 18-test suite.
- **[security-automation-scripts](https://github.com/gravion-ux/security-automation-scripts)**
  — small Node.js / Bash utilities: header analysis, TLS configuration check, log parsing
  helpers.
- **[llm-security-bot](https://github.com/gravion-ux/llm-security-bot)** — pattern-based
  static analyzer for code, configs, and log lines, with optional LLM-assisted triage.

**Developer tooling** — zero runtime dependencies, Node >= 18

- **[skill-supply-chain-auditor](https://github.com/gravion-ux/skill-supply-chain-auditor)** —
  audits agent skill packages for prompt injection, unsafe shell, obfuscated payloads, embedded
  secrets and unpinned dependencies. 34 rules, redacted reports, CLI. 125 tests.
- **[memorytrust](https://github.com/gravion-ux/memorytrust)** — audits an agent's memory store
  for unverified, stale, contradictory and sensitive content, and scores how much of it can be
  trusted. 16 trust rules, trust score 0-100. 117 tests.
- **[preference-data-doctor](https://github.com/gravion-ux/preference-data-doctor)** — diagnoses
  and repairs preference datasets: duplicates, contradictions, class imbalance, format drift and
  leaked secrets. 18 rules, health score 0-100. 147 tests.
- **[local-slm-eval-kit](https://github.com/gravion-ux/local-slm-eval-kit)** — evaluates a local
  model against a fixed 10-task suite with 6 scorers and diffable reports, so a model swap is a
  measured decision instead of a guess. 113 tests.
- **[gravion-harness](https://github.com/gravion-ux/gravion-harness)** — a scoped, auditable
  security-testing harness: every proposed step is checked against the engagement scope before it
  can run, and every decision lands in a hash-chained audit log. 127 tests.
- **[context-bridge](https://github.com/gravion-ux/context-bridge)** — a VS Code
  extension that writes privacy-conscious Markdown handoffs, with workspace containment and
  secret redaction built in. 66 tests; a 13-defect security audit is documented in the repo.
- **[project-aegis](https://github.com/gravion-ux/project-aegis)** — multi-agent system core:
  task lifecycle, persistent memory, provider abstraction, a default-deny tool registry, budgets
  and recovery. 294-test suite.

**Open-source collaboration**

- **[xerj-ipv6-rate-limit-fix](https://github.com/gravion-ux/xerj-ipv6-rate-limit-fix)** — my
  contribution to [xerj-org/xerj](https://github.com/xerj-org/xerj): a fix for the Corpus Hub
  rate limiter, which bucketed compressed IPv6 addresses by their first four colon-separated
  fields instead of their /64. Open upstream as
  [xerj-org/xerj#2872](https://github.com/xerj-org/xerj/pull/2872).
- **[portfolio](https://github.com/gravion-ux/portfolio)** — current resume, services, and
  writeups.

### 🧪 How I work

1. Read the code path first, before running tools.
2. Reproduce the bug with the smallest possible proof.
3. Quantify the impact in business terms the engineer cares about.
4. Write the fix as a code suggestion, not just an observation.
5. Measure before and after, and quote only the numbers a command produced.

### 📬 Get in touch

- **Email:** priyanshukumarthakur937@gmail.com
- **LinkedIn:** [Priyanshu Kumar Thakur](https://www.linkedin.com/in/priyanshukumarthakur)

📍 India — open to **remote** and **hybrid** (Delhi NCR) roles.
