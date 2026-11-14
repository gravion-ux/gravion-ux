## Hi 👋, I'm Priyanshu Kumar Thakur (Gravion)

**Security engineer** — I find the flaw in web applications and APIs, and I build the
open-source tooling that stops it happening twice.

🔗 [Portfolio](https://gravion-ux.github.io/portfolio) ·
🔗 [LinkedIn](https://www.linkedin.com/in/priyanshukumarthakur) ·
🔗 [Fiverr](https://www.fiverr.com/ig_priyanshu)

---

### 🚀 Two ways to work with me

| | |
| --- | --- |
| **Sponsor the open-source tools** | Recurring monthly support from **$5**, or one-time contributions that fund a specific bug, feature or release. Prices are published and never change after they are set. **[github.com/sponsors/gravion-ux](https://github.com/sponsors/gravion-ux)** |
| **Hire me for security work** | Web and API assessments from **$500**, secure code review and threat modelling from **$300**, automation builds from **$800**. Scope agreed in writing before any testing starts. **[See the packages](https://gravion-ux.github.io/portfolio/services.html)** |

Sponsorship pays for the work nobody sees: issue triage, CI maintenance, dependency
review of my own tools, and the next release. That is what keeps the tools free and
free of telemetry, whether or not anyone sponsors. All 30 published projects carry
the MIT licence. 22 of them run a CI workflow, and 28 have a test suite whose size
was measured.

---

### 🤝 Sponsors

Sponsorship is what keeps these tools free and free of telemetry. Sponsor names are listed
here, and in the three flagship READMEs, as sponsors join.

**[Sponsor on GitHub](https://github.com/sponsors/gravion-ux)** — recurring tiers from
**$5** a month, plus one-time tiers that fund a specific bug, feature or release.

---

### 📊 The work, measured

| | |
| --- | --- |
| **30 of 30** | open-source projects published, MIT licensed |
| **2,103** | test cases across 28 projects — every count measured by running the suite |
| **431** | tests in the three flagship tools alone (129 + 187 + 115) |
| **15 of 16** | Node tools ship with zero runtime dependencies |

Star counts, licences and CI coverage are re-read from the live GitHub API, so the
numbers above move when the work moves.

---

### 🔐 What I do

- **Web application security assessment** — manual testing of OWASP Top 10 issues,
  with reproducible evidence and remediation guidance.
- **API security testing** — BOLA and cross-tenant detection, rate-limit probing,
  header and TLS posture reviews.
- **Secure code review** — review pull requests and small services for access-control,
  session and injection flaws.
- **Security automation** — small, dependency-light tools that integrate into
  engineering workflows.
- **Supply-chain and data auditing** — tooling that checks agent skill packages, agent
  memory stores and preference datasets for the defects that matter before they reach
  production.
- **Reporting and triage** — structured findings in JSON and Markdown so engineering
  teams can route work without re-formatting.

---

### 🧰 Open-source projects

Every project below is MIT licensed. Test counts are the number each repository's own
suite reports.

**Red-team and detection engineering**

| Project | What it does | Tests |
| --- | --- | --- |
| [fixqueue](https://github.com/gravion-ux/fixqueue) | Merge SARIF, Trivy, Grype and OSV scanner output into one deduplicated, EPSS and KEV prioritized fix queue. | 129 |
| [rulebench](https://github.com/gravion-ux/rulebench) | Sigma rule conformance harness: run rules against events, lint them, and measure coverage against the MITRE knowledge base. | 187 |
| [opsledger](https://github.com/gravion-ux/opsledger) | Tamper-evident evidence ledger for red-team engagements: hash-chained events and a signed manifest. | 115 |
| [iamosiac](https://github.com/gravion-ux/iamosiac) | Offline cloud-IAM policy review and permission-relationship visualization data, with least-privilege remediation hints. | 39 |
| [violet-trace](https://github.com/gravion-ux/violet-trace) | A safe purple-team validation harness for defensive telemetry and detection-rule tests. | 34 |
| [accessweave](https://github.com/gravion-ux/accessweave) | Offline identity-relationship and directory-permission review from explicitly exported inventory data. | 33 |
| [secret-sniper](https://github.com/gravion-ux/secret-sniper) | Leaked credential detection with live verification. | 69 |
| [fuzzharbor](https://github.com/gravion-ux/fuzzharbor) | A reproducible local fuzzing campaign manager and crash triage toolkit. | 21 |
| [quanta-sentry](https://github.com/gravion-ux/quanta-sentry) | Cryptographic inventory and post-quantum migration-readiness reporting from source and configuration evidence. | 26 |
| [cipherbench](https://github.com/gravion-ux/cipherbench) | A benchmark and interoperability test harness specification for vetted post-quantum cryptographic providers. | 29 |

**AI and agent security**

| Project | What it does | Tests |
| --- | --- | --- |
| [preference-data-doctor](https://github.com/gravion-ux/preference-data-doctor) | Diagnoses and repairs preference datasets: duplicates, contradictions, class imbalance, format drift, leaked secrets. | 147 |
| [skill-supply-chain-auditor](https://github.com/gravion-ux/skill-supply-chain-auditor) | Audits agent skill packages for prompt injection, unsafe shell, obfuscated payloads, embedded secrets, unpinned dependencies. | 125 |
| [gravion-harness](https://github.com/gravion-ux/gravion-harness) | A scoped, auditable security-testing harness with a hash-chained audit log. | 127 |
| [memorytrust](https://github.com/gravion-ux/memorytrust) | Audits an agent memory store for unverified, stale, contradictory and sensitive content and scores how much can be trusted. | 112 |
| [local-slm-eval-kit](https://github.com/gravion-ux/local-slm-eval-kit) | Evaluates a local model against a fixed task suite with redaction, timeouts and diffable reports. | 108 |
| [llm-security-bot](https://github.com/gravion-ux/llm-security-bot) | Pattern-based static analysis for code, configs, log lines and LLM input — deterministic, so the output is a triage list, not proof of exploitability. | 20 |
| [context-bridge](https://github.com/gravion-ux/context-bridge) | A VS Code extension that writes privacy-conscious Markdown handoffs, with secret redaction built in. | 66 |
| [gravion-trainner](https://github.com/gravion-ux/gravion-trainner) | Model quality evaluation starter for OpenAI-compatible chat-completions endpoints. | 27 |

**Assessment, automation and platform**

| Project | What it does | Tests |
| --- | --- | --- |
| [TRISHUL](https://github.com/gravion-ux/TRISHUL) | Authorized-scope, AI-powered security testing platform with real tool integration behind scope gates and an AI policy boundary. | 118 |
| [webapp-security-toolkit](https://github.com/gravion-ux/webapp-security-toolkit) | Authorized-only web and API security assessment toolkit: header analysis, TLS posture, scope enforcement, structured findings. | 44 |
| [web-security-labs](https://github.com/gravion-ux/web-security-labs) | Four OWASP-style labs (IDOR, XSS, broken-auth, logic-flaw), each with a vulnerable and a secure variant, loopback-only by design. | 22 checks across 4 labs |
| [api-security-testing](https://github.com/gravion-ux/api-security-testing) | Read-only BOLA and cross-tenant detector with a rate-limit probe, backed by a local mock API for reproducible demos. | 18 |
| [security-automation-scripts](https://github.com/gravion-ux/security-automation-scripts) | Small Node.js and Bash utilities: header analysis, TLS configuration check, log parsing helpers. | 22 |
| [agent-browser](https://github.com/gravion-ux/agent-browser) | Visible Playwright browser starter with an explicit domain allow-list and explicit stop conditions. | 43 |
| [privacyflow](https://github.com/gravion-ux/privacyflow) | Validates authorized WireGuard profiles and plans safe VPN rotation workflows. | 38 |
| [localshare](https://github.com/gravion-ux/localshare) | Shares a local development server through Cloudflare tunnels, with loopback-only origins. | 40 |
| [rasgulla-ai](https://github.com/gravion-ux/rasgulla-ai) | A local-first AI-assisted security research workbench for code understanding and safe test generation. | 50 |
| [aegis](https://github.com/gravion-ux/aegis) | Multi-agent system core: task lifecycle, persistent memory, provider abstraction, default-deny tool registry, budgets and recovery. | 294 |

**Upstream contribution and other**

| Project | What it does |
| --- | --- |
| [xerj-ipv6-rate-limit-fix](https://github.com/gravion-ux/xerj-ipv6-rate-limit-fix) | A contribution to [xerj-org/xerj](https://github.com/xerj-org/xerj) fixing the Corpus Hub rate limiter to bucket compressed IPv6 addresses by their /64. Open upstream as [xerj-org/xerj#2872](https://github.com/xerj-org/xerj/pull/2872). |
| [catalog-forge](https://github.com/gravion-ux/catalog-forge) | Crawls a shop catalog and serves it as a storefront. |

---

### 🧪 How I work

1. Read the code path first, before running tools.
2. Reproduce the bug with the smallest possible proof.
3. Quantify the impact in the business terms the engineer cares about.
4. Write the fix as a code suggestion, not just an observation.
5. Measure before and after, and quote only the numbers a command produced.

---

### 💼 Services

Prices are starting prices, published so you know the floor before you enquire.

- **Web and API security assessment — from $500.** An agreed target list, OWASP Top 10
  and OWASP API Top 10 coverage with emphasis on authorization and cross-tenant
  flaws, broken authentication and session handling, injection, and rate limiting.
  Five business days. Findings report with impact, reproduction steps and remediation
  guidance per finding, plus a retest of critical findings. No testing outside the
  agreed scope.
- **Secure code review and threat modelling — from $300.** Up to two pull requests or
  one service. Access control, session handling, input validation and injection
  paths, with a short threat model of the changed surface. Three business days.
  Inline findings with severity and concrete fixes, plus a written threat model.
- **Security automation build — from $800.** One small CI-friendly tool for your
  stack: scanner triage, a dependency gate, log normalization, or detection-rule
  linting. Built as a repository with a test suite, a CI pipeline and documentation,
  delivered with a working demo. Two to three weeks.

Also quoted on scope: detection-rule review and coverage analysis, cloud IAM and
permission review, and post-quantum migration-readiness inventory.

📬 [Enquire on Fiverr](https://www.fiverr.com/ig_priyanshu) or
[LinkedIn](https://www.linkedin.com/in/priyanshukumarthakur).

---

### 📬 Get in touch

- **LinkedIn:** [Priyanshu Kumar Thakur](https://www.linkedin.com/in/priyanshukumarthakur)
- **Fiverr:** [Priyanshu Kumar Thakur](https://www.fiverr.com/ig_priyanshu) — OWASP Top 10 and API security assessments
- **Sponsor:** [github.com/sponsors/gravion-ux](https://github.com/sponsors/gravion-ux)
- **Full portfolio:** [gravion-ux.github.io/portfolio](https://gravion-ux.github.io/portfolio)

📍 India — open to **remote** and **hybrid** (Delhi NCR) roles.

---

<sub>All 30 published projects carry the MIT licence. No telemetry, no tracking, no
accounts.</sub>
