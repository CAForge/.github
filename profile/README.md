<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=32&pause=1500&color=6E7681&center=true&vCenter=true&width=560&lines=CAForge" alt="CAForge" />

<br/>

<sub>Building production-grade AI systems, distributed platforms, and modern software.</sub>

<br/><br/>

We build software the way it's meant to be built — designed deliberately, engineered for production, and documented so anyone can pick it up.

<br/>

[![Repositories](https://img.shields.io/badge/Repositories-141414?style=for-the-badge&logo=github&logoColor=white)](https://github.com/orgs/CAForge/repositories)
[![Projects](https://img.shields.io/badge/Projects-141414?style=for-the-badge&logo=vercel&logoColor=white)](#featured-projects)
[![Documentation](https://img.shields.io/badge/Documentation-141414?style=for-the-badge&logo=readthedocs&logoColor=white)](#development-standards)

</div>

<br/>

---

<br/>

## About

**CAForge** is a small engineering organization designing modern software with production-quality engineering practices. Every project is treated as a real system, not a demo — built with the same discipline around architecture, reliability, and documentation regardless of scale.

Our focus areas:

<table>
<tr>
<td>

**Artificial Intelligence**
Applied ML and real-time computer vision

</td>
<td>

**Backend Engineering**
API and service design

</td>
<td>

**Distributed Systems**
Event streaming and multi-service architecture

</td>
</tr>
<tr>
<td>

**Cloud Infrastructure**
Containerized, cloud-deployed systems

</td>
<td>

**Developer Experience**
Documentation and tooling that reduce friction

</td>
<td>

**Full-Stack Engineering**
End-to-end products, data to interface

</td>
</tr>
</table>

<br/>

---

<br/>

## Engineering Philosophy

<table>
<tr><td width="50%">

**Build for production**
Code is written to hold up under real conditions, not just to demo well.

</td><td width="50%">

**Design before implementation**
Architecture decisions are made deliberately, before the first line of code.

</td></tr>
<tr><td width="50%">

**Performance by default**
Latency and resource usage are measured, not assumed.

</td><td width="50%">

**Readable software**
Code is written for the next engineer reading it, not just the compiler.

</td></tr>
<tr><td width="50%">

**Scalable architecture**
Clear service boundaries so components can evolve independently.

</td><td width="50%">

**Reliable infrastructure**
Systems are containerized and deployed the same way every time.

</td></tr>
<tr><td width="50%">

**Automation over repetition**
Linting, testing, and builds run in CI — not by hand, before every push.

</td><td width="50%">

**Documentation as code**
READMEs and architecture docs are maintained alongside the code they describe.

</td></tr>
</table>

<br/>

---

<br/>

## Technology Stack

<div align="center">

**Languages**
![Python](https://img.shields.io/badge/Python-14151A?style=flat-square&logo=python&logoColor=3776AB)
![C++](https://img.shields.io/badge/C%2B%2B-14151A?style=flat-square&logo=cplusplus&logoColor=00599C)
![TypeScript](https://img.shields.io/badge/TypeScript-14151A?style=flat-square&logo=typescript&logoColor=3178C6)
![JavaScript](https://img.shields.io/badge/JavaScript-14151A?style=flat-square&logo=javascript&logoColor=F7DF1E)
![SQL](https://img.shields.io/badge/SQL-14151A?style=flat-square&logo=postgresql&logoColor=4169E1)

**Backend**
![FastAPI](https://img.shields.io/badge/FastAPI-14151A?style=flat-square&logo=fastapi&logoColor=009688)
![Node.js](https://img.shields.io/badge/Node.js-14151A?style=flat-square&logo=nodedotjs&logoColor=339933)
![Kafka](https://img.shields.io/badge/Kafka-14151A?style=flat-square&logo=apachekafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-14151A?style=flat-square&logo=redis&logoColor=DC382D)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-14151A?style=flat-square&logo=postgresql&logoColor=4169E1)

**Frontend**
![React](https://img.shields.io/badge/React-14151A?style=flat-square&logo=react&logoColor=61DAFB)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-14151A?style=flat-square&logo=tailwindcss&logoColor=06B6D4)
![Three.js](https://img.shields.io/badge/Three.js-14151A?style=flat-square&logo=threedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-14151A?style=flat-square&logo=typescript&logoColor=3178C6)

**AI**
![TensorFlow.js](https://img.shields.io/badge/TensorFlow.js-14151A?style=flat-square&logo=tensorflow&logoColor=FF6F00)
![MediaPipe](https://img.shields.io/badge/MediaPipe-14151A?style=flat-square&logo=google&logoColor=4285F4)
![OpenCV](https://img.shields.io/badge/OpenCV-14151A?style=flat-square&logo=opencv&logoColor=5C3EE8)
![Gemini API](https://img.shields.io/badge/Gemini_API-14151A?style=flat-square&logo=googlegemini&logoColor=8E75B2)

**Cloud**
![AWS](https://img.shields.io/badge/AWS-14151A?style=flat-square&logo=amazonaws&logoColor=FF9900)
![Docker](https://img.shields.io/badge/Docker-14151A?style=flat-square&logo=docker&logoColor=2496ED)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-14151A?style=flat-square&logo=githubactions&logoColor=2088FF)
![Linux](https://img.shields.io/badge/Linux-14151A?style=flat-square&logo=linux&logoColor=FCC624)

</div>

<br/>

---

<br/>

## Featured Projects

<br/>

**[FleetFlow](https://github.com/CAForge/FleetFlow)** · [Live](http://13.53.163.137/)
Real-time telemetry platform simulating connected vehicles over an event-driven streaming architecture.
- Kafka-based ingestion decoupling simulation from processing
- Redis caching layer with PostgreSQL for persistence
- Multi-service design: simulator, processing, and API layers
- Containerized and deployed on AWS EC2

`FastAPI` `Kafka` `Redis` `PostgreSQL` `Docker` `AWS`

<br/>

**[Neuro-Drive](https://github.com/CAForge/neuro-driver)** · [Demo](https://youtu.be/NpORRi-yiKY)
Real-time AI driver monitoring platform for fatigue and distraction detection.
- MediaPipe Face Mesh with EAR/MAR based fatigue analysis
- Gaze tracking and head-pose deviation estimation
- Per-user calibration for cross-condition robustness
- Live alerting via Server-Sent Events

`Python` `OpenCV` `MediaPipe` `FastAPI` `SSE`

<br/>

**[Echo-Vision](https://github.com/CAForge/Echo-Vision)** · [Live](https://echo-vision-seven.vercel.app/)
Browser-based assistive vision platform for accessibility.
- On-device object detection across 80+ classes
- Directional and distance-aware spatial guidance
- Gemini-powered scene narration with voice output

`React` `TypeScript` `TensorFlow.js` `Face-API.js` `Gemini API`

<br/>

**[Shadow-Sim](https://github.com/CAForge/shadow-sim)** · [Live](https://shadow-sim.vercel.app/)
Vehicle digital twin with real-time telemetry synchronization.
- Kinematic bicycle model physics engine
- WebSocket telemetry at 20Hz with dead-reckoning prediction
- Statistical outlier filtering for data integrity

`FastAPI` `WebSockets` `Three.js`

<br/>

**[HR-Dashboard](https://github.com/CAForge/HR_DASHBOARD)** · [Live](https://hr-dashboard-five-dusky.vercel.app/)
Modern HR management platform with AI-assisted workflows.
- Employee and project tracking
- Modular, service-based frontend architecture
- Gemini API integration for AI-assisted features

`React` `TypeScript` `Vite` `Node.js`

<br/>

---

<br/>

## Software Architecture

**Engineering workflow**

```mermaid
flowchart LR
    A[Idea] --> B[Research]
    B --> C[Architecture]
    C --> D[Development]
    D --> E[Testing]
    E --> F[Deployment]
    F --> G[Monitoring]
    G --> H[Iteration]
    H --> B
```

**System layout**

```mermaid
flowchart TD
    A[Frontend] --> B[API Layer]
    B --> C[Business Logic]
    C --> D[Database]
    C --> E[Cloud Infrastructure]
```

<br/>

---

<br/>

## Development Standards

Every repository in this organization follows the same baseline:

- Containerization for consistent local and production environments
- Clear, maintained documentation
- Conventional Commits for a readable history
- CI/CD on every pull request
- Mandatory code review before merge
- Test coverage for core logic
- Clean, layered architecture
- Semantic versioning for releases
- API documentation where applicable
- Issue tracking for planned work
- A meaningful README — not a placeholder

<br/>

---

<br/>

## Team

<table>
<tr>
<td width="50%">

**Chitransh Sahrawat**
AI Engineering · Computer Vision · Backend · Distributed Systems
[github.com/chitranshsahrawat](https://github.com/chitranshsahrawat)

</td>
<td width="50%">

**Aditya Tiwari**
Full-Stack Engineering · Frontend · Backend · System Design
[github.com/Adityatiwari86](https://github.com/Adityatiwari86)

</td>
</tr>
</table>

<br/>

---

<br/>

## Current Focus

`Distributed Systems` `AI Infrastructure` `Cloud-Native Applications` `Developer Tools` `Computer Vision` `Production-Grade APIs`

<br/>

---

<br/>

## Future Direction

CAForge is building toward a growing set of scalable, production-grade systems — spanning distributed infrastructure, real-time applications, and applied AI. Each new project is an opportunity to raise the engineering bar set by the last one, with the long-term goal of open-sourcing work that reflects genuine software craftsmanship rather than one-off builds.

<br/>

---

<br/>

<div align="center">

**CAForge**
Engineering software with clarity, scalability, and purpose.

</div>
