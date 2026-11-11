
<div align="center">

  <!-- Animated Header -->
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1020,50:123B65,100:00C2FF&height=220&section=header&text=SUHAS%20KRISHNA%20SHETTI&fontSize=42&fontColor=FFFFFF&fontAlignY=38&desc=BACKEND%20%7C%20DISTRIBUTED%20SYSTEMS%20%7C%20GENAI&descSize=16&descAlignY=60&animation=fadeIn" alt="Suhas Krishna Shetti Header"/>

  <br/>

  <!-- Typing Animation -->
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=19&pause=1000&color=00C2FF&center=true&vCenter=true&width=700&lines=Building+Backend+%26+Distributed+Systems;Exploring+Post-Quantum+Cryptography;Developing+GenAI+%2F+RAG+Applications;Engineering+Practical+AI+Solutions;300%2B+DSA+Problems+Solved" alt="Typing Animation"/>
  </a>

  <br/><br/>

  <!-- Social Links -->
  <a href="https://github.com/suhasshetti02">
    <img src="https://komarev.com/ghpvc/?username=suhasshetti02&style=for-the-badge&color=0B8FAC&label=PROFILE+VIEWS" alt="Profile views"/>
  </a>
  <a href="https://www.linkedin.com/in/suhas-shetti-7b43a7327/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://leetcode.com/u/suhasshetti02/">
    <img src="https://img.shields.io/badge/LeetCode-300%2B-orange?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode"/>
  </a>
  <a href="mailto:suhasks.cs24@rvce.edu.in">
    <img src="https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>

</div>

<br/>

---

## 01 // ABOUT ME

<img align="right" width="290" src="https://github-readme-stats.vercel.app/api?username=suhasshetti02&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" alt="GitHub Statistics"/>

Hi! I'm **Suhas Krishna Shetti**, a Computer Science and Engineering student at **R.V. College of Engineering, Bengaluru**.

I enjoy building systems that go beyond conventional CRUD applications, particularly in backend engineering, distributed computing, cryptography, and applied AI.

My engineering interests include:

- ⚙️ Backend Engineering and Distributed Systems
- 🔐 Cryptography and Post-Quantum Security
- 🤖 Generative AI, RAG and Intelligent Applications
- 🧠 Data Structures, Algorithms and Problem Solving
- ☁️ Cloud Infrastructure and Microservices

**Currently focused on:** Building reliable backend systems, understanding distributed architectures, and developing practical AI-powered applications.

**Looking for:** Software Engineering, Backend Engineering, Distributed Systems and AI Engineering opportunities.

<br clear="right"/>

---

## 02 // TECHNOLOGY STACK

<div align="center">

  <h3>Languages & Development</h3>

  <img src="https://skillicons.dev/icons?i=cpp,c,python,go,java,js,ts,react,nodejs,express&perline=10" alt="Languages and development technologies"/>

  <h3>Backend, Databases & Infrastructure</h3>

  <img src="https://skillicons.dev/icons?i=django,fastapi,flask,postgres,mongodb,redis,firebase,docker,kubernetes,linux&perline=10" alt="Backend and infrastructure technologies"/>

  <h3>AI, ML & Developer Tools</h3>

  <img src="https://skillicons.dev/icons?i=tensorflow,sklearn,git,github,vscode,postman&perline=10" alt="AI and developer tools"/>

</div>

<details>
<summary><b>Detailed Technology Breakdown</b></summary>

| Category | Technologies |
|---|---|
| Languages | C++, C, Python, Go, Java, JavaScript, TypeScript |
| Backend | Node.js, Express.js, Django REST, FastAPI, Flask |
| Databases | PostgreSQL, Supabase, MongoDB, Firebase, Redis |
| Distributed Systems | RabbitMQ, TCP/IP, Microservices, Event-Driven Architecture |
| Cloud & DevOps | Docker, Kubernetes, AWS, Linux |
| AI / ML | TensorFlow, Scikit-learn, Hugging Face, RAG, NLP |
| Security | RSA, AES-GCM, JWT, PBKDF2, Cryptographic Protocols |
| Tools | Git, GitHub, Postman, VS Code |

</details>

---

## 03 // ENGINEERING APPROACH

I approach software development through system design, modularity, and measurable implementation.

```mermaid
flowchart TD
    A["Problem Understanding"] --> B["System Design & Architecture"]
    B --> C["Data Structures & Protocol Design"]
    C --> D["Backend & Distributed Services"]
    D --> E["AI / ML Integration"]
    E --> F["Testing & Evaluation"]
    F --> G["Containerization & Deployment"]

    classDef primary fill:#123B65,color:#ffffff,stroke:#00C2FF
    class A,B,C,D,E,F,G primary
```

My focus is not only implementing features, but also understanding how systems communicate, manage data, handle failures, and scale.

---

## 04 // FEATURED PROJECTS

### 🗄️ 1. Distributed PQC Storage System

<sub>Distributed Systems | Cryptography | Fault Tolerance</sub>

**Tech:** `Go` `TCP/IP` `Kyber-768` `AES-GCM` `Reed-Solomon` `SQLite`

A distributed storage prototype exploring secure peer-to-peer communication and data availability.

- Developed custom TCP-based peer communication and file-storage components.
- Integrated Kyber-768-based key establishment and AES-GCM encryption.
- Implemented SHA-256 content addressing and Reed-Solomon erasure-coding components.
- Built SQLite-backed metadata management and shard audit/recovery workflows.

**Engineering focus:** Peer communication, cryptographic key establishment, data integrity, and recovery mechanisms.

🔗 [View Repository](https://github.com/suhasshetti02/Distributed-pqc-storage)

---

### 🎬 2. Distributed Media Processing Pipeline

<sub>Microservices | Event-Driven Architecture | Asynchronous Processing</sub>

**Tech:** `Python` `Flask` `RabbitMQ` `MongoDB GridFS` `Docker` `Kubernetes`

An asynchronous video-to-audio processing system built around independent microservices.

- Designed four services: Authentication, Gateway, Converter, and Notification.
- Used RabbitMQ to decouple upload requests from background conversion jobs.
- Integrated MongoDB GridFS for video and generated audio storage.
- Implemented JWT-based authentication and manual message acknowledgements.

**Engineering focus:** Service communication, message queues, asynchronous workloads, and media processing.

🔗 [View Repository](https://github.com/suhasshetti02/Distributed-media-pipeline)

---

### 📄 3. ContextDrop — Document-Grounded AI Platform

<sub>Generative AI | Retrieval-Augmented Generation | Backend Engineering</sub>

**Tech:** `Python` `Django REST` `Node.js` `PostgreSQL` `pgvector` `Redis`

A document intelligence platform that transforms uploaded documents and web content into shareable question-answering experiences.

- Implemented document ingestion, text extraction, and structure-aware chunking.
- Integrated embeddings and PostgreSQL pgvector similarity search for contextual retrieval.
- Developed independent Django REST and Node.js/Express services.
- Implemented Server-Sent Events (SSE) for streaming AI responses.
- Added Redis-backed rate limiting and HMAC-based internal service authentication.

**Engineering focus:** RAG pipelines, vector search, inter-service communication, and grounded AI responses.

🔗 [View Repository](https://github.com/suhasshetti02/ContextDrop)

---

### 🔐 4. Aegis-Gate — Context-Aware Network Access Control

<sub>Cybersecurity | Cryptography | Adaptive Authentication</sub>

**Tech:** `Python` `Flask` `RSA-2048` `PBKDF2` `Isolation Forest` `SQLite`

A context-aware authentication prototype that evaluates both user credentials and device trust.

- Implemented password authentication using PBKDF2-SHA256.
- Integrated device fingerprinting, trusted-device registration, and email OTP verification.
- Developed RSA-PSS challenge-response authentication and one-time nonce validation.
- Combined rule-based risk assessment with per-user Isolation Forest anomaly detection.
- Implemented simulated IP allocation and role-based VLAN assignment.

**Engineering focus:** Authentication protocols, device trust, risk evaluation, and access-control simulation.

🔗 [View Repository](https://github.com/suhasshetti02/Agis-gate)

---

### 🌱 5. GreenChain — Food Redistribution Platform

<sub>Full-Stack Engineering | Applied AI | Cloud Applications</sub>

**Tech:** `Next.js` `Node.js` `Express` `Supabase PostgreSQL` `FastAPI` `Gemini`

A food redistribution platform connecting donors with NGOs and receivers through donation and claiming workflows.

- Developed donation creation, discovery, and claim-management workflows.
- Integrated Supabase PostgreSQL and Storage for application data and images.
- Built a separate FastAPI machine-learning service for spoilage-risk / priority estimation.
- Integrated Gemini-assisted food-safety guidance with rule-based fallback logic.
- Implemented JWT-based authentication and messaging integrations.

**Engineering focus:** Full-stack development, REST APIs, database design, and ML service integration.

🔗 [View Repository](https://github.com/suhasshetti02/greenchain-platform)

---

### 🧬 6. Cross-Language Semantic Code Clone Detector

<sub>Compiler Design | Program Analysis | Graph Algorithms</sub>

**Tech:** `Python` `FastAPI` `LLVM IR` `NetworkX` `React`

A compiler-oriented prototype exploring structural and semantic similarity between programs written in different programming languages.

- Integrated compiler pipelines for C, C++, Rust, and Fortran.
- Generated and analysed LLVM Intermediate Representation (IR).
- Constructed Control Flow Graphs (CFG) and Data Flow Graphs (DFG).
- Applied Weisfeiler-Lehman graph hashing and Structural Program Representation (SPR).
- Developed a comparison dashboard for pairwise and multi-file analysis.

**Engineering focus:** Compiler pipelines, graph-based program analysis, and similarity detection.

🔗 [View Repository](https://github.com/suhasshetti02/cross-lang-code-detector)

---

<details>
<summary><b>🌾 Other Projects & Experiments</b></summary>

| Project | Description | Repository |
|---|---|---|
| Plant Pulse | Crop recommendation using Random Forest and plant-disease classification using CNNs. | [GitHub](https://github.com/suhasshetti02/Plant-Pulse) |
| TruthLab | Multimodal fake-news analysis using MuRIL, Vision Transformer, and evidence-assisted AI workflows. | [GitHub](https://github.com/suhasshetti02/explainable-multimodal-fakenews-detection) |
| SolarShare | IoT-based energy sharing prototype using React Native, Firebase and ESP32. | [GitHub](https://github.com/suhasshetti02/solarshare-app) |
| Flight Route Optimization | Interactive graph algorithms and weather-aware flight-route visualisation. | [GitHub](https://github.com/suhasshetti02/Fligh_Route_Optimization_System) |
| Bio-Mat Web | Searchable biodegradable-material catalogue using React, Express and MongoDB. | [GitHub](https://github.com/suhasshetti02/bio-mat-web) |

</details>

---

## 05 // DATA STRUCTURES & ALGORITHMS

<div align="center">

  <a href="https://leetcode.com/u/suhasshetti02/">
    <img width="500" src="https://leetcard.jacoblin.cool/suhasshetti02?theme=dark&font=Fira%20Code&ext=heatmap" alt="LeetCode Statistics"/>
  </a>

  <br/>

  <img src="https://img.shields.io/badge/300%2B-Problems%20Solved-00C2FF?style=for-the-badge&logo=leetcode&logoColor=white" alt="300 plus problems solved"/>

</div>

**Core topics:**

- Arrays, Strings, Hashing and Two Pointers
- Sliding Window and Binary Search
- Trees, BST and Graph Algorithms
- BFS, DFS and Dijkstra's Algorithm
- Greedy Algorithms and Dynamic Programming
- Backtracking and Advanced Data Structures

**Practice platforms:** LeetCode · GeeksforGeeks · CodeStudio

🔗 [LeetCode Profile](https://leetcode.com/u/suhasshetti02/)

---

## 06 // GITHUB ACTIVITY

<div align="center">

  <!-- Contribution Graph -->
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=suhasshetti02&bg_color=0d1117&color=00c2ff&line=00c2ff&point=ffffff&area=true&hide_border=true" alt="GitHub Contribution Graph"/>

  <br/><br/>

  <!-- GitHub Streak -->
  <img height="165" src="https://streak-stats.demolab.com?user=suhasshetti02&theme=tokyonight&hide_border=true" alt="GitHub Streak"/>

  <br/><br/>

  <!-- Top Languages -->
  <img width="350" src="https://github-readme-stats.vercel.app/api/top-langs/?username=suhasshetti02&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages"/>

  <br/><br/>

  <!-- Trophies -->
  <img width="100%" src="https://github-profile-trophy.vercel.app/?username=suhasshetti02&theme=algolia&no-frame=true&no-bg=true&margin-w=8&row=1" alt="GitHub Trophies"/>

</div>

---

## 07 // CONNECT WITH ME

<div align="center">

  <h3>Let's build something meaningful!</h3>

  I'm always interested in discussing backend engineering, distributed systems, cryptography, and practical AI applications.

  <br/><br/>

  <a href="https://github.com/suhasshetti02">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://www.linkedin.com/in/suhas-shetti-7b43a7327/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:suhasks.cs24@rvce.edu.in">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>

  <br/><br/>

  **Open to Software Engineering Opportunities**

  <br/>

  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:00C2FF,50:123B65,100:0B1020&height=120&section=footer" alt="Footer"/>

</div>
