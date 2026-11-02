# Hi there 👋, I'm Alessandro Seghini 

### 👨‍💻 About Me

* 🎓 **Background:** M.Sc. in Artificial Intelligence Engineering from **Universität Passau** and B.Sc. in Computer Science from **Università Politecnica delle Marche**.
* 🛠️ **Engineering Mindset:** Strong advocate for clean architecture, Domain-Driven Design (DDD), static typing, and automated testing. I prefer deterministic code, strict schemas, and zero-ORM overhead over fragile layers.
* 🔭 **Current Focus:** Developing **[Strata](https://github.com/AlessandroS01/Strata)**—an air-gapped, offline hybrid RAG knowledge engine built with Python, SQLite WAL, and local vector reranking.
* 🏎️ **Leadership:** Former Software Engineering Team Lead for the **Polimarche Racing Team**, architecting telemetry backends for 50+ engineers.
* 💬 **Ask Me About:** Python backend design, high-frequency telemetry ingestion, streaming data reliability, local RAG architectures, and Spring Boot testing patterns.

---

### 🧰 Tech Stack & Tooling

<table>
  <tr>
    <td align="center" width="25%"><strong>Languages</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
      <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
      <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
      <img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white" alt="Dart" />
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
      <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" alt="Kotlin" />
    </td>
  </tr>
  <tr>
    <td align="center"><strong>Backend & APIs</strong></td>
    <td>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
      <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white" alt="Spring Boot" />
      <img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white" alt="Pydantic" />
      <img src="https://img.shields.io/badge/RESTful_APIs-005571?style=flat-square" alt="RESTful APIs" />
      <img src="https://img.shields.io/badge/Domain--Driven_Design-4A154B?style=flat-square" alt="DDD" />
    </td>
  </tr>
  <tr>
    <td align="center"><strong>Data & Storage</strong></td>
    <td>
      <img src="https://img.shields.io/badge/SQLite_(WAL)-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite WAL" />
      <img src="https://img.shields.io/badge/Qdrant-DC2626?style=flat-square&logo=qdrant&logoColor=white" alt="Qdrant" />
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL" />
      <img src="https://img.shields.io/badge/H2_Database-1B5E20?style=flat-square" alt="H2" />
      <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black" alt="Firebase" />
      <img src="https://img.shields.io/badge/Streaming_Telemetry-FF6F00?style=flat-square" alt="Streaming" />
    </td>
  </tr>
  <tr>
    <td align="center"><strong>AI & Retrieval</strong></td>
    <td>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
      <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain" />
      <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" alt="Ollama" />
      <img src="https://img.shields.io/badge/Hybrid_RAG_(RRF_+_BM25)-6A1B9A?style=flat-square" alt="Hybrid RAG" />
      <img src="https://img.shields.io/badge/LLM_Benchmarking-37474F?style=flat-square" alt="LLM Evaluation" />
    </td>
  </tr>
  <tr>
    <td align="center"><strong>Tooling & Quality</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
      <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white" alt="CI/CD" />
      <img src="https://img.shields.io/badge/JUnit5-25A162?style=flat-square&logo=junit5&logoColor=white" alt="JUnit5" />
      <img src="https://img.shields.io/badge/Mockito-C53030?style=flat-square" alt="Mockito" />
      <img src="https://img.shields.io/badge/Mypy-2F4F4F?style=flat-square" alt="Mypy" />
      <img src="https://img.shields.io/badge/Ruff-D7FF64?style=flat-square&logoColor=black" alt="Ruff" />
    </td>
  </tr>
</table>

---

### 🚀 Highlighted Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🔍 <a href="https://github.com/AlessandroS01/Strata">Strata</a></h3>
      <p><em>Air-gapped, offline hybrid RAG engine and local personal knowledge base.</em></p>
      <ul>
        <li>Architected via <strong>Domain-Driven Design</strong> and SQLite in WAL mode, delivering sub-5ms local reads without ORM overhead.</li>
        <li>Implemented an <strong>AST-aware Markdown chunker</strong> generating Small-to-Big relationships with SHA-256 caching to skip duplicate vector embedding steps.</li>
        <li>Dual-channel retrieval: dense vector search (Qdrant) + sparse lexical search (BM25) fused via <strong>Reciprocal Rank Fusion (RRF)</strong> and cross-encoder reranking.</li>
      </ul>
      <p><code>Python</code> • <code>SQLite (WAL)</code> • <code>Qdrant</code> • <code>FastEmbed</code> • <code>rank_bm25</code> • <code>Mypy</code></p>
    </td>
    <td width="50%" valign="top">
      <h3>📈 <a href="https://github.com/AlessandroS01/Callisia-WearLM">Callisia-WearLM</a></h3>
      <p><em>High-integrity multi-modal telemetry pipeline & automated LLM auditing suite.</em></p>
      <ul>
        <li>Engineered end-to-end Python pipeline processing streaming <strong>100 Hz PPG/ACC data</strong> into structured clinical payloads.</li>
        <li>Resolved Bluetooth jitter with a 40 Hz interpolation protocol, yielding 100% deterministic reliability across validation runs.</li>
        <li>Created a scalable <strong>LLM-as-a-Judge</strong> evaluation framework assessing model decision boundary stability, safety, and latency.</li>
      </ul>
      <p><code>Python</code> • <code>Pydantic</code> • <code>LangChain</code> • <code>PyTorch</code> • <code>Ollama</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🏎️ <a href="https://github.com/AlessandroS01/thesis-polimarche">Polimarche Racing Telemetry</a></h3>
      <p><em>Scalable telemetry management platform for a Formula SAE team of 50+ members.</em></p>
      <ul>
        <li>Designed a modular <strong>Spring Boot REST backend</strong> applying Service-Repository patterns and Role-Based Access Control (RBAC).</li>
        <li>Guaranteed regression stability through comprehensive unit and integration suites using <strong>JUnit5, Mockito, and H2</strong>.</li>
        <li>Shipped a cross-platform Flutter client centralizing dynamic vehicle setup configurations and test runs.</li>
      </ul>
      <p><code>Java</code> • <code>Spring Boot</code> • <code>JUnit5</code> • <code>Flutter</code> • <code>Dart</code> • <code>Firebase</code></p>
    </td>
    <td width="50%" valign="top">
      <h3>🤖 <a href="https://github.com/AlessandroS01/PiCarX-AI-Vision-Co">Autonomous Vision Rover</a></h3>
      <p><em>Real-time edge control and computer vision system on Raspberry Pi 4.</em></p>
      <ul>
        <li>Built an autonomous closed-loop pipeline translating real-time computer vision metrics directly into motor commands.</li>
        <li>Trained and deployed edge vision models (YOLO) with noise/vibration augmentations, reaching <strong>0.992 mAP50</strong> for edge line and object tracking.</li>
      </ul>
      <p><code>Python</code> • <code>YOLO</code> • <code>Roboflow</code> • <code>Raspberry Pi 4</code> • <code>Computer Vision</code></p>
    </td>
  </tr>
</table>

---

### 📊 GitHub Activity & Metrics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=AlessandroS01&show_icons=true&locale=en&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AlessandroS01&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="150" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=AlessandroS01&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</div>

---

<div align="center">
  <h3>📬 Let's Connect & Collaborate</h3>
  <p>I am always open to discussing backend architectures, local AI retrieval systems, or software engineering opportunities.</p>

  <p>
    <a href="https://linkedin.com/in/alessandro-seghini"><img src="https://img.shields.io/badge/LinkedIn-Alessandro_Seghini-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="mailto:it_seghini@outlook.com"><img src="https://img.shields.io/badge/Outlook-it__seghini@outlook.com-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white" alt="Email" /></a>
    <a href="https://github.com/AlessandroS01"><img src="https://img.shields.io/badge/GitHub-AlessandroS01-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  </p>
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,11,21&height=100&section=footer" width="100%" alt="Footer Banner" />
