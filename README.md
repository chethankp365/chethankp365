<div align="center">

<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/banner.svg" alt="Chethan Kumar KP — AI, computer vision, cybersecurity and backend" width="100%"/>

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-34d399?style=for-the-badge&logo=vercel&logoColor=0a0e0c&labelColor=0a0e0c)](https://chethankumar-portfolio.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-34d399?style=for-the-badge&logo=linkedin&logoColor=34d399&labelColor=0a0e0c)](https://www.linkedin.com/in/chethan-kumar-kp17/)
[![Email](https://img.shields.io/badge/Email-chethankp365%40gmail.com-34d399?style=for-the-badge&logo=gmail&logoColor=34d399&labelColor=0a0e0c)](mailto:chethankp365@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-View-34d399?style=for-the-badge&logo=googledrive&logoColor=34d399&labelColor=0a0e0c)](https://drive.google.com/file/d/1ql_ltsz6ATxShFthLh8isdJ55G_tSCTB/view?usp=sharing)
[![YouTube](https://img.shields.io/badge/YouTube-Channel-34d399?style=for-the-badge&logo=youtube&logoColor=34d399&labelColor=0a0e0c)](https://www.youtube.com/@CHETHANKUMARKP-v6w)
[![Instagram](https://img.shields.io/badge/Instagram-chethankumarkp__-34d399?style=for-the-badge&logo=instagram&logoColor=34d399&labelColor=0a0e0c)](https://www.instagram.com/chethankumarkp_/)

</div>

<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/film.svg" width="100%" alt="Now showing: a scrolling film strip of eight projects"/>

<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/divider.svg" width="100%" alt=""/>

<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/h-about.svg" width="100%" alt="About"/>

<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/about.svg" width="100%" alt="Focus: AI and computer vision, speech AI, backend, security. Currently: Cyber Security Intern at Cynaris Solutions. Education: B.E. CSE and Design Engineering, Atria IT"/>

<br/>

I'm a final-year Computer Science & Design Engineering student in Bengaluru. I build AI-powered platforms, full-stack applications and IoT systems across **computer vision, speech AI, backend engineering, optimization and cybersecurity**, with a focus on real-world problems: workforce and farm access, railway safety, disaster response, aviation safety and cyber defense.

I'm currently a **Cyber Security Intern at Cynaris Solutions**, working on a Kali Linux lab, OWASP Top 10 assessments, controlled exploitation, digital forensics and CVSS-rated penetration testing reports, while building **NO ENTRY**, an AI-powered cyber range.

<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/divider.svg" width="100%" alt=""/>

<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/h-highlights.svg" width="100%" alt="Highlights"/>

<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/metrics.svg" width="100%" alt="8 projects, 5 AI services, 80 lab rooms, 168 tests passing, ~2s detection, Top 4 SIH internal"/>

<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/divider.svg" width="100%" alt=""/>

<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/h-projects.svg" width="100%" alt="Projects"/>

Each project includes an animated architecture flow. Where a concept needs more explanation, expand the **Technical notes** section underneath it.

<br/>

<!-- ============ 01 NO ENTRY ============ -->
<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/flow-noentry.svg" width="100%" alt="NO ENTRY architecture flow"/>

### NO ENTRY — AI-Powered Cybersecurity Training Platform & Isolated Cyber Range
An 80-room training platform across four tracks (Red Team, Blue Team, Purple Team, Detection Engineering). Learners run **real commands inside live Docker containers** rather than simulated terminals. All 20 Red Team rooms are implemented (reconnaissance, SQL injection, XSS, command injection, privilege escalation and more), supported by **GHOST**, a multi-provider AI mentor, and validated by **168 passing automated tests**.

`Python` `FastAPI` `Docker` `SQLModel` `PostgreSQL` `WebSockets` `JavaScript` `YAML` `MITRE ATT&CK`

[![Source](https://img.shields.io/badge/Source-NO--ENTRY-34d399?style=flat-square&logo=github&logoColor=34d399&labelColor=0a0e0c)](https://github.com/chethankp365/NO-ENTRY) [![Live demo](https://img.shields.io/badge/Live%20demo-no--entry.onrender.com-22d3ee?style=flat-square&labelColor=0a0e0c)](https://no-entry.onrender.com/)

<details>
<summary><b>Technical notes: how a lab session works</b></summary>

```mermaid
sequenceDiagram
    autonumber
    participant L as Learner
    participant A as FastAPI Core
    participant D as Docker Cyber Range
    participant T as Vulnerable Target
    participant G as GHOST AI Mentor
    L->>A: Start room
    A->>D: Spin up disposable attacker + target
    D-->>L: Live terminal over WebSocket
    L->>T: nmap, sqlmap, exploit...
    T-->>L: Real output
    L->>A: Submit flag
    A-->>L: Validate, award XP, unlock next room
    L->>G: Request a hint
    G-->>L: Contextual guidance without spoilers
```
</details>

<br/>

<!-- ============ 02 UDYOGASETHU ============ -->
<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/flow-udyogasethu.svg" width="100%" alt="UdyogaSethu architecture flow"/>

### UdyogaSethu — Multilingual Workforce & Farm Marketplace
A voice-first mobile platform connecting informal workers and small farmers with customers through **GPS-based service matching** and farm-to-consumer commerce. It integrates **five AI services** (Deepgram, Groq, Gemini, OpenRouter, Hugging Face) and applies a **six-safeguard trust and safety layer**: identity and QR job verification, face/liveness checks, live GPS tracking, one-tap SOS and secure chat, enforced with PostgreSQL Row Level Security. Includes a Spring Boot + Vaadin admin portal and three Figma-prototyped user journeys.

`Flutter` `Supabase` `PostGIS` `RLS` `Edge Functions` `Spring Boot` `Vaadin` `Deepgram` `Groq` `Gemini`

[![Source](https://img.shields.io/badge/Source-UdyogaSethu%20(app%20%2B%20admin)-34d399?style=flat-square&logo=github&logoColor=34d399&labelColor=0a0e0c)](https://github.com/chethankp365/UdyogaSethu) [![Mobile APK](https://img.shields.io/badge/Mobile%20APK-Download-22d3ee?style=flat-square&labelColor=0a0e0c)](https://drive.google.com/file/d/1f6fvaAMZZhQ-E97YEeMnLMw5GF81H0Qy/view) [![Admin portal](https://img.shields.io/badge/Admin%20portal-Live-22d3ee?style=flat-square&labelColor=0a0e0c)](https://udyogasethu-admin.onrender.com/)

<details>
<summary><b>Technical notes: the trust layer</b></summary>

```mermaid
flowchart LR
    U([Worker / Farmer / Customer]) --> V{Identity<br/>verified?}
    V -- yes --> Q[QR job<br/>verification]
    Q --> F[Face + liveness<br/>check]
    F --> M[GPS match<br/>via PostGIS]
    M --> J[Job in progress]
    J --> T[Live GPS tracking]
    J --> S[One-tap SOS]
    J --> C[Secure chat]
    T --> R[(Row Level Security<br/>guards every read and write)]
    S --> R
    C --> R
    V -- no --> X[Access blocked]
```
</details>

<br/>

<!-- ============ 03 SAFECOMM ============ -->
<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/flow-safecomm.svg" width="100%" alt="SafeComm architecture flow"/>

### SafeComm — Real-Time Aviation Speech AI
Transcribes ATC radio, extracts flight instructions and detects **incorrect pilot read-backs within about 2 seconds**, with a sub-5 ms local regex fallback. Alerts are cross-checked against live ADS-B and ATIS data using confidence-aware scoring, and the monitoring dashboard includes error-injection testing.

`React` `TypeScript` `Python` `Whisper` `FastAPI` `Supabase` `Gemini` `Groq`

[![Source](https://img.shields.io/badge/Source-SafeComm-34d399?style=flat-square&logo=github&logoColor=34d399&labelColor=0a0e0c)](https://github.com/chethankp365/SafeComm) [![Live demo](https://img.shields.io/badge/Live%20demo-safecomm.vercel.app-22d3ee?style=flat-square&labelColor=0a0e0c)](https://safecomm.vercel.app/)

<details>
<summary><b>Technical notes: what is a read-back and why does it matter?</b></summary>

A controller issues an instruction and the pilot must read it back. An unnoticed mismatch (wrong altitude, wrong runway) is a classic root cause of aviation incidents. SafeComm acts as an independent safety net that listens for those mismatches.

```mermaid
sequenceDiagram
    participant ATC as Controller
    participant P as Pilot
    participant S as SafeComm
    participant X as ADS-B / ATIS
    ATC->>P: "Climb and maintain FL240"
    P->>ATC: "Climb FL220"
    ATC-->>S: audio stream
    P-->>S: audio stream
    S->>S: Whisper transcribes both sides
    S->>S: Extract instruction vs read-back
    S->>X: Cross-check live aircraft + airport data
    S-->>ATC: Alert: read-back mismatch (~2s)
```
</details>

<br/>

<!-- ============ 04 SATQUERY ============ -->
<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/flow-satquery.svg" width="100%" alt="SatQuery AI architecture flow"/>

### SatQuery AI — Satellite Vision-Language Assistant
Ask questions about satellite imagery in plain language. An agentic assistant (Gemini 2.5 VLM) routes each query to **YOLOv8 detection, SSIM/CVA change detection, NDVI/NDWI/NBR indices and SAR–optical fusion**, then returns evidence-grounded insights and change maps through a COG/GeoJSON pipeline with a MongoDB audit trail. **Top 4, Smart India Hackathon Internal (Software Edition).**

`React` `TypeScript` `Python` `Gemini 2.5` `YOLOv8` `GDAL / GeoTIFF` `MongoDB`

[![Source](https://img.shields.io/badge/Source-SatQuery--AI-34d399?style=flat-square&logo=github&logoColor=34d399&labelColor=0a0e0c)](https://github.com/chethankp365/SatQuery-AI) [![Live demo](https://img.shields.io/badge/Live%20demo-sat--query--ai-22d3ee?style=flat-square&labelColor=0a0e0c)](https://sat-query-ai-murex.vercel.app/)

<br/>

<!-- ============ 05 CAMPUS CONNECT ============ -->
<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/flow-campusconnect.svg" width="100%" alt="Campus Connect architecture flow"/>

### Campus Connect — Full-Stack Campus Communication Platform
Built during my Full Stack Web Development internship (Rotaract Club of Atria I.T. × Dept. of CSE) on the MERN stack. Ranked in the **Top 8 of 60+ projects** in the cohort.

`MongoDB` `Express.js` `React` `Node.js`

[![Source](https://img.shields.io/badge/Source-CampusConnect-34d399?style=flat-square&logo=github&logoColor=34d399&labelColor=0a0e0c)](https://github.com/chethankp365/CampusConnect) [![Live demo](https://img.shields.io/badge/Live%20demo-campus--connect-22d3ee?style=flat-square&labelColor=0a0e0c)](https://campus-connect-beta-weld.vercel.app/)

<br/>

<!-- ============ 06 AAHAT ============ -->
<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/flow-aahat.svg" width="100%" alt="Aahat architecture flow"/>

### Aahat — AI Predictive Railway Safety & Defect Digital Twin
A multi-sensor system that "listens" to the track. It fuses **acoustic, vibration, vision and GPS** data, confirms a defect only when **two or more sensors agree**, pins it on a **digital twin**, scores severity and **forecasts when it becomes critical**. The prototype runs on simulated data; real-track validation is on the roadmap.

`Raspberry Pi 4` `Python` `TensorFlow Lite` `React`

[![Source](https://img.shields.io/badge/Source-Aahat-34d399?style=flat-square&logo=github&logoColor=34d399&labelColor=0a0e0c)](https://github.com/chethankp365/Aahat) [![Live demo](https://img.shields.io/badge/Live%20demo-aahat.vercel.app-22d3ee?style=flat-square&labelColor=0a0e0c)](https://aahat.vercel.app/)

<details>
<summary><b>Technical notes: the multi-sensor agreement rule</b></summary>

A single noisy sensor should not trigger a false alarm. Aahat raises a defect only when independent sensors corroborate each other, which reduces false positives.

```mermaid
flowchart LR
    A[Acoustic] --> E{2 or more<br/>sensors agree?}
    B[Vibration] --> E
    C[Vision] --> E
    D[GPS position] --> E
    E -- no --> I[Treat as noise]
    E -- yes --> T[Pin defect on<br/>Digital Twin]
    T --> S[Severity score]
    S --> F[Forecast:<br/>time to critical]
    F --> R[Maintenance alert]
```
</details>

<br/>

<!-- ============ 07 RAKSHAAN ============ -->
<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/flow-rakshaan.svg" width="100%" alt="Rakshaan architecture flow"/>

### Rakshaan — AI-Powered Autonomous Disaster-Response Drone
An autonomous search-and-rescue drone that uses **RGB and thermal vision** to detect survivors and hazards while navigating difficult terrain, and sends survivor locations, hazards and risk information to rescue teams in real time. Built for SIH 2026.

`TypeScript` `RGB + Thermal Vision` `Autonomous Navigation`

[![Source](https://img.shields.io/badge/Source-Rakshaan-34d399?style=flat-square&logo=github&logoColor=34d399&labelColor=0a0e0c)](https://github.com/chethankp365/Rakshaan)

<br/>

<!-- ============ 08 ECOBRAIN ============ -->
<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/flow-ecobrain.svg" width="100%" alt="EcoBrain flow"/>

### EcoBrain
A live demo is available. A full write-up is coming soon.

[![Source](https://img.shields.io/badge/Source-EcoBrain--AI-34d399?style=flat-square&logo=github&logoColor=34d399&labelColor=0a0e0c)](https://github.com/chethankp365/EcoBrain-AI) [![Live demo](https://img.shields.io/badge/Live%20demo-eco--brain--ai-22d3ee?style=flat-square&labelColor=0a0e0c)](https://eco-brain-ai.vercel.app/)

<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/divider.svg" width="100%" alt=""/>

<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/h-skills.svg" width="100%" alt="Skills"/>

<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/skills.svg" width="100%" alt="Skills: cybersecurity, AI and ML, languages, web and backend, data, tools and optimization"/>

<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/divider.svg" width="100%" alt=""/>

<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/h-experience.svg" width="100%" alt="Experience"/>

<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/journey.svg" width="100%" alt="Timeline: B.E. 2023, Full Stack Intern 2025, UI/UX Intern 2026, Cyber Security Intern Nov 2026 to present, Graduation 2027"/>

**Cyber Security Intern** · Cynaris Solutions Pvt. Ltd. · *Nov 2026 – Present*
Personal Kali Linux lab with vulnerable VMs; network reconnaissance and vulnerability scans; OWASP Top 10 assessments; controlled exploitation and privilege escalation; digital forensics on disk images and memory dumps; CVSS-rated penetration testing reports with remediation guidance.

**Virtual UI/UX Design Intern** · CodSoft · *Jun 2026 – Jul 2026*
User flows, wireframes and interactive prototypes in Figma, refined against usability.

**Full Stack Web Development Intern** · Rotaract Club of Atria I.T. × Dept. of CSE · *Mar 2025 – Jun 2025*
Built Campus Connect on the MERN stack; ranked Top 8 of 60+ projects.

<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/divider.svg" width="100%" alt=""/>

<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/h-process.svg" width="100%" alt="Process"/>

<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/build-loop.svg" width="100%" alt="Build loop: understand, research, prototype, test and harden, ship, iterate"/>

<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/divider.svg" width="100%" alt=""/>

<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/h-activity.svg" width="100%" alt="GitHub activity"/>

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=chethankp365&show_icons=true&hide_border=true&bg_color=0a0e0c&title_color=34d399&icon_color=22d3ee&text_color=e7efe9&ring_color=34d399&count_private=true" alt="GitHub stats"/>
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=chethankp365&layout=compact&hide_border=true&bg_color=0a0e0c&title_color=34d399&text_color=e7efe9" alt="Top languages"/>

<img src="https://streak-stats.demolab.com?user=chethankp365&background=0A0E0C&ring=34D399&fire=22D3EE&currStreakLabel=34D399&sideLabels=E7EFE9&currStreakNum=E7EFE9&sideNums=E7EFE9&dates=8A9A91&border=1F2B25" alt="Streak stats" width="100%"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=chethankp365&bg_color=0a0e0c&color=34d399&line=34d399&point=22d3ee&area=true&area_color=34d399&hide_border=true&custom_title=Contribution%20Activity" alt="Contribution graph" width="100%"/>

<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/output/github-snake-dark.svg" alt="Contribution snake" width="100%"/>

</div>

<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/divider.svg" width="100%" alt=""/>

<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/h-certs.svg" width="100%" alt="Certifications"/>

| Certification | Issued by |
|---|---|
| Ethical Hacker | Cisco Networking Academy |
| Artificial Intelligence Fundamentals | IBM SkillsBuild |
| Apply API Testing & Automation with Postman | EDUCBA, Coursera |
| Unmanned Aerial Systems: Operations | University of Alaska Fairbanks, Coursera |
| Java Spring Boot Backend Development | Coursera |
| Programming in C · Programming Using Java | Infosys Springboard |

<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/divider.svg" width="100%" alt=""/>

<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/h-contact.svg" width="100%" alt="Contact"/>

I'm open to internships, collaborations and conversations about AI, computer vision, cybersecurity, backend engineering and optimization. The best ways to reach me are [email](mailto:chethankp365@gmail.com) and [LinkedIn](https://www.linkedin.com/in/chethan-kumar-kp17/). You can also visit my [portfolio](https://chethankumar-portfolio.vercel.app/) or view my [resume](https://drive.google.com/file/d/1ql_ltsz6ATxShFthLh8isdJ55G_tSCTB/view?usp=sharing).

<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/main/readme-kit%20(3)/assets/footer.svg" width="100%" alt="More projects in progress"/>
