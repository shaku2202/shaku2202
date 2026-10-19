<!-- SHASHANK SINGH | GITHUB PROFILE README -->

<h1 align="center">Hi, I'm Shashank Singh 👋</h1>

<p align="center">
  <a href="https://portfolio-lake-two-81.vercel.app/">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=3000&pause=900&color=2F81F7&center=true&vCenter=true&width=720&lines=Full+Stack+Software+Engineer+%C2%B7+3%2B+years;Node.js+%C2%B7+TypeScript+%C2%B7+Go+%C2%B7+AWS+%C2%B7+PostgreSQL;Government+%26+fintech+platforms+at+national+scale;Serverless+%C2%B7+Microservices+%C2%B7+Secure+APIs" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <b>I build full stack products that stay fast, secure and cheap at national scale.</b>
</p>

<p align="center">
  <a href="https://portfolio-lake-two-81.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>
  <a href="https://linkedin.com/in/shashank-singh-8b5a471aa"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://leetcode.com/u/shashank_masai"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
  <a href="mailto:shashank.psit057@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://portfolio-lake-two-81.vercel.app/Shashank_Singh_Resume.pdf"><img src="https://img.shields.io/badge/Resume-2F81F7?style=for-the-badge&logo=readthedocs&logoColor=white" alt="Resume"/></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Open%20to%20work-2EA043?style=flat-square" alt="Open to work"/>
  <img src="https://img.shields.io/badge/Notice-Immediate%20joiner-2EA043?style=flat-square" alt="Immediate joiner"/>
  <img src="https://img.shields.io/badge/Location-Noida%2C%20India%20%C2%B7%20Remote%20%2F%20Relocate-555?style=flat-square" alt="Location"/>
</p>

---

## 🧑‍💻 About Me

I'm a full stack engineer with **3+ years** on **government and fintech platforms**, working from React screens down to Node.js and Go services, AWS and the database underneath.

On every system I design, I think about three things: **who can access what**, **how it behaves under load**, and **what it costs to run each month**.

- 🏛️ Shipped production systems for **NPS (National Pension Scheme)**, **Aadhaar eSign** and **PAN 2.0**
- ☁️ Designed and owned a **serverless AWS platform** end to end with infrastructure as code (CDK)
- 🔐 Built auth & RBAC with **Keycloak, OAuth 2.0 and JWT** that cleared a **government security audit**
- 🎯 Looking for a team that wants products owned from **design to production**

---

## 📊 Impact at a Glance

<div align="center">

| 🚀 **400+** | 💸 **70%** | ⚡ **40%** | ✅ **90%+** |
|:---:|:---:|:---:|:---:|
| REST APIs shipped to production | Cloud cost cut on UtsavWale | Lower p95 latency on PAN 2.0 | Jest coverage on ESign Pro |

</div>

---

## 💼 Experience

### Backend Software Engineer · [MoneyMul Technology Pvt. Ltd.](https://portfolio-lake-two-81.vercel.app/#work)
`May 2024 – Sep 2026` · Noida

- Built and maintained backend systems for **government and fintech** platforms (NPS, ESign Pro, PAN 2.0) and **led UtsavWale** end to end
- Owned **AWS infrastructure as code** with CDK across Dev, UAT and Production, with CodePipeline and a manual production gate
- Standardized error handling, request validation and contract testing, cutting **production regressions by 30%**

### Backend Developer Intern · Masai School
`Aug 2023 – Apr 2024` · Bengaluru

- Built a **real-time video and messaging platform** with WebRTC and Socket.IO
- Reworked the signalling path to cut **message latency by 25%**

---

## 🛠️ Featured Work

<table>
<tr>
<td width="50%" valign="top">

### 📸 [UtsavWale](https://portfolio-lake-two-81.vercel.app/work/utsavwale)
**Multi-tenant event-photo platform** · *Led end to end*

Organizers upload albums; guests find their own photos with a **selfie + liveness check**.

- **320+ REST APIs** on Express running on **AWS Lambda**
- Face-search pipeline: **SQS-fed workers** dedupe, resize and index faces in **Rekognition**, with **DLQs** so no photo is lost
- PostgreSQL via **RDS Proxy** + DynamoDB; whole stack in **AWS CDK**
- Cut cloud cost by **70%** with no change to read latency

`Next.js` `TypeScript` `Lambda` `SQS` `Rekognition` `DynamoDB` `CDK`

🔗 [Live](https://one.utsavwale.ai/login) · [Case study](https://portfolio-lake-two-81.vercel.app/work/utsavwale)

</td>
<td width="50%" valign="top">

### ✍️ [ESign Pro](https://portfolio-lake-two-81.vercel.app/work/esign-pro)
**B2B digital signing platform** · *Banks, NBFCs, corporates*

Aadhaar eSign, DSC, e-Stamp, wallet billing and webhooks.

- **100+ REST APIs** for legally binding workflows: maker-checker, **sequential / parallel / hybrid** signing, full audit trails
- **Atomic wallet billing** (reserve → settle → reverse)
- **HMAC-signed webhooks** + email, SMS and WhatsApp notifications
- **90%+ Jest coverage**, 30% fewer production regressions

`Node.js` `Express` `PostgreSQL` `Sequelize` `Redis` `Keycloak`

🔗 [Live](https://esign-proteantech.in/login) · [Case study](https://portfolio-lake-two-81.vercel.app/work/esign-pro)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏛️ [NPS](https://portfolio-lake-two-81.vercel.app/work/nps)
**National Pension Scheme onboarding** · *PFRDA-regulated*

Pension account opening across Individual, Corporate and Vatsalya journeys.

- Maintained **Go backend services** for subscriber registration
- Fixed defects across **KYC, OTP validation and resume-journey** flows, improving onboarding reliability

`Go` `REST APIs` `KYC` `OTP`

🔗 [Case study](https://portfolio-lake-two-81.vercel.app/work/nps)

</td>
<td width="50%" valign="top">

### 🪪 [PAN 2.0](https://portfolio-lake-two-81.vercel.app/work/pan-2)
**National PAN issuance & KYC** · *Income Tax Department proposal*

- Led the move from a **monolith to domain-owned microservices**; releases went from weekly to **daily**
- **Keycloak + OAuth 2.0 + JWT** with fine-grained RBAC across **200+ Aadhaar KYC endpoints**, zero critical findings in a government audit
- **40% lower p95 latency** with Redis caching, query rewrites and composite indexes

`Node.js` `TypeScript` `Microservices` `Keycloak` `Aurora PostgreSQL`

🔗 [Case study](https://portfolio-lake-two-81.vercel.app/work/pan-2)

</td>
</tr>
</table>

---

## 🧰 Tech Stack

**Languages**
<p>
  <img src="https://skillicons.dev/icons?i=ts,js,go,python&perline=10" alt="Languages"/>
  <img src="https://img.shields.io/badge/SQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" height="40" alt="SQL"/>
</p>

**Backend**
<p>
  <img src="https://skillicons.dev/icons?i=nodejs,express,sequelize&perline=10" alt="Backend"/>
  <img src="https://img.shields.io/badge/REST%20APIs-005571?style=for-the-badge" height="40" alt="REST"/>
  <img src="https://img.shields.io/badge/Microservices-6E40C9?style=for-the-badge" height="40" alt="Microservices"/>
  <img src="https://img.shields.io/badge/Event--Driven-F05032?style=for-the-badge" height="40" alt="Event-driven"/>
  <img src="https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socketdotio&logoColor=white" height="40" alt="Socket.IO"/>
  <img src="https://img.shields.io/badge/WebRTC-333333?style=for-the-badge&logo=webrtc&logoColor=white" height="40" alt="WebRTC"/>
</p>

**Frontend**
<p>
  <img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,html,css&perline=10" alt="Frontend"/>
</p>

**Databases & Caching**
<p>
  <img src="https://skillicons.dev/icons?i=postgres,mongodb,mysql,redis&perline=10" alt="Databases"/>
  <img src="https://img.shields.io/badge/DynamoDB-4053D6?style=for-the-badge&logo=amazondynamodb&logoColor=white" height="40" alt="DynamoDB"/>
  <img src="https://img.shields.io/badge/Aurora%20PostgreSQL-527FFF?style=for-the-badge&logo=amazonrds&logoColor=white" height="40" alt="Aurora"/>
</p>

**Cloud & DevOps**
<p>
  <img src="https://skillicons.dev/icons?i=aws,gcp,docker,kubernetes,githubactions,jenkins,linux&perline=10" alt="Cloud"/>
</p>
<p>
  <img src="https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white" alt="Lambda"/>
  <img src="https://img.shields.io/badge/API%20Gateway-FF4F8B?style=flat-square&logo=amazonapigateway&logoColor=white" alt="API Gateway"/>
  <img src="https://img.shields.io/badge/SQS-FF4F8B?style=flat-square&logo=amazonsqs&logoColor=white" alt="SQS"/>
  <img src="https://img.shields.io/badge/SNS-FF4F8B?style=flat-square&logo=amazonsimpleemailservice&logoColor=white" alt="SNS"/>
  <img src="https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazons3&logoColor=white" alt="S3"/>
  <img src="https://img.shields.io/badge/CloudFront-8C4FFF?style=flat-square&logo=amazonaws&logoColor=white" alt="CloudFront"/>
  <img src="https://img.shields.io/badge/RDS%20Proxy-527FFF?style=flat-square&logo=amazonrds&logoColor=white" alt="RDS"/>
  <img src="https://img.shields.io/badge/Cognito-DD344C?style=flat-square&logo=amazonaws&logoColor=white" alt="Cognito"/>
  <img src="https://img.shields.io/badge/Rekognition-01A88D?style=flat-square&logo=amazonaws&logoColor=white" alt="Rekognition"/>
  <img src="https://img.shields.io/badge/AWS%20CDK-FF9900?style=flat-square&logo=amazonaws&logoColor=white" alt="CDK"/>
  <img src="https://img.shields.io/badge/CodePipeline-527FFF?style=flat-square&logo=amazonaws&logoColor=white" alt="CodePipeline"/>
  <img src="https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white" alt="Helm"/>
  <img src="https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white" alt="ArgoCD"/>
</p>

**Security, Workflows & Integrations**
<p>
  <img src="https://img.shields.io/badge/Keycloak-4D4D4D?style=flat-square&logo=keycloak&logoColor=white" alt="Keycloak"/>
  <img src="https://img.shields.io/badge/OAuth%202.0-EB5424?style=flat-square&logo=auth0&logoColor=white" alt="OAuth"/>
  <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" alt="JWT"/>
  <img src="https://img.shields.io/badge/RBAC-555555?style=flat-square" alt="RBAC"/>
  <img src="https://img.shields.io/badge/Temporal-000000?style=flat-square&logo=temporal&logoColor=white" alt="Temporal"/>
  <img src="https://img.shields.io/badge/Razorpay-0C2451?style=flat-square&logo=razorpay&logoColor=white" alt="Razorpay"/>
  <img src="https://img.shields.io/badge/Aadhaar%20eSign%20%2F%20KYC-1E90FF?style=flat-square" alt="Aadhaar"/>
</p>

**Testing & Quality**
<p>
  <img src="https://skillicons.dev/icons?i=jest,postman&perline=10" alt="Testing"/>
  <img src="https://img.shields.io/badge/Mocha-8D6748?style=for-the-badge&logo=mocha&logoColor=white" height="40" alt="Mocha"/>
  <img src="https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white" height="40" alt="SonarQube"/>
  <img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black" height="40" alt="Swagger"/>
</p>

---

## 🏗️ How I Build

```ts
const engineeringPrinciples = {
  security:     "RBAC & least-privilege designed up front, not bolted on",
  reliability:  "Queues, DLQs, idempotency and retries for anything that can fail",
  performance:  "Measure p95 first → cache, index, rewrite → measure again",
  cost:         "Every architecture decision has a monthly bill attached",
  delivery:     "Infra as code, CI/CD, tests in the pipeline, small safe releases",
};
```

---

## 📈 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Shaku2202&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true" height="165" alt="GitHub Stats"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Shaku2202&layout=compact&theme=github_dark&hide_border=true&langs_count=8" height="165" alt="Top Languages"/>
  <br/>
  <img src="https://streak-stats.demolab.com?user=Shaku2202&theme=github-dark-blue&hide_border=true" height="165" alt="GitHub Streak"/>
</div>

---

## 🎓 Education & Achievements

- 🎓 **B.Tech, Information Technology**, Pranveer Singh Institute of Technology, Kanpur (2019–2023)
- ⭐ **5-star Problem Solving** on HackerRank
- 💻 Regular DSA practice on [LeetCode](https://leetcode.com/u/shashank_masai)
- 🛡️ Auth design that cleared a **government security audit with zero critical findings**

---

## 🤝 Let's Connect

<p align="center">
  Hiring, or need a product built end to end? I reply within one working day.<br/><br/>
  <a href="https://portfolio-lake-two-81.vercel.app/#contact"><img src="https://img.shields.io/badge/Let's%20Talk-2F81F7?style=for-the-badge&logo=minutemailer&logoColor=white" alt="Contact"/></a>
  <a href="mailto:shashank.psit057@gmail.com"><img src="https://img.shields.io/badge/shashank.psit057@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Shaku2202&label=Profile%20views&color=2F81F7&style=flat-square" alt="Profile views"/>
</p>
