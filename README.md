
<div align="center">

  <img src="./assets/profile-banner.svg" width="100%" alt="Suhas Krishna Shetti — Software Engineering, Backend Systems, Applied AI" />

  <br/><br/>

  <a href="https://github.com/suhasshetti02">
    <img src="https://komarev.com/ghpvc/?username=suhasshetti02&style=for-the-badge&color=123B65&label=PROFILE+VIEWS" alt="Profile views"/>
  </a>
  <a href="https://www.linkedin.com/in/suhas-shetti-7b43a7327/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://leetcode.com/u/suhasshetti02/">
    <img src="https://img.shields.io/badge/LeetCode-300%2B_Problems-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/>
  </a>
  <a href="mailto:suhasks.cs24@rvce.edu.in">
    <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>

</div>

---

## 01 — ABOUT ME
<sub>WHO I AM · WHAT I BUILD · WHAT I EXPLORE</sub>

I'm **Suhas Krishna Shetti**, a Computer Science and Engineering student at **R.V. College of Engineering, Bengaluru**.

I enjoy building software beyond conventional CRUD applications — from backend services and distributed workflows to cryptography and document-grounded AI applications.

**Current interests:** Software engineering, backend architecture, distributed systems, applied AI, and problem solving.

**Open to:** Software Engineering and Backend Engineering opportunities.

---

## 02 — TECHNICAL TOOLKIT
<sub>LANGUAGES · FRAMEWORKS · INFRASTRUCTURE</sub>

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=c,cpp,python,go,java,js,ts&perline=7" alt="C, C++, Python, Go, Java, JavaScript and TypeScript"/>

**Backend & Frontend**

<img src="https://skillicons.dev/icons?i=nodejs,express,django,fastapi,flask,react,nextjs&perline=7" alt="Node.js, Express, Django, FastAPI, Flask, React and Next.js"/>

**Data & Infrastructure**

<img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,firebase,docker,kubernetes,linux&perline=7" alt="PostgreSQL, MongoDB, Redis, Firebase, Docker, Kubernetes and Linux"/>

**AI / ML & Tools**

<img src="https://skillicons.dev/icons?i=tensorflow,sklearn,git,github,vscode,postman&perline=6" alt="TensorFlow, scikit-learn, Git, GitHub, VS Code and Postman"/>

</div>

<details>
<summary><strong>Technology details</strong></summary>

| Area | Technologies |
|---|---|
| Languages | C, C++, Python, Go, Java, JavaScript, TypeScript |
| Backend | Node.js, Express, Django REST, FastAPI, Flask |
| Frontend | React, Next.js, React Native, Tailwind CSS |
| Databases | PostgreSQL, Supabase, MongoDB, Firebase, Redis |
| Distributed Systems | RabbitMQ, TCP/IP, Microservices, Event-Driven Architecture |
| Cloud & DevOps | Docker, Kubernetes, AWS, Linux |
| AI / ML | TensorFlow, scikit-learn, Hugging Face, RAG, NLP |
| Security | RSA, AES-GCM, JWT, PBKDF2 |

</details>

---

## 03 — SELECTED PROJECTS
<sub>SYSTEMS BUILT · IDEAS IMPLEMENTED · PROBLEMS SOLVED</sub>

A selection of systems and prototypes I've been building across backend engineering, distributed computing, security, and applied AI.

### 01. Distributed PQC Storage

<a href="https://github.com/suhasshetti02/Distributed-pqc-storage">
  <img src="./assets/projects/pqc-storage.svg" width="100%" alt="Distributed PQC Storage project banner"/>
</a>

A Go-based distributed-storage prototype exploring peer-to-peer file transfer, cryptographic key establishment, and data recovery.

- Custom TCP peer communication and local storage nodes.
- Kyber-768-based key establishment with AES-GCM encryption.
- SHA-256 content addressing and Reed-Solomon erasure-coding components.
- SQLite metadata with shard audit and recovery workflows.

**Stack:** Go · TCP/IP · Kyber-768 · AES-GCM · Reed-Solomon · SQLite

[View repository →](https://github.com/suhasshetti02/Distributed-pqc-storage)

---

### 02. Distributed Media Processing Pipeline

<a href="https://github.com/suhasshetti02/Distributed-media-pipeline">
  <img src="./assets/projects/media-pipeline.svg" width="100%" alt="Distributed Media Pipeline project banner"/>
</a>

An event-driven microservices prototype for asynchronous video-to-audio processing.

- Four services: Authentication, Gateway, Converter, and Notification.
- RabbitMQ decouples upload requests from background conversion jobs.
- MongoDB GridFS stores source media and generated audio.
- JWT-based gateway authentication and message acknowledgements.

**Stack:** Python · Flask · RabbitMQ · MongoDB GridFS · Docker · Kubernetes

[View repository →](https://github.com/suhasshetti02/Distributed-media-pipeline)

---

### 03. ContextDrop — Document-Grounded AI

<a href="https://github.com/suhasshetti02/ContextDrop">
  <img src="./assets/projects/contextdrop.svg" width="100%" alt="ContextDrop project banner"/>
</a>

A document intelligence platform that turns uploaded documents and web content into contextual question-answering experiences.

- Document ingestion, text extraction, and structure-aware chunking.
- Embeddings and PostgreSQL pgvector similarity search for retrieval.
- Separate Django REST and Node.js/Express services.
- Server-Sent Events (SSE) for streaming responses.
- Redis-backed rate limiting and HMAC-based internal service authentication.

**Stack:** Python · Django REST · Node.js · PostgreSQL · pgvector · Redis

[View repository →](https://github.com/suhasshetti02/ContextDrop)

---

### 04. Aegis-Gate — Context-Aware Access Control

<a href="https://github.com/suhasshetti02/Agis-gate">
  <img src="./assets/projects/aegis-gate.svg" width="100%" alt="Aegis-Gate project banner"/>
</a>

A context-aware authentication and network-access simulation prototype that evaluates user credentials, device identity, and access risk.

- PBKDF2-based password handling, device fingerprinting, and email OTP.
- RSA-PSS challenge-response with one-time nonce validation.
- Rule-based risk scoring and per-user Isolation Forest anomaly detection when enough history is available.
- Simulated IP allocation and role-based VLAN assignment.

**Stack:** Python · Flask · RSA-PSS · PBKDF2 · Isolation Forest · SQLite

[View repository →](https://github.com/suhasshetti02/Agis-gate)

---

### 05. GreenChain — Food Redistribution Platform

<a href="https://github.com/suhasshetti02/greenchain-platform">
  <img src="./assets/projects/greenchain.svg" width="100%" alt="GreenChain project banner"/>
</a>

A full-stack platform connecting food donors with NGOs and receivers through donation and claim-management workflows.

- Donation discovery, creation, and claim-management flows.
- Supabase PostgreSQL and Storage for application data and media.
- Separate FastAPI machine-learning service for spoilage-risk estimation.
- Gemini-assisted food-safety guidance with fallback logic.
- JWT-based authentication and messaging integrations.

**Stack:** Next.js · Node.js · Express · Supabase PostgreSQL · FastAPI · Gemini

[View repository →](https://github.com/suhasshetti02/greenchain-platform)

---

### 06. Cross-Language Code Clone Detector

<a href="https://github.com/suhasshetti02/cross-lang-code-detector">
  <img src="./assets/projects/code-clone-detector.svg" width="100%" alt="Cross-Language Code Clone Detector project banner"/>
</a>

A compiler-oriented prototype exploring structural similarity between programs written in C, C++, Rust, and Fortran.

- Compiler pipelines that can generate LLVM Intermediate Representation (IR).
- Control Flow Graph (CFG) and Data Flow Graph (DFG) construction.
- Weisfeiler-Lehman graph hashing and structural program features.
- Pairwise and multi-file comparison interface.

**Stack:** Python · FastAPI · LLVM IR · NetworkX · React

[View repository →](https://github.com/suhasshetti02/cross-lang-code-detector)

---

<details>
<summary><strong>More projects & experiments</strong></summary>

| Project | Focus | Repository |
|---|---|---|
| Plant Pulse | Random Forest crop recommendation and CNN-based plant-disease classification | [Source](https://github.com/suhasshetti02/Plant-Pulse) |
| TruthLab | Multimodal fake-news analysis using MuRIL, Vision Transformer, and cross-modal learning | [Source](https://github.com/suhasshetti02/explainable-multimodal-fakenews-detection) |
| SolarShare | IoT-based energy-sharing prototype using React Native, Firebase, and ESP32 | [Source](https://github.com/suhasshetti02/solarshare-app) |
| Flight Route Optimization | Route algorithms and interactive weather-aware visualisation | [Source](https://github.com/suhasshetti02/Fligh_Route_Optimization_System) |
| Bio-Mat Web | Biodegradable-material catalogue using React, Express, and MongoDB | [Source](https://github.com/suhasshetti02/bio-mat-web) |

</details>

---

## 04 — ENGINEERING APPROACH
<sub>HOW I DESIGN · BUILD · INTEGRATE · DELIVER</sub>

I focus on understanding how software components fit together — from data structures and protocols to service boundaries, retrieval pipelines, testing, and deployment.

<div align="center">

<img src="https://img.shields.io/badge/DESIGN-System_Architecture-123B65?style=flat-square" alt="System architecture"/>
<img src="https://img.shields.io/badge/BUILD-Backend_%26_Services-087E8B?style=flat-square" alt="Backend and services"/>
<img src="https://img.shields.io/badge/INTEGRATE-AI_%26_Data-5965A8?style=flat-square" alt="AI and data"/>
<img src="https://img.shields.io/badge/SHIP-Test_%26_Deploy-287A55?style=flat-square" alt="Test and deploy"/>

</div>

---

## 05 — DATA STRUCTURES & ALGORITHMS
<sub>PROBLEM SOLVING · ALGORITHMIC THINKING · CORE CS</sub>

<div align="center">

<a href="https://leetcode.com/u/suhasshetti02/">
  <img src="https://img.shields.io/badge/LeetCode-300%2B_Problems_Solved-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="300 plus problems solved"/>
</a>

</div>

I practise problem solving to strengthen algorithmic thinking and core computer-science fundamentals.

**Topics:** Arrays · Strings · Hashing · Two Pointers · Sliding Window · Binary Search · Trees · Graphs · Greedy · Dynamic Programming · Backtracking

[Visit my LeetCode profile →](https://leetcode.com/u/suhasshetti02/)

---

## 06 — GITHUB CONTRIBUTIONS
<sub>OPEN-SOURCE WORK · CONSISTENCY · CONTRIBUTION HISTORY</sub>

<div align="center">

  <h3>👾 Contribution Maze</h3>

  <picture>
    <source
      media="(prefers-color-scheme: dark)"
      srcset="https://raw.githubusercontent.com/suhasshetti02/suhasshetti02/output/pacman-contribution-graph-dark.svg"
    />
    <source
      media="(prefers-color-scheme: light)"
      srcset="https://raw.githubusercontent.com/suhasshetti02/suhasshetti02/output/pacman-contribution-graph.svg"
    />
    <img
      src="https://raw.githubusercontent.com/suhasshetti02/suhasshetti02/output/pacman-contribution-graph.svg"
      alt="Pacman contribution graph"
      width="100%"
    />
  </picture>

  <br/><br/>

  <a href="https://github.com/suhasshetti02?tab=repositories">
    <img src="https://img.shields.io/badge/Explore-My_Repositories-123B65?style=for-the-badge&logo=github&logoColor=white" alt="Explore repositories"/>
  </a>

</div>

---

## 07 — LET'S CONNECT
<sub>COLLABORATION · IDEAS · ENGINEERING OPPORTUNITIES</sub>

<div align="center">

**Interested in building useful software and solving challenging engineering problems.**

<a href="https://github.com/suhasshetti02">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>
<a href="https://www.linkedin.com/in/suhas-shetti-7b43a7327/">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="mailto:suhasks.cs24@rvce.edu.in">
  <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>
<a href="https://leetcode.com/u/suhasshetti02/">
  <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/>
</a>

<br/><br/>

<sub>Designed with a focus on clarity, systems thinking, and continuous learning.</sub>

</div>
