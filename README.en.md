<div align="center">
  <img width="100%" src="assets/profile-header.svg" alt="akirakawashi profile banner"/>
</div>

<h1 align="center">Alexander Ozhereliev</h1>

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&pause=1000&color=8B5CF6&center=true&vCenter=true&width=620&lines=AI+Engineer+%26+Fullstack+Developer;Technical+Team+Leadership;LLM+%2F+VLM+%26+Speech+Analytics;Creator+of+AiNoCraft" alt="Typing SVG" />
</div>

<div align="center">
  <a href="https://github.com/akirakawashi">
    <img src="https://img.shields.io/badge/GitHub-akirakawashi-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://t.me/akirakawashi">
    <img src="https://img.shields.io/badge/Telegram-akirakawashi-0088CC?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"/>
  </a>
  <a href="mailto:akirakawashi@yandex.ru"><img src="https://img.shields.io/badge/Email-6366F1?style=for-the-badge" alt="Email"/></a>
  <a href="https://akirakawashi.github.io/my-profile/"><img src="https://img.shields.io/badge/Resume-6366F1?style=for-the-badge" alt="Resume"/></a>
</div>

<p align="center"><a href="README.md">Русский</a> · <strong>English</strong></p>

<table>
  <tr>
    <td width="25%" align="center"><h3>3 years</h3><sub>Commercial development</sub></td>
    <td width="25%" align="center"><h3>2 developers</h3><sub>Technical team leadership</sub></td>
    <td width="25%" align="center"><h3>3 AI products</h3><sub>Delivered to production</sub></td>
    <td width="25%" align="center"><h3>4 months</h3><sub>Serving as Team Lead</sub></td>
  </tr>
</table>

## About Me

I build AI services and web applications: speech recognition and analysis, computer vision, document processing, and LLM/VLM integrations. Develop Python/FastAPI backends and React/Next.js frontends.

At IC8, I combine technical leadership with development: coordinate two developers, plan and allocate tasks, design architecture, and conduct code reviews. I continue writing code alongside the team.

**Career path:** working in IT since 2020 — Windows Server and Linux → technical support → backend → AI engineering and technical leadership. Joined IC8 in October 2022.

---

## Work Projects · IC8

**Within my first 4 months of technical leadership, my team and I delivered three AI products to production.** My contribution combines architecture, development coordination, and hands-on implementation.

<table>
  <tr>
    <td width="50%" valign="top">
      <p><sub>01 / SPEECH & LLM</sub> &nbsp; <img src="https://img.shields.io/badge/Production-238636?style=flat-square" alt="Production"/></p>
      <h3><a href="https://github.com/akirakawashi/speech-backend">Speech Analytics</a></h3>
      <p>Reworked an ASR and LLM call analytics system with another developer, split it into services, and introduced GigaAM with Triton/TensorRT.</p>
      <p><strong>≈ 5,000 calls per hour</strong><br/><sub>Full pipeline · load tests</sub></p>
      <p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&amp;logo=python&amp;logoColor=white" alt="Python"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&amp;logo=fastapi&amp;logoColor=white" alt="FastAPI"/> <img src="https://img.shields.io/badge/GigaAM-475569?style=flat-square" alt="GigaAM"/> <img src="https://img.shields.io/badge/LLM-475569?style=flat-square" alt="LLM"/></p>
      <p><a href="https://github.com/akirakawashi/speech-backend">Backend</a> · <a href="https://github.com/akirakawashi/speech-worker">Worker</a> · <a href="https://github.com/akirakawashi/speech-frontend">Frontend</a></p>
      <details><summary>GigaAM ASR — recognition service</summary><p>HTTP speech recognition service. The encoder runs on GPU through Triton/TensorRT; audio preparation and decoding run on CPU. Models load once per process, with parallel recording processing.</p><p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&amp;logo=python&amp;logoColor=white" alt="Python"/> <img src="https://img.shields.io/badge/TensorRT-76B900?style=flat-square&amp;logo=nvidia&amp;logoColor=white" alt="TensorRT"/> <img src="https://img.shields.io/badge/NVIDIA%20Triton%20Inference%20Server-76B900?style=flat-square&amp;logo=nvidia&amp;logoColor=white" alt="NVIDIA Triton Inference Server"/></p><p><a href="https://github.com/akirakawashi/speech-gigaam">speech-gigaam</a></p></details>
    </td>
    <td width="50%" valign="top">
      <p><sub>02 / COMPUTER VISION</sub> &nbsp; <img src="https://img.shields.io/badge/Production-238636?style=flat-square" alt="Production"/></p>
      <h3><a href="https://github.com/akirakawashi/ai_ad_backend">AI Ad</a></h3>
      <p>Independently developed and deployed outdoor advertising video analytics to production: detection, VLM brand classification, geolocation, and route analytics.</p>
      <p><strong>4–5 hours of video per week</strong><br/><sub>Current processing volume</sub></p>
      <p><img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&amp;logo=pytorch&amp;logoColor=white" alt="PyTorch"/> <img src="https://img.shields.io/badge/YOLO-475569?style=flat-square" alt="YOLO"/> <img src="https://img.shields.io/badge/VLM-475569?style=flat-square" alt="VLM"/></p>
      <p><a href="https://github.com/akirakawashi/ai_ad_backend">Backend</a> · <a href="https://github.com/akirakawashi/ai_ad_ml">ML</a> · <a href="https://github.com/akirakawashi/ai_ad_frontend">Frontend</a></p>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <p><sub>03 / LLM PLATFORM</sub> &nbsp; <img src="https://img.shields.io/badge/Production-238636?style=flat-square" alt="Production"/></p>
      <h3><a href="https://akirakawashi.github.io/my-profile/#experience">Enterprise LLM Platform</a></h3>
      <p>Designed centralized architecture for LLMs/VLMs, guardrails, and AI agent tools. Coordinate development, integrations, and GPU infrastructure optimization.</p>
      <p><img src="https://img.shields.io/badge/Qwen-475569?style=flat-square" alt="Qwen"/> <img src="https://img.shields.io/badge/LLM%20%2F%20VLM-475569?style=flat-square" alt="LLM / VLM"/> <img src="https://img.shields.io/badge/AI%20Agents-475569?style=flat-square" alt="AI Agents"/></p>
      <p><a href="https://akirakawashi.github.io/my-profile/#experience">Details in resume</a></p>
    </td>
  </tr>
</table>

---

## Personal Project

<table>
  <tr>
    <td width="65%" valign="top">
      <p><img src="https://img.shields.io/badge/Live%20Platform-238636?style=flat-square" alt="Live Platform"/></p>
      <h3><a href="https://github.com/akirakawashi/AiNoCraft_back">AiNoCraft</a></h3>
      <p>Live gaming platform, developed with another developer. Responsible for architecture, backend, frontend, and infrastructure. Users can register, install the client, and play.</p>
      <p><a href="https://github.com/akirakawashi/AiNoCraft_back">Backend</a> · <a href="https://github.com/akirakawashi/AiNoCraft_front">Frontend</a> · <a href="https://github.com/akirakawashi/AiNoCraft_dep">Deployment</a></p>
    </td>
    <td width="35%" valign="top">
      <h3>My Role</h3>
      <p>Architecture, backend, frontend, and infrastructure. Develop the project with another developer.</p>
      <p><img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&amp;logo=fastapi&amp;logoColor=white" alt="FastAPI"/> <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&amp;logo=react&amp;logoColor=white" alt="React"/> <img src="https://img.shields.io/badge/Kubernetes%20%2F%20k3s-326CE5?style=flat-square&amp;logo=kubernetes&amp;logoColor=white" alt="Kubernetes / k3s"/></p>
    </td>
  </tr>
</table>

---

## Freelance

Client web services, integrations, and AI solutions. I work as an independent developer.

<table>
  <tr>
    <td width="50%" valign="top">
      <p><sub>VK / GAMIFICATION</sub> &nbsp; <img src="https://img.shields.io/badge/Launched-238636?style=flat-square" alt="Launched"/></p>
      <h3><a href="https://github.com/akirakawashi/volnateca_bot">Volnateca</a></h3>
      <p>Launched VK gamification platform: tasks, points, achievements, referrals, and a reward store. Implemented the callback server and administration interface.</p>
      <p><img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&amp;logo=fastapi&amp;logoColor=white" alt="FastAPI"/> <img src="https://img.shields.io/badge/VK%20API-475569?style=flat-square" alt="VK API"/> <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&amp;logo=react&amp;logoColor=white" alt="React"/></p>
      <p><a href="https://github.com/akirakawashi/volnateca_bot">Backend</a> · <a href="https://github.com/akirakawashi/volnateca_admin">Admin</a></p>
    </td>
    <td width="50%" valign="top">
      <p><sub>WEB / BOOKING</sub> &nbsp; <img src="https://img.shields.io/badge/In%20Development-9a6700?style=flat-square" alt="In Development"/></p>
      <h3><a href="https://github.com/akirakawashi/Ridebook-backend">Ridebook</a></h3>
      <p>Intercity trip booking service, currently in development. Design segment-based seat inventory, fares, booking idempotency, and phone verification.</p>
      <p><img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&amp;logo=fastapi&amp;logoColor=white" alt="FastAPI"/> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&amp;logo=postgresql&amp;logoColor=white" alt="PostgreSQL"/> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&amp;logo=redis&amp;logoColor=white" alt="Redis"/></p>
      <p><a href="https://github.com/akirakawashi/Ridebook-backend">Backend</a></p>
    </td>
  </tr>
</table>

<details>
<summary><strong>Another project: Tilda → Nextcloud</strong></summary>

<table>
  <tr>
    <td>
      <h3><a href="https://github.com/akirakawashi/integration_layer_tilda_api">Tilda → Nextcloud</a></h3>
      <p>Webhook integration with an idempotent PostgreSQL queue, background archive processing, WebDAV uploads, and transient-failure retries.</p>
      <p><img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&amp;logo=fastapi&amp;logoColor=white" alt="FastAPI"/> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&amp;logo=postgresql&amp;logoColor=white" alt="PostgreSQL"/> <img src="https://img.shields.io/badge/WebDAV-475569?style=flat-square" alt="WebDAV"/></p>
      <p><a href="https://github.com/akirakawashi/integration_layer_tilda_api">Integration service</a></p>
    </td>
  </tr>
</table>

</details>

---

## Core Stack

<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&amp;logo=python&amp;logoColor=white" alt="Python"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&amp;logo=fastapi&amp;logoColor=white" alt="FastAPI"/> <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&amp;logo=react&amp;logoColor=white" alt="React"/> <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&amp;logo=nextdotjs&amp;logoColor=white" alt="Next.js"/> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&amp;logo=typescript&amp;logoColor=white" alt="TypeScript"/> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&amp;logo=pytorch&amp;logoColor=white" alt="PyTorch"/> <img src="https://img.shields.io/badge/Qwen-475569?style=flat-square" alt="Qwen"/> <img src="https://img.shields.io/badge/Kubernetes%20%2F%20k3s-326CE5?style=flat-square&amp;logo=kubernetes&amp;logoColor=white" alt="Kubernetes / k3s"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&amp;logo=docker&amp;logoColor=white" alt="Docker"/></p>

<details>
<summary><strong>Full stack by area</strong></summary>

<table>
  <tr>
    <td><strong>Backend</strong></td>
    <td><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&amp;logo=python&amp;logoColor=white" alt="Python"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&amp;logo=fastapi&amp;logoColor=white" alt="FastAPI"/> <img src="https://img.shields.io/badge/asyncio-475569?style=flat-square" alt="asyncio"/> <img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&amp;logo=pydantic&amp;logoColor=white" alt="Pydantic"/> <img src="https://img.shields.io/badge/SQLAlchemy%20%2F%20SQLModel-D71F00?style=flat-square&amp;logo=sqlalchemy&amp;logoColor=white" alt="SQLAlchemy / SQLModel"/> <img src="https://img.shields.io/badge/Alembic-475569?style=flat-square" alt="Alembic"/> <img src="https://img.shields.io/badge/REST%20API-475569?style=flat-square" alt="REST API"/></td>
  </tr>
  <tr>
    <td><strong>Frontend</strong></td>
    <td><img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&amp;logo=react&amp;logoColor=white" alt="React"/> <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&amp;logo=nextdotjs&amp;logoColor=white" alt="Next.js"/> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&amp;logo=typescript&amp;logoColor=white" alt="TypeScript"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&amp;logo=javascript&amp;logoColor=white" alt="JavaScript"/> <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&amp;logo=vite&amp;logoColor=white" alt="Vite"/></td>
  </tr>
  <tr>
    <td><strong>AI</strong></td>
    <td><img src="https://img.shields.io/badge/LLM%20%2F%20VLM-475569?style=flat-square" alt="LLM / VLM"/> <img src="https://img.shields.io/badge/RAG-475569?style=flat-square" alt="RAG"/> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&amp;logo=pytorch&amp;logoColor=white" alt="PyTorch"/> <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&amp;logo=huggingface&amp;logoColor=white" alt="Hugging Face"/> <img src="https://img.shields.io/badge/Qwen-475569?style=flat-square" alt="Qwen"/> <img src="https://img.shields.io/badge/vLLM-475569?style=flat-square" alt="vLLM"/> <img src="https://img.shields.io/badge/YOLO-475569?style=flat-square" alt="YOLO"/> <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&amp;logo=opencv&amp;logoColor=white" alt="OpenCV"/></td>
  </tr>
  <tr>
    <td><strong>Speech &amp; inference</strong></td>
    <td><img src="https://img.shields.io/badge/Whisper-475569?style=flat-square" alt="Whisper"/> <img src="https://img.shields.io/badge/GigaAM-475569?style=flat-square" alt="GigaAM"/> <img src="https://img.shields.io/badge/Silero%20VAD-475569?style=flat-square" alt="Silero VAD"/> <img src="https://img.shields.io/badge/NVIDIA%20Triton%20Inference%20Server-76B900?style=flat-square&amp;logo=nvidia&amp;logoColor=white" alt="NVIDIA Triton Inference Server"/> <img src="https://img.shields.io/badge/TensorRT-76B900?style=flat-square&amp;logo=nvidia&amp;logoColor=white" alt="TensorRT"/></td>
  </tr>
  <tr>
    <td><strong>Data &amp; integrations</strong></td>
    <td><img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&amp;logo=postgresql&amp;logoColor=white" alt="PostgreSQL"/> <img src="https://img.shields.io/badge/Oracle%20%2F%20PL%2FSQL-475569?style=flat-square" alt="Oracle / PL/SQL"/> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&amp;logo=redis&amp;logoColor=white" alt="Redis"/> <img src="https://img.shields.io/badge/MinIO%20%2F%20S3-475569?style=flat-square" alt="MinIO / S3"/> <img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&amp;logo=apachekafka&amp;logoColor=white" alt="Kafka"/> <img src="https://img.shields.io/badge/Webhooks-475569?style=flat-square" alt="Webhooks"/> <img src="https://img.shields.io/badge/WebDAV-475569?style=flat-square" alt="WebDAV"/></td>
  </tr>
  <tr>
    <td><strong>Infrastructure</strong></td>
    <td><img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&amp;logo=docker&amp;logoColor=white" alt="Docker"/> <img src="https://img.shields.io/badge/Docker%20Compose-2496ED?style=flat-square&amp;logo=docker&amp;logoColor=white" alt="Docker Compose"/> <img src="https://img.shields.io/badge/Kubernetes%20%2F%20k3s-326CE5?style=flat-square&amp;logo=kubernetes&amp;logoColor=white" alt="Kubernetes / k3s"/> <img src="https://img.shields.io/badge/Helm-0F1689?style=flat-square&amp;logo=helm&amp;logoColor=white" alt="Helm"/> <img src="https://img.shields.io/badge/GitLab%20CI%2FCD-FC6D26?style=flat-square&amp;logo=gitlab&amp;logoColor=white" alt="GitLab CI/CD"/> <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&amp;logo=githubactions&amp;logoColor=white" alt="GitHub Actions"/> <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&amp;logo=linux&amp;logoColor=white" alt="Linux"/></td>
  </tr>
</table>

</details>

## Engineering Approach

- Plan and break down tasks, conduct code reviews, and help developers make technical decisions.
- Take projects from requirements and architecture through deployment and maintenance.
- Separate APIs, background processes, and model inference, with explicit component contracts.
- Account for request retries, transactions, and failure recovery.
- Combine technical leadership with backend, frontend, and AI development.

I want to grow in technical leadership while continuing hands-on development.

<details>
<summary><strong>Learning Projects</strong></summary>

[Recommendation system](https://github.com/akirakawashi/Anime_Recommendation_System) · [Diamond price prediction](https://github.com/akirakawashi/Diamond_Price_Prediction) · [Vehicle detection in ROI](https://github.com/akirakawashi/roi_detection_car)

</details>

## GitHub Statistics

<p align="center"><img src="https://komarev.com/ghpvc/?username=akirakawashi&style=for-the-badge&color=7c3aed" alt="Profile views"/></p>

<div align="center">
  <img src="https://img.shields.io/badge/Work%20activity-private%20GitLab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white" alt="Private GitLab activity"/>
</div>

> Most of my work activity is in the company's private GitLab. The statistics below mainly reflect personal projects, learning work, and public repositories.

<div align="center">
  <img width="64%" src="https://github-readme-streak-stats.herokuapp.com/?user=akirakawashi&theme=tokyonight&hide_border=true" alt="GitHub streak"/>
</div>



<div align="center">
  <img width="100%" src="assets/profile-footer.svg" alt="footer"/>
</div>
