<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=260&section=header&text=Abhishek%20Kr.%20Mishra&fontSize=42&fontColor=fff&fontAlignY=35&animation=fadeIn&desc=Software%20Engineer%20%7C%20Full%20Stack%20%7C%20ML%20Enthusiast&descSize=16&descAlignY=55" width="100%"/>

<a href="https://www.abhishekmishra.me/">
  <img src="https://img.shields.io/badge/Portfolio-abhishekmishra.me-6C3EF4?style=for-the-badge&logo=aboutdotme&logoColor=white" />
</a>
<a href="https://www.linkedin.com/in/abhishekmishra028">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="https://twitter.com/kr_abhi__">
  <img src="https://img.shields.io/badge/Twitter-Follow-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" />
</a>
<a href="mailto:kumarabhishekmishra28@gmail.com">
  <img src="https://img.shields.io/badge/Email-Say%20Hi-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

<br/><br/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=6C3EF4&center=true&vCenter=true&width=650&lines=Building+scalable+full-stack+systems...;Turning+data+into+decisions+with+ML...;Currently+shipping+RateShield+%26+SplitMate...;500%2B+DSA+problems+solved+and+counting..." alt="Typing SVG" />
</a>

</div>

---

### 🚀 About Me

I'm a third-year B.Tech Computer Science student at Lovely Professional University, building at the intersection of **Machine Learning** and **Full Stack Engineering**. I like tearing down real, messy problems — split expenses with floating-point drift, APIs getting hammered by bots, banking systems that need to stay correct under concurrency — and rebuilding them as clean, production-grade systems.

- 🔭 Currently building **RateShield**, a Redis-backed rate limiting service, and refining **SplitMate**, an expense-splitting engine with an anomaly-detecting CSV importer
- 🌱 Deepening my grip on **System Design**, distributed systems primitives (Redis, Lua scripting, concurrency), and advanced DSA
- 💬 Ask me about **MERN**, ML pipelines, or API architecture
- ⚡ Fun fact: I've solved 500+ DSA problems across LeetCode, GFG, HackerRank & Codeforces

---

### 🛠️ Tech Arsenal

<p align="left">
  <img src="https://skillicons.dev/icons?i=js,ts,react,nextjs,nodejs,express,mongodb,mysql,postgres,redis,cpp,tailwind,docker,git,github,vercel,figma&perline=9" />
</p>

<p align="left">
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" />
  <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" />
  <img src="https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white" />
  <img src="https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white" />
  <img src="https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white" />
  <img src="https://img.shields.io/badge/ShadCN-F4F4F5?style=flat-square&logo=shadcnui&logoColor=000000" />
  <img src="https://img.shields.io/badge/Radix_UI-EFECFF?style=flat-square&logo=radixui&logoColor=000000" />
</p>

---

### 🏆 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

#### 🛡️ [RateShield](https://github.com/abhishekmishra28/RateShield)
**High-performance API rate limiter service**

Production-grade backend that sits in front of APIs and blocks abuse using Token Bucket & Sliding Window algorithms, both executed atomically via Redis Lua scripts to stay race-condition-free under load.

- ⚙️ Strategy + Factory pattern for pluggable rate-limit algorithms
- 🐳 Fully Dockerized with CI via GitHub Actions
- 📊 k6 load-tested: `>1,000 req/s`, `p95 < 100ms`
- 🧪 55+ unit & integration tests (Jest + Supertest)

`Node.js` `Express 5` `Redis` `PostgreSQL` `Prisma` `Docker`

</td>
<td width="50%" valign="top">

#### 💸 [SplitMate](https://github.com/abhishekmishra28/SplitMate)
**Expense-splitting app that survives real-world chaos**

Solves "who owes whom" with mathematical precision — handling mid-month roommate turnover, unequal/percentage/share-based splits, floating-point currency drift, and messy CSV imports.

- 🧮 Dynamic split engine (equal, unequal, % , shares)
- 📅 Temporal group memberships (join/leave date aware)
- 🧠 Smart CSV importer running 19 anomaly-detection checks
- 🔍 Transparent audit trail — "no magic numbers"

`React (Vite)` `Node.js` `Express` `NeonDB` `JWT`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🦆 [GiffyDuck Notes](https://www.giffyduck.com/)
**AI-powered notes & creative writing assistant**

A full-stack notes platform blending traditional note management with Gemini-powered AI assistance, semantic search, and productivity tooling.

- 🤖 AI chat assistant for writing & summarization
- 🔐 JWT auth with OTP email verification
- 🏷️ Tag-based organization + full-text search
- 📊 Admin dashboard with analytics

`React` `TypeScript` `Node.js` `MongoDB` `Gemini API` `Redux Toolkit`

</td>
<td width="50%" valign="top">

#### 🏦 [C++ Banking System](https://github.com/abhishekmishra28/Banking-System)
**Multi-threaded banking engine in C++20**

A from-scratch banking backend showcasing OOP design, concurrency-safe accounts, a custom TCP server, and SQLite persistence — benchmarked up to **657K txns/sec** across 8 worker threads.

- 🔒 `shared_mutex` + `scoped_lock` for deadlock-free transfers
- 🌐 Cross-platform TCP server with a live text protocol
- 📈 Built-in benchmarking: TPS + p50/p95/p99 latency
- 🛡️ Rule-based fraud detection pipeline

`C++20` `SQLite` `CMake` `Multithreading` `TCP/IP`

</td>
</tr>
</table>

<details>
<summary><b>🩸 More projects worth a look</b></summary>
<br/>

- **[BloodBridge](https://blood-bridge-rho.vercel.app/)** — MERN blood donation platform with role-based dashboards, slot booking, and admin analytics
- **[Soninavratna Jewellers](https://www.soninavratnajewellers.in/)** — Online jewelry storefront built with Next.js & Supabase
- **[Crop Recommendation System](https://crop-recommendation-system-45.streamlit.app/)** — ML model recommending crops from soil & environmental data

</details>

---

### 📊 GitHub Analytics

<div align="center">
<img width="48%" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=abhishekmishra28&theme=github_dark" />
<img width="48%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=abhishekmishra28&theme=github_dark" />
</div>

<div align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=abhishekmishra28&theme=tokyonight&hide_border=true" />
</div>

<div align="center">

**LeetCode**

<img src="https://leetcard.jacoblin.cool/abhishekmishra2002?theme=dark&font=baloo" />

</div>

<div align="center">

#### 🐍 Contribution Snake

<img src="https://raw.githubusercontent.com/abhishekmishra28/abhishekmishra28/output/snake.svg" />

</div>

---

### 📚 What I'm Sharpening Right Now

| Area | Focus |
|---|---|
| 🧠 DSA | 450+ LeetCode + 500+ across GFG, HackerRank, Codeforces |
| 🏗️ System Design | Scalability patterns, distributed caching, rate limiting |
| ⚙️ MERN Mastery | Production-grade auth, testing, CI/CD pipelines |
| 🎯 Placements | Preparing for SDE roles at top tech companies |

---

<div align="center">

### 📬 Let's Build Something

<a href="mailto:kumarabhishekmishra28@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/abhishekmishra028"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://twitter.com/kr_abhi__"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" /></a>
<a href="https://www.abhishekmishra.me/"><img src="https://img.shields.io/badge/Portfolio-03A062?style=for-the-badge&logo=about.me&logoColor=white" /></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=abhishekmishra28&style=flat-square&color=6C3EF4&label=Profile+Views" />

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

</div>
