<div align="center">

<img src="./assets/banner.svg" alt="CHETHAN KUMAR KP — cinematic title card" width="100%"/>

<br/>

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-OPEN-39FF14?style=for-the-badge&logo=vercel&logoColor=black&labelColor=07040d)](https://chethankumar-portfolio.vercel.app/)
[![GitHub](https://img.shields.io/badge/GITHUB-chethankp365-39FF14?style=for-the-badge&logo=github&logoColor=black&labelColor=07040d)](https://github.com/chethankp365)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-CONNECT-FF1F2D?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=07040d)](https://www.linkedin.com/in/chethan-kumar-kp17/)
[![Email](https://img.shields.io/badge/EMAIL-chethankp365%40gmail.com-FF1F2D?style=for-the-badge&logo=gmail&logoColor=white&labelColor=07040d)](mailto:chethankp365@gmail.com)
[![YouTube](https://img.shields.io/badge/YOUTUBE-CHANNEL-9B4DFF?style=for-the-badge&logo=youtube&logoColor=white&labelColor=07040d)](https://www.youtube.com/@CHETHANKUMARKP-v6w)
[![Instagram](https://img.shields.io/badge/INSTAGRAM-chethankumarkp__-9B4DFF?style=for-the-badge&logo=instagram&logoColor=white&labelColor=07040d)](https://www.instagram.com/chethankumarkp_/)
[![Resume](https://img.shields.io/badge/RESUME-VIEW%20CV-FFD400?style=for-the-badge&logo=googledrive&logoColor=black&labelColor=07040d)](https://drive.google.com/file/d/1ql_ltsz6ATxShFthLh8isdJ55G_tSCTB/view?usp=sharing)

<img src="https://komarev.com/ghpvc/?username=chethankp365&style=for-the-badge&color=39FF14&label=AUDIENCE&labelColor=07040d" alt="profile views"/>

</div>

<img src="./assets/divider.svg" width="100%" alt=""/>

<img src="./assets/h-origin.svg" width="100%" alt="Chapter 00 — Origin Story"/>

<img src="./assets/intro.svg" width="100%" alt="Comic page: he builds things that see, listen and defend"/>

<img src="./assets/divider.svg" width="100%" alt=""/>

<img src="./assets/h-metrics.svg" width="100%" alt="Chapter 01 — Power Stats"/>

<img src="./assets/metrics.svg" width="100%" alt="8 projects, 5 AI services, 80 lab rooms, 168 tests passing, ~2s detection, Top 4 SIH internal"/>

<img src="./assets/divider.svg" width="100%" alt=""/>

<img src="./assets/h-projects.svg" width="100%" alt="Chapter 02 — The Missions"/>

> 🎬 **How to read this chapter:** every mission has a flow diagram. Follow the glowing packet left to right and wait for the sound effect at the end. Expand the **🧠 deep dive** under a mission to see how the theory works.

<br/>

<!-- ============ 01 NO ENTRY ============ -->
<img src="./assets/flow-noentry.svg" width="100%" alt="NO ENTRY flow"/>

### 🔴 ISSUE #01 · NO ENTRY — AI-Powered Cybersecurity Training Platform & Isolated Cyber Range
An **80-room training platform across 4 tracks** (Red, Blue, Purple, Detection Engineering). Learners run **real commands inside live Docker containers**, not fake terminal output. All **20 Red Team rooms** are built (recon, SQL injection, XSS, command injection, privilege escalation and more), guided by **GHOST**, a multi-provider AI mentor, and backed by **168 passing automated tests**.

`Python` `FastAPI` `Docker` `SQLModel` `PostgreSQL` `WebSockets` `JavaScript` `YAML` `MITRE ATT&CK`

[![Source](https://img.shields.io/badge/SOURCE-NO--ENTRY-FF1F2D?style=for-the-badge&logo=github&labelColor=07040d)](https://github.com/chethankp365/NO-ENTRY) [![Live](https://img.shields.io/badge/▶%20LIVE%20DEMO-no--entry.onrender.com-39FF14?style=for-the-badge&labelColor=07040d)](https://no-entry.onrender.com/)

<details>
<summary><b>🧠 Deep dive: how one lab session works</b></summary>

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
    L->>G: Stuck? Ask for a hint
    G-->>L: Contextual guidance, no spoilers
```
</details>

<br/>

<!-- ============ 02 UDYOGASETHU ============ -->
<img src="./assets/flow-udyogasethu.svg" width="100%" alt="UdyogaSethu flow"/>

### 🟢 ISSUE #02 · UdyogaSethu — Multilingual Workforce & Farm Marketplace
A **voice-first** mobile platform connecting informal workers and small farmers with customers through **GPS-based matching** and farm-to-consumer commerce. It orchestrates **5 AI services** (Deepgram, Groq, Gemini, OpenRouter, Hugging Face) and protects users with a **6-safeguard trust layer** (identity + QR job verification, face/liveness checks, live GPS tracking, one-tap SOS, secure chat) enforced by **PostgreSQL Row Level Security**. Ships with a **Spring Boot + Vaadin admin portal** and 3 Figma-prototyped user journeys.

`Flutter` `Supabase` `PostGIS` `RLS` `Edge Functions` `Spring Boot` `Vaadin` `Deepgram` `Groq` `Gemini`

[![Source](https://img.shields.io/badge/SOURCE-UDYOGASETHU%20(APP%20%2B%20ADMIN)-39FF14?style=for-the-badge&logo=github&logoColor=black&labelColor=07040d)](https://github.com/chethankp365/UdyogaSethu) [![APK](https://img.shields.io/badge/📱%20MOBILE%20APK-DOWNLOAD-FFD400?style=for-the-badge&labelColor=07040d)](https://drive.google.com/file/d/1f6fvaAMZZhQ-E97YEeMnLMw5GF81H0Qy/view) [![Admin](https://img.shields.io/badge/▶%20ADMIN%20PORTAL-LIVE-9B4DFF?style=for-the-badge&labelColor=07040d)](https://udyogasethu-admin.onrender.com/)

<details>
<summary><b>🧠 Deep dive: the trust layer</b></summary>

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
    V -- no --> X[Blocked]
```
</details>

<br/>

<!-- ============ 03 SAFECOMM ============ -->
<img src="./assets/flow-safecomm.svg" width="100%" alt="SafeComm flow"/>

### 🟣 ISSUE #03 · SafeComm — Real-Time Aviation Speech AI
Transcribes **ATC radio**, extracts flight instructions and catches **incorrect pilot read-backs within ~2 seconds**, with a **sub-5 ms local regex fallback**. Alerts are cross-checked against live **ADS-B and ATIS** data with confidence-aware scoring, and the monitoring dashboard ships with error-injection testing.

`React` `TypeScript` `Python` `Whisper` `FastAPI` `Supabase` `Gemini` `Groq`

[![Source](https://img.shields.io/badge/SOURCE-SAFECOMM-9B4DFF?style=for-the-badge&logo=github&labelColor=07040d)](https://github.com/chethankp365/SafeComm) [![Live](https://img.shields.io/badge/▶%20LIVE%20DEMO-safecomm.vercel.app-39FF14?style=for-the-badge&labelColor=07040d)](https://safecomm.vercel.app/)

<details>
<summary><b>🧠 Deep dive: what is a "read-back" and why does it matter?</b></summary>

A controller gives an instruction and the pilot must **read it back**. A wrong read-back that nobody catches (wrong altitude, wrong runway) is a classic root cause of incidents. SafeComm is the safety net that listens for those mismatches.

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
    S-->>ATC: ALERT: read-back mismatch (~2s)
```
</details>

<br/>

<!-- ============ 04 SATQUERY ============ -->
<img src="./assets/flow-satquery.svg" width="100%" alt="SatQuery AI flow"/>

### 🟡 ISSUE #04 · SatQuery AI — Satellite Vision-Language Assistant
Ask questions about satellite imagery in plain language. The **agentic assistant** (Gemini 2.5 VLM) routes each query to **YOLOv8 detection, SSIM/CVA change detection, NDVI/NDWI/NBR indices and SAR–optical fusion**, then answers with **evidence-grounded insights and change maps** through a COG/GeoJSON pipeline with a MongoDB audit trail. 🏆 **Top 4, Smart India Hackathon Internal (Software Edition).**

`React` `TypeScript` `Python` `Gemini 2.5` `YOLOv8` `GDAL / GeoTIFF` `MongoDB`

[![Source](https://img.shields.io/badge/SOURCE-SATQUERY--AI-FFD400?style=for-the-badge&logo=github&logoColor=black&labelColor=07040d)](https://github.com/chethankp365/SatQuery-AI) [![Live](https://img.shields.io/badge/▶%20LIVE%20DEMO-sat--query--ai-39FF14?style=for-the-badge&labelColor=07040d)](https://sat-query-ai-murex.vercel.app/)

<br/>

<!-- ============ 05 CAMPUS CONNECT ============ -->
<img src="./assets/flow-campusconnect.svg" width="100%" alt="Campus Connect flow"/>

### 🔴 ISSUE #05 · Campus Connect — Full-Stack Campus Communication Platform
Built during my **Full Stack Web Development internship** (Rotaract Club of Atria I.T. × Dept. of CSE) on the **MERN stack**. Ranked 🏅 **Top 8 of 60+ projects** in the cohort.

`MongoDB` `Express.js` `React` `Node.js`

[![Source](https://img.shields.io/badge/SOURCE-CAMPUSCONNECT-FF1F2D?style=for-the-badge&logo=github&labelColor=07040d)](https://github.com/chethankp365/CampusConnect) [![Live](https://img.shields.io/badge/▶%20LIVE%20DEMO-campus--connect-39FF14?style=for-the-badge&labelColor=07040d)](https://campus-connect-beta-weld.vercel.app/)

<br/>

<!-- ============ 06 AAHAT ============ -->
<img src="./assets/flow-aahat.svg" width="100%" alt="Aahat flow"/>

### 🟢 ISSUE #06 · Aahat — AI Predictive Railway Safety & Defect Digital Twin
A multi-sensor system that **listens to the track**. It fuses **acoustic, vibration, vision and GPS** data, confirms a defect **only when two or more sensors agree**, pins it on a **digital twin**, scores severity and **forecasts when it turns critical**. The prototype runs on simulated data; real-track validation is on the roadmap.

`Raspberry Pi 4` `Python` `TensorFlow Lite` `React`

[![Source](https://img.shields.io/badge/SOURCE-AAHAT-39FF14?style=for-the-badge&logo=github&logoColor=black&labelColor=07040d)](https://github.com/chethankp365/Aahat) [![Live](https://img.shields.io/badge/▶%20LIVE%20DEMO-aahat.vercel.app-FFD400?style=for-the-badge&labelColor=07040d)](https://aahat.vercel.app/)

<details>
<summary><b>🧠 Deep dive: the "2 sensors must agree" rule</b></summary>

One noisy sensor should never stop a train. Aahat raises a defect only when independent sensors **corroborate** each other, which cuts false alarms.

```mermaid
flowchart LR
    A[Acoustic] --> E{2 or more<br/>sensors agree?}
    B[Vibration] --> E
    C[Vision] --> E
    D[GPS position] --> E
    E -- no --> I[Ignore as noise]
    E -- yes --> T[Pin defect on<br/>Digital Twin]
    T --> S[Severity score]
    S --> F[Forecast:<br/>time to critical]
    F --> R[Maintenance alert]
```
</details>

<br/>

<!-- ============ 07 RAKSHAAN ============ -->
<img src="./assets/flow-rakshaan.svg" width="100%" alt="Rakshaan flow"/>

### 🟣 ISSUE #07 · Rakshaan — AI-Powered Autonomous Disaster-Response Drone
An autonomous search & rescue drone that uses **RGB + thermal vision** to detect survivors and hazards while navigating difficult terrain, then sends **survivor locations, hazards and risk information** to rescue teams in real time. Built for **SIH 2026**.

`TypeScript` `RGB + Thermal Vision` `Autonomous Navigation`

[![Source](https://img.shields.io/badge/SOURCE-RAKSHAAN-9B4DFF?style=for-the-badge&logo=github&labelColor=07040d)](https://github.com/chethankp365/Rakshaan)

<br/>

<!-- ============ 08 ECOBRAIN ============ -->
<img src="./assets/flow-ecobrain.svg" width="100%" alt="EcoBrain flow"/>

### 🟡 ISSUE #08 · EcoBrain
The live demo is online. The full origin story is coming soon.

[![Source](https://img.shields.io/badge/SOURCE-ECOBRAIN--AI-FFD400?style=for-the-badge&logo=github&logoColor=black&labelColor=07040d)](https://github.com/chethankp365/EcoBrain-AI) [![Live](https://img.shields.io/badge/▶%20LIVE%20DEMO-eco--brain--ai-39FF14?style=for-the-badge&labelColor=07040d)](https://eco-brain-ai.vercel.app/)

<img src="./assets/divider.svg" width="100%" alt=""/>

<img src="./assets/h-arsenal.svg" width="100%" alt="Chapter 03 — The Arsenal"/>

<img src="./assets/skills.svg" width="100%" alt="Skills: cybersecurity, AI/ML, languages, web and backend, data, tools and optimization"/>

<img src="./assets/divider.svg" width="100%" alt=""/>

<img src="./assets/h-journey.svg" width="100%" alt="Chapter 04 — Origin to Now"/>

<img src="./assets/journey.svg" width="100%" alt="Timeline: B.E. 2023, Full Stack Intern 2025, UI/UX Intern 2026, Cyber Security Intern Nov 2026 to now, Graduation 2027"/>

**🔴 Cyber Security Intern** · Cynaris Solutions Pvt. Ltd. · *Nov 2026 – Present*
Personal Kali Linux lab with vulnerable VMs, network recon and vuln scans, OWASP Top 10 assessments, controlled exploitation and privilege escalation, digital forensics on disk images and memory dumps, and CVSS-rated pentest reports with remediation guidance.

**🟡 Virtual UI/UX Design Intern** · CodSoft · *Jun 2026 – Jul 2026*
User flows, wireframes and interactive prototypes in Figma, refined against usability.

**🟣 Full Stack Web Development Intern** · Rotaract Club of Atria I.T. × Dept. of CSE · *Mar 2025 – Jun 2025*
Built **Campus Connect** on the MERN stack and ranked Top 8 of 60+ projects.

<img src="./assets/divider.svg" width="100%" alt=""/>

<img src="./assets/h-loop.svg" width="100%" alt="Chapter 05 — The Build Loop"/>

<img src="./assets/build-loop.svg" width="100%" alt="Build loop: understand, research, prototype, attack it, ship live, iterate"/>

<img src="./assets/divider.svg" width="100%" alt=""/>

<img src="./assets/h-stats.svg" width="100%" alt="Chapter 06 — Telemetry"/>

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=chethankp365&show_icons=true&hide_border=true&bg_color=07040d&title_color=39FF14&icon_color=FF1F2D&text_color=F7F7F2&ring_color=39FF14&count_private=true" alt="GitHub stats"/>
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=chethankp365&layout=compact&hide_border=true&bg_color=07040d&title_color=39FF14&text_color=F7F7F2" alt="Top languages"/>

<img src="https://streak-stats.demolab.com?user=chethankp365&background=07040D&ring=39FF14&fire=FF1F2D&currStreakLabel=39FF14&sideLabels=F7F7F2&currStreakNum=F7F7F2&sideNums=F7F7F2&dates=a49fba&border=39FF1455" alt="Streak stats" width="100%"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=chethankp365&bg_color=07040d&color=39FF14&line=39FF14&point=FF1F2D&area=true&area_color=39FF14&hide_border=true&custom_title=Contribution%20Pulse" alt="Contribution graph" width="100%"/>

<img src="https://raw.githubusercontent.com/chethankp365/chethankp365/output/github-snake-dark.svg" alt="Contribution snake" width="100%"/>

</div>

<img src="./assets/divider.svg" width="100%" alt=""/>

<img src="./assets/h-certs.svg" width="100%" alt="Chapter 07 — Training Montage"/>

| 🎖️ Certification | 🏛️ Issued by |
|---|---|
| Ethical Hacker | Cisco Networking Academy |
| Artificial Intelligence Fundamentals | IBM SkillsBuild |
| Apply API Testing & Automation with Postman | EDUCBA, Coursera |
| Unmanned Aerial Systems: Operations | University of Alaska Fairbanks, Coursera |
| Java Spring Boot Backend Development | Coursera |
| Programming in C · Programming Using Java | Infosys Springboard |

<img src="./assets/divider.svg" width="100%" alt=""/>

<img src="./assets/h-connect.svg" width="100%" alt="Final scene — Post-credits"/>

Stay for the post-credits scene: I'm open to **internships, collaborations and conversations** about AI, computer vision, cybersecurity, backend and optimization. The fastest way to reach me is [email](mailto:chethankp365@gmail.com) or [LinkedIn](https://www.linkedin.com/in/chethan-kumar-kp17/). You can also browse my [portfolio](https://chethankumar-portfolio.vercel.app/) or read my [resume](https://drive.google.com/file/d/1ql_ltsz6ATxShFthLh8isdJ55G_tSCTB/view?usp=sharing).

<img src="./assets/footer.svg" width="100%" alt="To be continued"/>
