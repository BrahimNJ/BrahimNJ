<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e3a8a,100:2563eb&height=170&section=header&text=Brahim%20NAJI&fontSize=46&fontColor=ffffff&fontAlignY=36&desc=Fullstack%20Java%20Engineer%20%C2%B7%20Spring%20Boot%20%C2%B7%20Angular&descSize=17&descAlignY=58" width="100%" alt="Brahim NAJI" />

<a href="https://github.com/BrahimNJ">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&duration=3200&pause=900&color=2563EB&center=true&vCenter=true&width=620&lines=I+build+fullstack+apps+from+API+to+production;Java+21+%C2%B7+Spring+Boot+%C2%B7+Angular+%C2%B7+PostgreSQL;Tested%2C+secured%2C+continuously+deployed;AI-assisted+%E2%80%94+always+human-reviewed" alt="Typing intro" />
</a>

<p>
  <a href="https://linkedin.com/in/brahimnaji"><img src="https://img.shields.io/badge/LinkedIn-brahimnaji-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:brahim.naji.pro@gmail.com"><img src="https://img.shields.io/badge/Email-Contact%20me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://invoice-flow-brahim21.vercel.app"><img src="https://img.shields.io/badge/Live%20demo-InvoiceFlow-16A34A?style=for-the-badge&logo=vercel&logoColor=white" alt="InvoiceFlow live demo" /></a>
</p>

<img src="https://img.shields.io/badge/Open%20to-Software%20Engineer%20roles-2563EB?style=flat-square" alt="Open to software engineer roles" />
<img src="https://img.shields.io/badge/Based%20in-France-1e3a8a?style=flat-square" alt="Based in France" />

</div>

---

## 👋 About me

Software engineer with a **State Engineering Degree** (ENSET Mohammedia) and an **MSc in Software Engineering** (Université de Lorraine).
I build fullstack applications end to end, and I care about the parts that make software last: clear architecture, tests, security and a delivery pipeline you can trust.

```text
Architecture  →  Backend  →  Frontend  →  Security  →  CI/CD  →  Production
```

- 🏭 **Nexen Tech** : designed a multi-vendor abstraction API: 4 vendors with different protocols, plugged in without touching the shared core
- 🧾 **InvoiceFlow** : e-invoicing app for French SMEs, live in production, **172 automated tests**
- 🔐 Comfortable with **Keycloak, OAuth2/OIDC, JWT refresh-token rotation, Vault**
- 🤖 I use **Claude Code** as a coding agent - and I only ship code I can explain

---

## 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

### 🧾 [InvoiceFlow](https://github.com/BrahimNJ/InvoiceFlow)
Invoicing app built for the French e-invoicing reform (2026-2027).

- ✅ Live: accounts, customers, products & services with French VAT rates
- 🔐 JWT (15 min) + rotating refresh tokens with reuse detection (RFC 9700)
- 🧪 **172 tests** · every green merge is deployed **and verified in production**
- 🗺️ Next: invoices & payments → PDF / Factur-X → AI assistant

`Java 21` `Spring Boot 4` `Angular 21` `PostgreSQL 17` `Flyway` `Docker` `GitHub Actions`

[**▶ Live demo**](https://invoice-flow-brahim21.vercel.app) · [Source](https://github.com/BrahimNJ/InvoiceFlow)

</td>
<td width="50%" valign="top">

### 📊 [DevPulse](https://github.com/BrahimNJ/DevPulse)
Turns any public GitHub repository's history into clear health metrics: stale branches, protections, commit patterns.

- React app, HTTP API **and** CLI on one shared domain
- Layered architecture: I/O-free domain, injected GitHub client
- 1 GraphQL query for 100 branches · automated releases

`TypeScript` `Node.js 24` `React 19` `Vite` `GraphQL` `GitHub Actions`

[Source](https://github.com/BrahimNJ/DevPulse)

</td>
</tr>
</table>

---

## 🛠️ Tech stack

**Backend**
<br/>
<img src="https://skillicons.dev/icons?i=java,spring,nodejs,nestjs&perline=8" alt="Backend" />
<img src="https://img.shields.io/badge/Quarkus-4695EB?style=for-the-badge&logo=quarkus&logoColor=white" height="44" alt="Quarkus" />

**Frontend**
<br/>
<img src="https://skillicons.dev/icons?i=angular,react,ts,js,vite&perline=8" alt="Frontend" />

**Data**
<br/>
<img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb&perline=8" alt="Data" />

**DevOps & Cloud**
<br/>
<img src="https://skillicons.dev/icons?i=docker,kubernetes,jenkins,githubactions,gitlab,gcp,linux&perline=8" alt="DevOps" />

**Security**
<br/>
<img src="https://img.shields.io/badge/Keycloak-4D4D4D?style=for-the-badge&logo=keycloak&logoColor=white" alt="Keycloak" />
<img src="https://img.shields.io/badge/Vault-FFEC6E?style=for-the-badge&logo=vault&logoColor=black" alt="Vault" />
<img src="https://img.shields.io/badge/OAuth2%20%2F%20OIDC-2563EB?style=for-the-badge&logo=openid&logoColor=white" alt="OAuth2 / OIDC" />
<img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" alt="JWT" />

---

## 🧠 How I build software

AI speeds up the typing. Engineering decides what gets shipped.

```mermaid
flowchart LR
    A[Define the problem] --> B[Design & ADR]
    B --> C[AI-assisted implementation]
    C --> D{Human review}
    D -- changes needed --> C
    D -- approved --> E[Tests & CI]
    E --> F[Security checks]
    F --> G[Deploy]
    G --> H[Verify in production]
    H -. feedback .-> A
```

- **Small steps** : one issue per feature, small tested commits
- **Guardrails** : the agent never merges, never pushes to `main`, never touches secrets
- **Proof over promises** : tests, CI and post-deploy checks decide, not the model

---

## 🔭 Right now

- 🧾 Shipping **invoices & payments** in InvoiceFlow, then **Factur-X** export
- 🧩 Next: an **AI assistant** : a sentence in, a draft invoice out (structured output, tests, human confirmation)
- ☸️ Running InvoiceFlow on **Kubernetes** with Helm
- 💼 Looking for a **software engineer / fullstack Java** role in France

---

<div align="center">

**Let's talk** — [LinkedIn](https://linkedin.com/in/brahimnaji) · [brahim.naji.pro@gmail.com](mailto:brahim.naji.pro@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2563eb,100:1e3a8a&height=90&section=footer" width="100%" alt="" />

</div>
