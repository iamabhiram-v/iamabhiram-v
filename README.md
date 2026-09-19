<!--
  Images live in the assets/ folder next to this README.
  To add buttons later: Portfolio -> your site URL, Live Demo -> your RoleGuard URL.
-->

<p align="center">
  <img src="assets/banner.svg" width="100%" alt="Abhiram V: Application Security and Full Stack Engineering" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/abhiram-v-297188364/"><img src="https://img.shields.io/badge/LinkedIn-Connect-e11d9a?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0b0b1e" alt="LinkedIn" /></a>
  &nbsp;
  <a href="https://github.com/iamabhiram-v"><img src="https://img.shields.io/badge/GitHub-Follow-22d3ee?style=for-the-badge&logo=github&logoColor=white&labelColor=0b0b1e" alt="GitHub" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Building_%26_Learning-ff3355?style=flat-square&labelColor=0b0b1e" alt="Status" />
  <img src="https://img.shields.io/badge/Role-Full_Stack_Developer_Intern-e11d9a?style=flat-square&labelColor=0b0b1e" alt="Role" />
  <img src="https://img.shields.io/badge/Studying-MCA_Cyber_Security_%26_AI-8b5cf6?style=flat-square&labelColor=0b0b1e" alt="Studying" />
  <img src="https://img.shields.io/badge/Aiming_For-HTB_CPTS-22d3ee?style=flat-square&labelColor=0b0b1e" alt="Aiming for HTB CPTS" />
  <img src="https://img.shields.io/badge/Based_in-Kollam,_Kerala-ff3355?style=flat-square&labelColor=0b0b1e" alt="Kollam, Kerala" />
</p>

<p align="center">
  <img src="assets/marquee-stack.svg" width="100%" alt="TypeScript, React, Redux Toolkit, Vite, Node.js, Express, PostgreSQL, Redis, BullMQ, Socket.IO, JWT, Zod, Docker, Nginx, Razorpay, Twilio" />
</p>

<p align="center"><img src="assets/divider.svg" width="100%" alt="" /></p>

<h2 align="center"><img src="assets/h-about.svg" width="100%" alt="Who I Am" /></h2>

```ts
const abhiram = {
  name: "Abhiram V",
  role: "Full Stack Developer Intern @ Richinnovations",
  studying: "MCA in Cyber Security & AI (Amrita Vishwa Vidyapeetham)",
  building: "RoleGuard — RBAC & workspace collaboration platform",
  stack: ["TypeScript", "React", "Node.js", "Express", "PostgreSQL", "Redis"],
  security: ["Burp Suite", "Nmap", "Gobuster", "Metasploit", "OWASP Top 10"],
  goal: "HTB Certified Penetration Testing Specialist (CPTS)",
  approach: "Build it properly, then attack it to see if it holds.",
  motto: "Always learning. Always building. Always securing.",
} as const;
```

<p align="center">
  I'm an aspiring <b>Application Security Engineer</b>. Working as a developer teaches me how applications are put together, so when I switch to the attacker's seat, I already know where the weak spots hide: <b>APIs, authentication, and access control</b>.
</p>

<table width="100%" border="0" align="center">
<tr>
<td width="33%" align="center" style="padding: 14px;">
  <h4>💼 Now</h4>
  <p><b>Richinnovations</b><br /><sub>Full Stack Developer Intern<br />Jun 2026 – Present</sub></p>
</td>
<td width="33%" align="center" style="padding: 14px;">
  <h4>🎓 Studying</h4>
  <p><b>MCA · Cyber Security</b><br /><sub>Amrita Vishwa Vidyapeetham<br />Starting Oct 2026</sub></p>
</td>
<td width="33%" align="center" style="padding: 14px;">
  <h4>🎯 Next Milestone</h4>
  <p><b>HTB CPTS</b><br /><sub>Hack The Box<br />Penetration Testing Specialist</sub></p>
</td>
</tr>
</table>

<p align="center"><img src="assets/divider.svg" width="100%" alt="" /></p>

<h2 align="center"><img src="assets/h-project.svg" width="100%" alt="RoleGuard" /></h2>

<p align="center">
  <i>A role-based access control and workspace collaboration platform, built during my internship at Richinnovations.<br />
  Authentication, workspaces, background jobs, real-time presence, payments, and admin monitoring in one system.</i>
</p>

<p align="center">
  <a href="https://github.com/iamabhiram-v/role-guard-authentication-system"><img src="https://img.shields.io/badge/Source%20Code-💻%20View-8b5cf6?style=for-the-badge&logo=github&logoColor=white&labelColor=0b0b1e" alt="Source Code" /></a>
</p>

<p align="center">
  <img src="assets/stats.svg" width="100%" alt="RoleGuard by the numbers: 15 database tables, 3 OAuth providers, 3 background job types, 62 pages of documentation" />
</p>

<table width="100%" border="0" align="center">
<tr>
<td width="33%" valign="top" style="padding: 12px;">
  <h4>🔑 Authentication</h4>
  <sub>
  JWT access + refresh tokens in <b>httpOnly cookies</b><br />
  Optional email-OTP two-factor login<br />
  bcrypt hashing, Zod validation<br />
  Google, GitHub &amp; Microsoft OAuth
  </sub>
</td>
<td width="33%" valign="top" style="padding: 12px;">
  <h4>🛡️ Access Control</h4>
  <sub>
  Platform roles: Admin / User<br />
  Workspace roles: Owner / Admin / Member<br />
  Middleware + service-layer enforcement<br />
  Rate-limited auth &amp; account endpoints
  </sub>
</td>
<td width="33%" valign="top" style="padding: 12px;">
  <h4>👥 Workspaces</h4>
  <sub>
  Email invitations with accept / decline<br />
  Role changes &amp; ownership transfer<br />
  Leave and delete flows<br />
  Live presence &amp; typing indicators
  </sub>
</td>
</tr>
<tr>
<td width="33%" valign="top" style="padding: 12px;">
  <h4>⚙️ Background Jobs</h4>
  <sub>
  BullMQ on Redis: email, SMS, notifications<br />
  Exponential-backoff retries<br />
  Hold / release, pause / resume<br />
  Admin queue monitor
  </sub>
</td>
<td width="33%" valign="top" style="padding: 12px;">
  <h4>🔔 Notifications</h4>
  <sub>
  Real-time in-app notification center<br />
  Per-category preferences &amp; mute windows<br />
  Web push subscriptions<br />
  Admin announcements
  </sub>
</td>
<td width="33%" valign="top" style="padding: 12px;">
  <h4>📊 Admin &amp; Ops</h4>
  <sub>
  Analytics with CSV / JSON / PDF export<br />
  Service status dashboard<br />
  Liveness &amp; readiness health checks<br />
  Winston logging, PostgreSQL backups
  </sub>
</td>
</tr>
</table>

<h3 align="center">🏗️ Architecture</h3>

<p align="center">
  <img src="assets/architecture.svg" width="100%" alt="RoleGuard architecture: browser, Nginx, Express API with Socket.IO, PostgreSQL, Redis with a BullMQ worker, and external services" />
</p>

<h3 align="center">🔄 Login Flow (optional 2FA)</h3>

```mermaid
%%{init: {'theme': 'base', 'themeVariables': {'primaryColor': '#12122b', 'primaryTextColor': '#ffffff', 'primaryBorderColor': '#e11d9a', 'lineColor': '#22d3ee', 'actorBkg': '#12122b', 'actorBorder': '#e11d9a', 'actorTextColor': '#ffffff', 'signalColor': '#22d3ee', 'signalTextColor': '#ffffff', 'noteBkgColor': '#4c1d95', 'noteTextColor': '#ffffff'}}}%%
sequenceDiagram
    autonumber
    participant C as Client
    participant A as Express API
    participant D as PostgreSQL

    C->>A: POST /api/auth/login
    A->>D: Verify credentials
    alt 2FA disabled
        A-->>C: Set httpOnly cookies (access + refresh)
    else 2FA enabled
        A-->>C: requiresOtp true (OTP sent by email)
        C->>A: POST /api/auth/verify-otp
        A-->>C: Set httpOnly cookies (access + refresh)
    end
    Note over C,A: Later requests carry the accessToken cookie automatically
    C->>A: POST /api/auth/refresh (when the access token expires)
    A-->>C: New accessToken cookie
```

<details>
<summary><b>📚 &nbsp;Full documentation package (click to expand)</b></summary>
<br />

I documented RoleGuard end to end in a 62-page package covering:

| Section | Covers |
|---|---|
| 🏛️ **System Architecture** | Components, data flows, security architecture, scalability notes |
| 🗄️ **Database Design** | ER diagram, all 15 tables, cascade and indexing strategy |
| 🔌 **API Documentation** | REST + Socket.IO reference, status codes, rate limits |
| 🚢 **Deployment Guide** | Environment setup, Docker builds, health checks, rollback, backup and restore |
| 📖 **User Manual** | Roles, workspaces, notifications, admin tools |

</details>

<p align="center"><img src="assets/divider.svg" width="100%" alt="" /></p>

<h2 align="center"><img src="assets/h-security.svg" width="100%" alt="Security" /></h2>

<p align="center">
  <img src="assets/terminal-security.svg" width="100%" alt="Animated terminal showing nmap, gobuster, Burp Suite and John the Ripper used in an authorized lab" />
</p>

<table width="100%" border="0" align="center">
<tr>
<td width="50%" valign="top" style="padding: 12px;">
  <h4>🕷️ Web &amp; API Security</h4>
  <sub>
  OWASP Top 10 &amp; web application security<br />
  API security<br />
  SQL injection &amp; Cross-Site Scripting (XSS)<br />
  Authentication &amp; authorization testing
  </sub>
</td>
<td width="50%" valign="top" style="padding: 12px;">
  <h4>🧰 Tooling &amp; Labs</h4>
  <sub>
  Kali Linux, Burp Suite, Gobuster, Nmap<br />
  Metasploit &amp; John the Ripper<br />
  Active Directory attacks, Kerberoasting, BloodHound<br />
  Practised in labs and on my own apps
  </sub>
</td>
</tr>
</table>

<p align="center">
  <img src="assets/marquee-security.svg" width="100%" alt="Burp Suite, Nmap, Gobuster, Metasploit, John the Ripper, BloodHound, Kali Linux, OWASP Top 10, SQL injection, XSS, Active Directory, Kerberoasting, HTB CPTS" />
</p>

<p align="center">
  <b>Goal:</b> Hack The Box <b>CPTS</b> (Certified Penetration Testing Specialist)<br />
  <sub>All testing is done in labs, on my own systems, or where I have explicit authorization.</sub>
</p>

<p align="center"><img src="assets/divider.svg" width="100%" alt="" /></p>

<h2 align="center"><img src="assets/h-stack.svg" width="100%" alt="Development Stack" /></h2>

<p align="center"><b>Languages</b></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=ts&theme=dark" alt="TypeScript" />
  &nbsp;
  <img src="https://img.shields.io/badge/SQL-0b0b1e?style=for-the-badge&logo=postgresql&logoColor=22d3ee" alt="SQL" />
</p>

<p align="center"><b>Frontend</b></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=react,redux,vite&theme=dark" alt="Frontend" />
  &nbsp;
  <img src="https://img.shields.io/badge/Axios-0b0b1e?style=for-the-badge&logo=axios&logoColor=8b5cf6" alt="Axios" />
</p>

<p align="center"><b>Backend &amp; Data</b></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=nodejs,express,postgres,redis&theme=dark" alt="Backend" />
  <br /><br />
  <img src="https://img.shields.io/badge/BullMQ-0b0b1e?style=for-the-badge&logoColor=e11d9a" alt="BullMQ" />
  <img src="https://img.shields.io/badge/Socket.IO-0b0b1e?style=for-the-badge&logo=socketdotio&logoColor=22d3ee" alt="Socket.IO" />
  <img src="https://img.shields.io/badge/JWT-0b0b1e?style=for-the-badge&logo=jsonwebtokens&logoColor=ff3355" alt="JWT" />
  <img src="https://img.shields.io/badge/Zod-0b0b1e?style=for-the-badge&logo=zod&logoColor=8b5cf6" alt="Zod" />
  <img src="https://img.shields.io/badge/node--cron-0b0b1e?style=for-the-badge&logoColor=e11d9a" alt="node-cron" />
  <img src="https://img.shields.io/badge/Winston-0b0b1e?style=for-the-badge&logoColor=22d3ee" alt="Winston" />
</p>

<p align="center"><b>Integrations</b></p>
<p align="center">
  <img src="https://img.shields.io/badge/Razorpay-0b0b1e?style=for-the-badge&logo=razorpay&logoColor=22d3ee" alt="Razorpay" />
  <img src="https://img.shields.io/badge/Twilio-0b0b1e?style=for-the-badge&logo=twilio&logoColor=ff3355" alt="Twilio" />
  <img src="https://img.shields.io/badge/Nodemailer-0b0b1e?style=for-the-badge&logo=gmail&logoColor=e11d9a" alt="Nodemailer" />
  <img src="https://img.shields.io/badge/Cloudflare_R2-0b0b1e?style=for-the-badge&logo=cloudflare&logoColor=8b5cf6" alt="Cloudflare R2" />
</p>

<p align="center"><b>Deployment</b></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=docker,nginx&theme=dark" alt="Deployment" />
</p>

<p align="center"><img src="assets/divider.svg" width="100%" alt="" /></p>

<h2 align="center"><img src="assets/h-journey.svg" width="100%" alt="Journey" /></h2>

<table width="100%" border="0" align="center">
<tr>
<td width="33%" align="center" style="padding: 14px;">
  <h4>2023 – 2026</h4>
  <p><b>BCA</b><br /><sub>University of Kerala<br />Thiruvananthapuram</sub></p>
</td>
<td width="33%" align="center" style="padding: 14px;">
  <h4>Jun 2026 → Now</h4>
  <p><b>Full Stack Developer Intern</b><br /><sub>Richinnovations<br />Technopark, Thiruvananthapuram (Remote)</sub></p>
</td>
<td width="33%" align="center" style="padding: 14px;">
  <h4>Oct 2026 →</h4>
  <p><b>MCA · Cyber Security &amp; AI</b><br /><sub>Amrita Vishwa Vidyapeetham</sub></p>
</td>
</tr>
</table>

<p align="center"><img src="assets/divider.svg" width="100%" alt="" /></p>

<h2 align="center"><img src="assets/h-principles.svg" width="100%" alt="How I Work" /></h2>

<p align="center">
  <b>Correctness</b> → <b>Security</b> → <b>Reliability</b> → <b>Maintainability</b> → <b>Testability</b> → <b>Performance</b> → <b>Simplicity</b>
</p>

<p align="center">
  <i>Understand before changing. Verify before claiming. Prefer the simplest production-safe solution.</i>
</p>

<p align="center"><img src="assets/divider.svg" width="100%" alt="" /></p>

<h2 align="center"><img src="assets/h-activity.svg" width="100%" alt="GitHub Activity" /></h2>

<p align="center">
  <img src="https://github-readme-stats-fast.vercel.app/api?username=iamabhiram-v&show_icons=true&bg_color=0b0b1e&title_color=ff3355&text_color=e5e7eb&icon_color=8b5cf6&border_color=4c1d95&border_radius=12" width="440" alt="GitHub Stats" />
  &nbsp;&nbsp;
  <img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=iamabhiram-v&layout=compact&bg_color=0b0b1e&title_color=ff3355&text_color=e5e7eb&border_color=4c1d95&border_radius=12" width="350" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=iamabhiram-v&theme=dark&background=0b0b1e&ring=e11d9a&fire=ff3355&currStreakLabel=22d3ee&sideLabels=22d3ee&currStreakNum=ffffff&sideNums=ffffff&dates=9ca3af&border=4c1d95&stroke=4c1d95" width="500" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/iamabhiram-v/iamabhiram-v/output/github-snake-dark.svg" width="100%" alt="Contribution snake animation" />
</p>

<p align="center"><img src="assets/divider.svg" width="100%" alt="" /></p>

<h2 align="center"><img src="assets/h-connect.svg" width="100%" alt="Let's Connect" /></h2>

<p align="center">
  <i>Open to conversations about application security, web &amp; API testing, and building things properly.</i>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/abhiram-v-297188364/"><img src="https://img.shields.io/badge/LinkedIn-Abhiram_V-e11d9a?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0b0b1e" alt="LinkedIn" /></a>
  &nbsp;
  <a href="https://github.com/iamabhiram-v"><img src="https://img.shields.io/badge/GitHub-iamabhiram--v-22d3ee?style=for-the-badge&logo=github&logoColor=white&labelColor=0b0b1e" alt="GitHub" /></a>
</p>

<p align="center">
  <img src="assets/footer.svg" width="100%" alt="Always learning. Always building. Always securing." />
</p>
