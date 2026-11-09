<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&duration=2800&pause=2000&color=A9FEF7&center=true&vCenter=true&width=940&lines=Hi%2C+I'm+Sarthak+Shreshtha;Backend+%26+Full-Stack+Engineer;Open+Source+Contributor+%40+Kubescape+(CNCF);100%2B+merged+PRs+across+29+organisations" alt="Typing SVG" />

<p align="center">
    <a href="https://drive.google.com/file/d/1jspxlxYZPGKAYRdut__0VwtkpQnUoNfx/view?usp=sharing" target="_blank">
        <img src="https://img.shields.io/badge/Resume-Download-red?style=for-the-badge&logo=adobe-acrobat-reader&logoColor=white" alt="Resume" />
    </a>
    <a href="https://www.sarthakshreshtha.dev/" target="_blank">
        <img src="https://img.shields.io/badge/Portfolio-Website-1E2761?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" />
    </a>
    <a href="https://www.linkedin.com/in/sarthak-shreshtha/" target="_blank">
        <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="https://leetcode.com/u/sarthakshreshtha345/" target="_blank">
        <img src="https://img.shields.io/badge/LeetCode-Profile-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode" />
    </a>
</p>

[![Merged PRs](https://img.shields.io/badge/Merged%20PRs-100%2B-8957e5?style=flat-square&logo=github)](https://github.com/search?q=is%3Apr+is%3Amerged+author%3ASarthak-Shreshtha01&type=pullrequests)
[![Profile Views](https://komarev.com/ghpvc/?username=Sarthak-Shreshtha01&label=Profile%20Views&color=0e75b6&style=flat-square)](https://github.com/Sarthak-Shreshtha01)
[![GitHub Followers](https://img.shields.io/github/followers/Sarthak-Shreshtha01?label=Followers&style=flat-square&color=blue)](https://github.com/Sarthak-Shreshtha01?tab=followers)

</div>

---

## About Me

I'm a final-year Computer Science student at **Birla Institute of Technology, Mesra** (CGPA 8.4/10). I build backend systems: production REST APIs, event-driven pipelines with Redis and BullMQ, and the data models behind them. In open source I work mostly on **cloud-native tooling in Go**, with **Kubescape (CNCF)** as my main project.

```ts
const sarthak = {
  role: "Backend & Full-Stack Engineer",
  education: "B.Tech CSE @ BIT Mesra (2023 – 2027, CGPA 8.4/10)",
  languages: ["TypeScript", "Go", "Python", "C++"],
  stack: ["Node.js", "NestJS", "Next.js", "PostgreSQL", "Redis", "BullMQ", "Docker", "Kubernetes"],
  openSource: "100+ merged PRs across 29 organisations, 38 of them in Kubescape (CNCF)",
  lookingFor: "Backend / platform engineering roles and internships",
};
```

---

## Open Source

**103 merged pull requests across 29 organisations**, including CNCF projects, Google Summer of Code organisations, and Apache and Linux Foundation projects. Most are bug fixes with regression tests, written after reproducing the issue myself.

### Kubescape (CNCF Incubating): 38 merged PRs

My main project. I work across the CLI, the in-cluster storage component, the Rego control library, the Helm charts and the documentation.

- **Read-only MCP endpoint for in-cluster security data.** I wrote the [design proposal](https://github.com/kubescape/designs-and-proposals/pull/27) and built it in [`kubescape/storage`](https://github.com/search?q=repo%3Akubescape%2Fstorage+is%3Apr+is%3Amerged+author%3ASarthak-Shreshtha01&type=pullrequests): the `MCPServer` API type, the `mcpservers/mcp` endpoint, and tools for vulnerabilities, SBOMs, configuration scans and container profiles, plus the [Helm values](https://github.com/kubescape/helm-charts/pull/989) to deploy it.
- **Kubescape CLI MCP server.** New tools (`list_sboms`, `list_sbom_packages`, scan summaries), plus filtering and paging so that large scan results fit in an AI assistant's context.
- **Security and correctness fixes**: scan result files created with `0600` permissions and file paths redacted from errors, `--output` directory handling, `accountID` validation, and Rego rules that read the wrong object.
- **Documentation** for all 31 MCP server tools and for operator storage behaviour on [kubescape.io](https://github.com/search?q=repo%3Akubescape%2Fkubescape.io+is%3Apr+is%3Amerged+author%3ASarthak-Shreshtha01&type=pullrequests).

### Other projects

| Organisation | Merged PRs | Repositories | Highlights |
|---|:---:|---|---|
| [**C2SI**](https://github.com/search?q=org%3Ac2siorg+is%3Apr+is%3Amerged+author%3ASarthak-Shreshtha01&type=pullrequests) (GSoC) | 10 | imagelab, tensormap, dataloom | Alpha-channel handling in image operators; exported Python scripts that now match the in-app filters; a fix that keeps uploaded files inside the upload folder |
| [**D Language Foundation**](https://github.com/search?q=org%3Adlang+is%3Apr+is%3Amerged+author%3ASarthak-Shreshtha01&type=pullrequests) (GSoC) | 4 | dmd, phobos | Unary `+` in array operations in the compiler; accuracy fixes in `std.math` (`sinh`, `atanh`, `betaIncompleteInv`) |
| [**Open Food Facts**](https://github.com/search?q=org%3Aopenfoodfacts+is%3Apr+is%3Amerged+author%3ASarthak-Shreshtha01&type=pullrequests) (GSoC) | 4 | open-prices-frontend, robotoff, search-a-licious | Time-zone bugs in price dates, tag normalisation, facet keys in the search API |
| [**Lima**](https://github.com/search?q=org%3Alima-vm+is%3Apr+is%3Amerged+author%3ASarthak-Shreshtha01&type=pullrequests) (CNCF) | 4 | lima | gRPC connection leak in the guest agent, `PATH` in launchd autostart, Kubernetes template join URLs |
| [**kcp**](https://github.com/search?q=org%3Akcp-dev+is%3Apr+is%3Amerged+author%3ASarthak-Shreshtha01&type=pullrequests) (CNCF) | 3 | kcp | Finalizer on `LogicalClusterMigration` during migration, e2e coverage, a sort comparator fix |
| [**Fortran-lang**](https://github.com/search?q=org%3Afortran-lang+is%3Apr+is%3Amerged+author%3ASarthak-Shreshtha01&type=pullrequests) (GSoC) | 3 | stdlib, fpm | pkg-config output, Windows compiler flags |
| [**pwndbg**](https://github.com/search?q=org%3Apwndbg+is%3Apr+is%3Amerged+author%3ASarthak-Shreshtha01&type=pullrequests) (GSoC) | 3 | pwndbg | `vmmap` and `mmap` command fixes, quieter `next*` commands |
| [**Karmada**](https://github.com/search?q=org%3Akarmada-io+is%3Apr+is%3Amerged+author%3ASarthak-Shreshtha01&type=pullrequests) (CNCF) | 2 | karmada | A panic in CronFederatedHPA, deterministic MPIJob component order |
| [**NeuroInformatics Unit**](https://github.com/search?q=org%3Aneuroinformatics-unit+is%3Apr+is%3Amerged+author%3ASarthak-Shreshtha01&type=pullrequests) (GSoC) | 2 | movement, derotation | Non-square image derotation, single-track path metrics |
| [**openZIM / Kiwix**](https://github.com/search?q=org%3Aopenzim+is%3Apr+is%3Amerged+author%3ASarthak-Shreshtha01&type=pullrequests) (GSoC) | 2 | mwoffliner, python-scraperlib | Unicode-safe title truncation, content-language detection |

**Also merged in:** [Apache Camel K](https://github.com/apache/camel-k/pull/6856) · [Hyperledger Fabric](https://github.com/hyperledger/fabric/pull/5584) · [KubeVela](https://github.com/kubevela/kubevela/pull/7419) · [Perses](https://github.com/perses/perses/pull/4446) · [Kuadrant](https://github.com/Kuadrant/mcp-gateway/pull/1589) · [Cryostat](https://github.com/cryostatio/cryostat-web/pull/2510) · [Okteto](https://github.com/okteto/okteto/pull/5178) · [OpenEverest](https://github.com/openeverest/openeverest/pull/3202) · [CLI for Microsoft 365](https://github.com/pnp/cli-microsoft365/pull/7590)

[**See all merged pull requests →**](https://github.com/search?q=is%3Apr+is%3Amerged+author%3ASarthak-Shreshtha01+-user%3ASarthak-Shreshtha01&type=pullrequests)

---

## Experience

### Software Developer Intern, Quickeee Pvt Ltd
*May 2026 – Jul 2026*
- Cut order sync latency by **99.9%** (120 s → under 5 ms) by replacing polling with Redis Pub/Sub wake signals and priority-tiered BullMQ workers.
- Built an automated nightly **inventory reconciliation pipeline** (BullMQ, Redis, cron) for Unicommerce sync, with an API for manual runs.
- Shipped **30+ REST APIs** across purchase orders, inventory, refunds and warehouse operations, including SKU search and Redis cache invalidation.
- Implemented the end-to-end warehouse fulfilment flow (PO → GRN → Putaway → Picklist → Manifest) and debugged webhook delivery for four order types.

### Full-Stack Developer, Productimate AI Solutions
*May 2025 – Jan 2026*
- Built production features with **Next.js, React Native, Node.js and PostgreSQL** across several B2B SaaS products.
- Implemented PhonePe subscription billing, role-based access control, AI-assisted email generation and CSV lead imports.
- Integrated AWS S3, CloudWatch, GA4 and Hygraph CMS; improved Core Web Vitals with SSR tuning and lazy loading.

---

## Skills

<table align="center">
  <tr>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=ts,go,python,cpp,java" />
      <br><br>
      <img src="https://skillicons.dev/icons?i=nodejs,nestjs,express,nextjs,react,tailwind,prisma,graphql" />
      <br><br>
      <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,kafka" />
      <br><br>
      <img src="https://skillicons.dev/icons?i=docker,kubernetes,aws,linux,git,github,postman" />
    </td>
  </tr>
</table>

---

## Featured Projects

<table border="0">
  <tr>
    <td width="50%" valign="top">

<h3 align="center">TradeX: Unified Investment Dashboard</h3>
<p>
Real-time portfolio dashboard that connects three brokerage APIs (Zerodha, Angel One, Upstox) over persistent WebSockets and tracks 200+ instruments with sub-100 ms updates. A Gemini-based recommendation engine cut manual research time by 40%.
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Next.js-black?style=flat-square&logo=next.js" />
  <img src="https://img.shields.io/badge/WebSockets-4353FF?style=flat-square&logo=socketdotio&logoColor=white" />
  <img src="https://img.shields.io/badge/Google_Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" />
</p>

</td>
    <td width="50%" valign="top">

<h3 align="center">Pantheon'25: BIT Mesra Technical Fest</h3>
<p>
Official website of the BIT Mesra technical fest, with GSAP scroll animations, static generation and technical SEO: a 100% Lighthouse SEO score, under 2 s LCP on mobile, and 10,000+ concurrent visitors at peak with no downtime.
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Next.js-black?style=flat-square&logo=next.js" />
  <img src="https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=white" />
  <img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
</p>
<div align="center">
  <a href="https://pantheon-2k25-gules.vercel.app">Live Site</a> • <a href="https://github.com/RishavK010/Pantheon-2k25">Source Code</a>
</div>

</td>
  </tr>
  <tr>
    <td width="50%" valign="top">

<h3 align="center">Starsec: Security SaaS Landing Page</h3>
<p>
Production landing page for a security SaaS, with complex GSAP animations, structured SEO metadata and content managed in Hygraph.
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Next.js-black?style=flat-square&logo=next.js" />
  <img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/Hygraph-2A0053?style=flat-square&logo=graphql&logoColor=white" />
</p>
<div align="center">
  <a href="https://github.com/Sarthak-Shreshtha01/starsec">Source Code</a>
</div>

</td>
    <td width="50%" valign="top">

</td>
  </tr>
</table>

---

## Education

| Institution | Duration | Detail |
|---|---|---|
| **Birla Institute of Technology, Mesra**, B.Tech in Computer Science & Engineering | 2023 – 2027 | CGPA: 8.4/10 |
| **Delhi Public School, Bokaro**, CBSE Class XII | 2021 – 2023 | 92% |

---

## Achievements

- **4th place, Hackfest'25** (IIT ISM Dhanbad), with a Pre-Placement Interview offer from HF ILNB Financial Services.
- **1st runner-up, Hackatron'25** (BIT Sindri).
- **General Secretary**, Dhwani Music Society, BIT Mesra.
- **Goethe-Institut German A1** certified.

---

## GitHub Statistics

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=Sarthak-Shreshtha01&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=A9FEF7&icon_color=A9FEF7&text_color=C9D1D9" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sarthak-Shreshtha01&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A9FEF7&text_color=C9D1D9" />
</div>
<br>
<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Sarthak-Shreshtha01&theme=tokyonight&hide_border=true&background=0D1117&ring=A9FEF7&fire=A9FEF7&currStreakLabel=A9FEF7" alt="GitHub Streak Stats" />
</div>

---

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Sarthak-Shreshtha01/Sarthak-Shreshtha01/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Sarthak-Shreshtha01/Sarthak-Shreshtha01/output/github-contribution-grid-snake.svg">
    <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/Sarthak-Shreshtha01/Sarthak-Shreshtha01/output/github-contribution-grid-snake.svg">
  </picture>
</div>

---

<div align="center">

### Let's Connect

<a href="https://www.linkedin.com/in/sarthak-shreshtha/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:sarthakshreshtha345@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://www.sarthakshreshtha.dev/"><img src="https://img.shields.io/badge/Portfolio-1E2761?style=for-the-badge&logo=vercel&logoColor=white" /></a>
<a href="https://leetcode.com/u/sarthakshreshtha345/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" /></a>

</div>
