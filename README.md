<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=250&section=header&text=Vaibhav%20Gupta&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Full%20Stack%20Developer%20%7C%20AI%2FML%20Enthusiast%20%7C%20Software%20Engineer&descAlignY=55&descSize=20" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=A78BFA&center=true&vCenter=true&width=750&lines=Building+Scalable+Full+Stack+Applications;Architecting+Secure%2C+Role-Based+Systems;React+%7C+Next.js+%7C+Node.js+%7C+MongoDB;Open+to+Software+Development+Internships" alt="Typing SVG" />
</a>

<br/>

![Academic](https://img.shields.io/badge/B.Tech-Computer%20Science-6D28D9?style=for-the-badge&logo=googlescholar&logoColor=white)
![University](https://img.shields.io/badge/Bennett%20University-CGPA%208.82-7C3AED?style=for-the-badge&logo=studyverse&logoColor=white)
![Location](https://img.shields.io/badge/Location-Greater%20Noida%2C%20India-5B21B6?style=for-the-badge&logo=googlemaps&logoColor=white)

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-8B5CF6?style=for-the-badge&logo=vercel&logoColor=white)](https://vaibhavgportfolio.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-6D28D9?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vaibhavguptahere-/)
[![Email](https://img.shields.io/badge/Email-4C1D95?style=for-the-badge&logo=gmail&logoColor=white)](mailto:guptavaibhavg2005@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-7C3AED?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vaibhavguptahere)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=vaibhavguptahere&label=Profile%20Views&color=6D28D9&style=flat-square)
![Followers](https://img.shields.io/github/followers/vaibhavguptahere?label=Followers&style=flat-square&color=7C3AED)
![Stars](https://img.shields.io/github/stars/vaibhavguptahere?label=Stars&style=flat-square&color=8B5CF6)

</div>

---

## About Me

Computer Science undergraduate at Bennett University (CGPA 8.82/10.0) with hands-on experience in full stack development, end-to-end software engineering, and AI integration. I architect scalable web and mobile applications using React.js, Next.js, and Node.js, with a strong focus on secure data management, role-based access control, and system efficiency.

My work spans healthcare, civic-tech, and fintech domains — from building role-based dashboards and RESTful APIs to integrating generative AI assistants into production-style applications. I approach engineering with a product mindset: solving real user problems with clean, maintainable architecture.

**Open To:**
- Software Development Internships
- Full Stack Development Projects
- AI/ML Integration Work
- Open Source Contributions

---

## Tech Stack

**Languages**

<img src="https://skillicons.dev/icons?i=js,python,cpp,java,html,css" />

**Frontend & Mobile**

<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,expo" />

**Backend & Databases**

<img src="https://skillicons.dev/icons?i=nodejs,express,mongodb,supabase,prisma" />

**Cloud, DevOps & Tooling**

<img src="https://skillicons.dev/icons?i=aws,git,github,postman,vercel" />

---

## AI / ML Expertise

| Domain | Proficiency | Details |
|---|---|---|
| Machine Learning Fundamentals | ⭐⭐⭐☆☆ | Core ML concepts and data preprocessing techniques |
| Data Preprocessing | ⭐⭐⭐☆☆ | Cleaning, transforming, and structuring data for downstream use |
| Applied AI in Full Stack Apps | ⭐⭐⭐⭐☆ | Built AI-powered features (e.g. spending pattern analysis, conversational financial assistant) inside live full stack projects |

---

## Featured Projects

<details>
<summary><strong>BreathLine – Healthcare Management Platform</strong></summary>
<br/>

A role-based medical records platform built to solve a real access-control problem: patients, doctors, and emergency responders each need different views of the same data, instantly, without compromising security.

**What I actually built:**
- Designed the **RBAC (Role-Based Access Control) schema** from scratch — modeling permission boundaries so a doctor's dashboard, a patient's records view, and an emergency responder's QR-scan lookup all query the same underlying data with different authorization rules
- Architected the **API layer in Next.js** using route handlers structured around resource ownership rather than a flat endpoint list, so access checks live at the data layer, not just the UI
- Designed the **MongoDB schema** to support fast lookups by role and record type, avoiding N+1-style query patterns across dashboards
- Built the **QR-based emergency access flow** — encoding a scoped, time-relevant lookup token rather than exposing full patient records via a static QR code
- Integrated **Cloudinary** for medical document/media storage with access tied to the same RBAC layer, not a separate permissions system

| Category | Details |
|---|---|
| Stack | Next.js, MongoDB, Cloudinary |
| Scale | Multi-role platform supporting patients, doctors, and emergency responders |
| Performance | Real-time medical data accessibility across role-based dashboards |
| Security | Role-Based Access Control (RBAC) with secure authentication and authorization workflows |
| Impact | Enables instant emergency medical data access via QR-based interfaces |
| Repository | [Add GitHub link] |

</details>

<details>
<summary><strong>JanConnect – Civic Issue Reporting App</strong></summary>
<br/>

A cross-platform civic reporting app where the hard problem wasn't the UI — it was coordinating three distinct user roles (citizens, contractors, administrators) through one shared issue-resolution lifecycle without them stepping on each other's data.

**What I actually built:**
- Designed the **state machine for issue lifecycle** — reported → assigned → in-progress → resolved — so each role only sees and can act on the states relevant to them
- Implemented **geolocation-based issue tracking** using device location APIs in React Native (Expo), tying each report to coordinates for contractor dispatch
- Built **Supabase row-level security policies** so contractors only see issues assigned to them and administrators retain full visibility — access control enforced at the database layer, not just hidden in the UI
- Designed separate **contractor and admin dashboards** as distinct views over the same tender-resolution data model, rather than duplicating logic across role-specific apps
- Integrated **Cloudinary** for issue-evidence photo uploads tied to each report's lifecycle state

| Category | Details |
|---|---|
| Stack | React Native (Expo), Supabase, Cloudinary |
| Scale | Multi-user system spanning citizens, contractors, and administrators |
| Performance | Real-time geolocation tracking and status updates on reported issues |
| Security | Role-specific access flows enforced via Supabase row-level security |
| Impact | Streamlines civic issue reporting and tender resolution tracking end-to-end |
| Repository | [Add GitHub link] |

</details>

<details>
<summary><strong>Bachat Bhai – AI-Powered Finance Tracker</strong></summary>
<br/>

A personal finance tracker where the goal was to make an AI assistant genuinely useful for financial insight, not a chatbot bolted onto a CRUD app.

**What I actually built:**
- Modeled the **transaction, budget, and recurring-expense schema in Prisma ORM**, designing relations so spending-pattern queries (by category, by time window, by recurrence) stay performant as data grows
- Integrated the **Perplexity generative AI API** with a structured prompt/context pipeline — feeding the model scoped transaction summaries rather than raw data dumps, so responses stay accurate to the user's actual spending
- Built the **automated notification pipeline**: scheduled jobs that check budget thresholds and trigger monthly email summaries, decoupled from the main request/response cycle so they don't block the app
- Implemented **authentication and session handling via Clerk**, wiring it into Prisma's user model so every financial record is scoped to an authenticated owner
- Designed the **conversational query flow** so the AI assistant answers spending questions by pulling from the user's real transaction data, not generic financial advice

| Category | Details |
|---|---|
| Stack | Next.js, Prisma, Generative AI API (Perplexity), Clerk |
| Scale | Full transaction, budget, and recurring-expense tracking system |
| Performance | Automated monthly email summaries and real-time budget threshold notifications |
| Security | Authentication and data scoping handled via Clerk |
| Impact | Delivers AI-driven financial insights and proactive budget alerts to users |
| Repository | [Add GitHub link] |

</details>

---

## Experience

**Frontend Development Intern · HiTutor**
*Aug 2025 – Present · Remote*

Contributing to student and teacher-facing dashboards as part of a remote engineering team, with a focus on reusable, consistent UI architecture.

- Developed 7+ responsive UI components using React.js, ensuring consistency across student and teacher dashboards
- Engineered 10+ reusable modules, reducing development time for new features and improving maintainability
- Collaborated with backend teams to integrate APIs and align frontend architecture with business requirements
- Used Git/GitHub for version control and participated in collaborative code reviews in an Agile environment

`React.js` `Git` `GitHub` `REST APIs` `Agile`

**Community Research Member · BU Research Society**
*Oct 2024 – Sept 2025 · Greater Noida*

Contributed to the university's research community through event organization and technical writing.

- Co-organized ResCon 4.0 in collaboration with academic and industry professionals from Deloitte and the Indian Air Force
- Strengthened technical documentation skills by contributing content to the official BURS newsletter

`Technical Writing` `Event Organization` `Community Research`

---

## Achievements

<div align="center">

| Recognition | Details |
|---|---|
| AWS Certified Cloud Practitioner | Amazon Web Services, 2026 |
| ResCon 4.0 Co-Organizer | Collaborated with professionals from Deloitte and the Indian Air Force via BU Research Society |
| CGPA 8.82/10.0 | B.Tech Computer Science, Bennett University |

</div>

---

## Certifications

**AWS**

![AWS Certified Cloud Practitioner](https://img.shields.io/badge/AWS%20Certified%20Cloud%20Practitioner-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)

Certification ID: `5aa5a0cfcb0045628110948e49c9007a` — demonstrates foundational knowledge of AWS Cloud concepts, core services, security, architecture, pricing, and support.

---

## Coding Profiles

[![LeetCode](https://img.shields.io/badge/LeetCode-000000?style=for-the-badge&logo=leetcode&logoColor=orange)](https://leetcode.com/u/vaibhavguptahere/)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/vaibhavguptahere)

---

## GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=vaibhavguptahere&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A78BFA&icon_color=8B5CF6&text_color=C9D1D9" width="49%"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=vaibhavguptahere&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A78BFA&text_color=C9D1D9" width="35%"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=vaibhavguptahere&theme=tokyonight&hide_border=true&background=0D1117&ring=8B5CF6&fire=A78BFA&currStreakLabel=A78BFA" width="70%"/>

</div>

---

## Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=vaibhavguptahere&theme=react-dark&hide_border=true&bg_color=0D1117&color=A78BFA&line=8B5CF6&point=C9D1D9" width="100%"/>

</div>

---

## Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/vaibhavguptahere/vaibhavguptahere/output/github-contribution-grid-snake-dark.svg" width="100%"/>

</div>

> **Setup required:** this image only renders once a GitHub Action generates it in your profile repo. See the workflow snippet below.

---

## Current Focus

```yaml
learning:
  - "Advanced Machine Learning & Generative AI integration"
  - "System design for scalable full stack applications"

building:
  - "Full stack products across healthcare, civic-tech, and fintech domains"
  - "Role-based, secure application architectures"

exploring:
  - "Generative AI API integration in production applications"
  - "Cloud architecture on AWS"

open_to:
  - "Software Development Internships"
  - "Full Stack Development Projects"
  - "AI/ML Integration Work"
  - "Open Source Contributions"
```

---

## Connect

[![Gmail](https://img.shields.io/badge/Gmail-4C1D95?style=for-the-badge&logo=gmail&logoColor=white)](mailto:guptavaibhavg2005@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-6D28D9?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vaibhavguptahere-/)
[![GitHub](https://img.shields.io/badge/GitHub-7C3AED?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vaibhavguptahere)
[![Portfolio](https://img.shields.io/badge/Portfolio-8B5CF6?style=for-the-badge&logo=vercel&logoColor=white)](https://vaibhavgportfolio.netlify.app/)

---

<div align="center">

*"Engineering secure, scalable software — one role-based dashboard at a time."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=150&section=footer" width="100%"/>

</div>
