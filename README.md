<div align="center">

# Sarthak Shreshtha

**Backend Engineer · Open Source Contributor @ Kubescape (CNCF) · CS @ BIT Mesra '27**

<a href="https://www.sarthakshreshtha.dev/"><img src="https://img.shields.io/badge/Portfolio-1E2761?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
<a href="https://www.linkedin.com/in/sarthak-shreshtha/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://drive.google.com/file/d/1jspxlxYZPGKAYRdut__0VwtkpQnUoNfx/view?usp=sharing"><img src="https://img.shields.io/badge/Resume-D14836?style=for-the-badge&logo=googledrive&logoColor=white" alt="Resume" /></a>
<a href="mailto:sarthakshreshtha345@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://leetcode.com/u/sarthakshreshtha345/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" /></a>

<a href="https://github.com/search?q=org%3Akubescape+is%3Apr+is%3Amerged+author%3ASarthak-Shreshtha01&type=pullrequests"><img src="https://img.shields.io/badge/Kubescape-38%20merged%20PRs-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubescape: 38 merged PRs" /></a>
<a href="https://github.com/search?q=org%3Ac2siorg+is%3Apr+is%3Amerged+author%3ASarthak-Shreshtha01&type=pullrequests"><img src="https://img.shields.io/badge/https://github.com/search?q=org%3Ac2siorg+is%3Apr+is%3Amerged+author%3ASarthak-Shreshtha01&type=pullrequestsSI-10%2B%20merged%20PRs-F57C00?style=flat-square&logo=github&logoColor=white" alt="https://github.com/search?q=org%3Ac2siorg+is%3Apr+is%3Amerged+author%3ASarthak-Shreshtha01&type=pullrequestsSI: 10+ merged PRs" /></a>
<img src="https://komarev.com/ghpvc/?username=Sarthak-Shreshtha01&label=Profile%20views&color=0e75b6&style=flat-square" alt="Profile views" />

</div>

---

Backend engineer and final-year Computer Science student at BIT Mesra. I build APIs and event-driven systems in TypeScript and Node.js, and I contribute to cloud-native open source in Go, mainly **Kubescape (CNCF)**.

---

## Open source

### Kubescape (CNCF): [38 merged PRs](https://github.com/search?q=org%3Akubescape+is%3Apr+is%3Amerged+author%3ASarthak-Shreshtha01&type=pullrequests)

Kubescape is a Kubernetes security platform. My work covers the CLI, the in-cluster storage component, the Rego control library, the Helm charts and the docs.

- **Read-only MCP endpoint in the cluster.** I wrote the [design proposal](https://github.com/kubescape/designs-and-proposals/pull/27) and then built it in `kubescape/storage`. AI assistants can now query vulnerability, SBOM, configuration-scan and container-profile data that is already stored in the cluster, without any scan running. This added the `MCPServer` API type, the endpoint and its tools, and the [Helm values](https://github.com/kubescape/helm-charts/pull/989) that turn it on.
- **MCP server in the Kubescape CLI.** Added SBOM tools and scan summaries, plus filtering and paging, so that results from large clusters fit in an assistant's context.
- **Security fixes.** Scan result files written by the HTTP handler are now readable only by their owner, and file paths no longer leak through scan errors.
- **CLI bug fixes.** Reports and diffs now land inside the `--output` directory, the account ID is validated as a UUID, and API server info is collected on every cluster scan.
- **Control library fixes.** Rego rules that read the wrong object or dropped the node name from their results.
- **Documentation.** Documented all 31 MCP tools, explained when operator storage data is lost, and fixed Helm chart docs that listed keys the chart never reads.

### C2SI: [10+ merged PRs](https://github.com/search?q=org%3Ac2siorg+is%3Apr+is%3Amerged+author%3ASarthak-Shreshtha01&type=pullrequests)

- **ImageLab.** Images with transparency lost their alpha channel in brightness, contrast and histogram equalisation; they now keep it.
- **ImageLab.** Python scripts exported from the app gave different results from the app itself. The exported Sepia, brightness/contrast, CLAHE, Gabor, Sobel, Scharr and Prewitt filters and shape drawing now match.
- **TensorMap.** Fixed a path traversal bug, so uploaded files can no longer be written outside the upload folder.
- **TensorMap.** Paginated file previews counted lines instead of CSV records, which broke on fields that span lines.
- **DataLoom.** Fixed filtering of boolean columns, and rejected aggregations that use the group-by column as the value column.

---

## Experience

**Software Developer Intern, Quickeee** · May 2026 – Jul 2026

- Cut order sync latency from 120 s to under 5 ms by replacing polling with Redis Pub/Sub signals and priority-based BullMQ workers.
- Built a nightly inventory reconciliation job with Unicommerce (BullMQ, Redis, cron), with an API to run it on demand.
- Shipped 30+ REST APIs for purchase orders, inventory, refunds and warehouse operations, including SKU search and cache invalidation.
- Implemented the warehouse fulfilment flow from purchase order to manifest, and fixed webhook delivery for four order types.

**Full-Stack Developer, Productimate AI Solutions** · May 2025 – Jan 2026

- Built features for several B2B SaaS products with Next.js, React Native, Node.js and PostgreSQL.
- Implemented PhonePe subscription billing, role-based access control, AI-assisted email drafting and CSV lead import.
- Integrated AWS S3, CloudWatch, GA4 and Hygraph, and improved Core Web Vitals through SSR and lazy loading.

---

## Projects

**TradeX**: a portfolio dashboard that connects Zerodha, Angel One and Upstox over WebSockets and tracks 200+ instruments with sub-100 ms updates. A Gemini-based assistant suggests trades and cut manual research time by about 40%.

<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" /> <img src="https://img.shields.io/badge/WebSockets-4353FF?style=flat-square&logo=socketdotio&logoColor=white" alt="WebSockets" /> <img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini" />

**Pantheon'25**: the website for BIT Mesra's technical fest. It scored 100 on Lighthouse SEO, loads in under 2 s on mobile, and handled 10,000+ concurrent visitors at peak without downtime. [Live](https://pantheon-2k25-gules.vercel.app) · [Code](https://github.com/RishavK010/Pantheon-2k25)

<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" /> <img src="https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=black" alt="GSAP" /> <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind_CSS" />

---

## Skills

<div align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,go,python,cpp,java" />
  <br />
  <img src="https://skillicons.dev/icons?i=nodejs,nestjs,express,graphql,prisma,react,nextjs,tailwind" />
  <br />
  <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,kafka,docker,kubernetes,aws,linux,git" />
</div>

- **Languages:** TypeScript, JavaScript, Go, Python, C++, Java
- **Backend:** Node.js, NestJS, Express, REST, GraphQL, Prisma
- **Data:** PostgreSQL, MySQL, MongoDB, Redis, BullMQ, Kafka
- **Frontend:** React, Next.js, React Native, Tailwind CSS
- **Infrastructure:** Docker, Kubernetes, AWS, Linux, Git

---

## Education

**Birla Institute of Technology, Mesra**: B.Tech in Computer Science and Engineering, 2023 – 2027, CGPA 8.4/10

---

## Achievements

- 4th place at Hackfest'25 (IIT ISM Dhanbad), with a pre-placement interview offer from HF ILNB Financial Services
- 1st runner-up at Hackatron'25 (BIT Sindri)
- General Secretary of Dhwani, the music society of BIT Mesra
- Goethe-Institut German A1

---

<div align="center">

## GitHub stats

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Sarthak-Shreshtha01&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=A9FEF7&icon_color=A9FEF7&text_color=C9D1D9" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sarthak-Shreshtha01&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A9FEF7&text_color=C9D1D9" alt="Top languages" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Sarthak-Shreshtha01&theme=tokyonight&hide_border=true&background=0D1117&ring=A9FEF7&fire=A9FEF7&currStreakLabel=A9FEF7" alt="GitHub streak" />

</div>
