# Alexander Ozhereliev

**AI Engineer / Fullstack Developer / Team Lead**

[Resume](https://akirakawashi.github.io/my-profile/) · [Telegram](https://t.me/akirakawashi) · [Email](mailto:akirakawashi@yandex.ru) · [Русский](README.md)

Fullstack and AI developer with 3 years of commercial experience. For the past 4 months, I have served as a Team Lead, coordinating two developers who primarily work on LLMs. I plan and allocate tasks, design architecture, conduct code reviews, and continue coding alongside the team.

I have worked in IT since 2020: Windows Server and Linux administration → technical support → backend → AI engineering and technical leadership. I joined IC8 in October 2022.

I build AI services and web applications: speech recognition and analysis, computer vision, document processing, LLM/VLM integrations, Python/FastAPI backends, and React/Next.js frontends.

**Within my first 4 months of technical leadership, delivered 3 AI products to production with the team:** outdoor advertising video analytics, speech analytics, and an enterprise LLM platform.

## Selected projects

| Project | Problem and contribution | Source |
| --- | --- | --- |
| **Speech Analytics** | Reworked an ASR and LLM call analytics system with another developer, split it into services, and introduced GigaAM with Triton/TensorRT. The full pipeline reached approximately 5,000 calls per hour in load tests. The system is in production. | [Backend](https://github.com/akirakawashi/speech-backend) · [Worker](https://github.com/akirakawashi/speech-worker) · [Frontend](https://github.com/akirakawashi/speech-frontend) |
| **GigaAM ASR** | HTTP speech recognition service. The encoder runs on GPU through Triton/TensorRT; audio preparation and decoding run on CPU. Models load once per process, with parallel recording processing. | [speech-gigaam](https://github.com/akirakawashi/speech-gigaam) |
| **AI Ad** | Independently developed and deployed outdoor advertising video analytics to production: detection, VLM brand classification, geolocation, and route analytics. Processes approximately 4–5 hours of video per week. | [Backend](https://github.com/akirakawashi/ai_ad_backend) · [ML](https://github.com/akirakawashi/ai_ad_ml) · [Frontend](https://github.com/akirakawashi/ai_ad_frontend) |
| **Enterprise LLM Platform** | Designed centralized architecture for LLMs/VLMs, guardrails, and AI agent tools. Coordinate development, integrations, and GPU infrastructure optimization. | [Details in resume](https://akirakawashi.github.io/my-profile/#experience) |
| **AiNoCraft** | Live gaming platform, developed with another developer. Responsible for architecture, backend, frontend, and infrastructure. Users can register, install the client, and play. | [Backend](https://github.com/akirakawashi/AiNoCraft_back) · [Frontend](https://github.com/akirakawashi/AiNoCraft_front) · [Deployment](https://github.com/akirakawashi/AiNoCraft_dep) |
| **Ridebook** | Intercity trip booking service, currently in development. Design segment-based seat inventory, fares, booking idempotency, and phone verification. | [Backend](https://github.com/akirakawashi/Ridebook-backend) |
| **Volnateca** | Launched VK gamification platform: tasks, points, achievements, referrals, and a reward store. Implemented the callback server and administration interface. | [Backend](https://github.com/akirakawashi/volnateca_bot) · [Admin](https://github.com/akirakawashi/volnateca_admin) |
| **Tilda → Nextcloud** | Webhook integration with an idempotent PostgreSQL queue, background archive processing, WebDAV uploads, and transient-failure retries. | [Integration service](https://github.com/akirakawashi/integration_layer_tilda_api) |

## Core stack

| Area | Technologies |
| --- | --- |
| Backend | Python, FastAPI, asyncio, Pydantic, SQLAlchemy / SQLModel, Alembic, REST API |
| Frontend | React, Next.js, TypeScript, JavaScript, Vite |
| AI | LLM / VLM, RAG, PyTorch, Hugging Face, Qwen, vLLM, YOLO, OpenCV |
| Speech & inference | Whisper, GigaAM, Silero VAD, NVIDIA Triton Inference Server, TensorRT |
| Data & integrations | PostgreSQL, Oracle / PL/SQL, Redis, MinIO / S3, Kafka, Webhooks, WebDAV |
| Infrastructure | Docker, Docker Compose, Kubernetes / k3s, Helm, GitLab CI/CD, GitHub Actions, Linux |

## Engineering approach

- Plan and break down tasks, conduct code reviews, and help developers make technical decisions.
- Take projects from requirements and architecture through deployment and maintenance.
- Separate APIs, background processes, and model inference, with explicit component contracts.
- Account for request retries, transactions, and failure recovery.
- Combine technical leadership with backend, frontend, and AI development.

Alongside my primary role, I develop AiNoCraft. I deliver web services, AI solutions, bots, and integrations as an independent developer through [VoidLabs](https://akirakawashi.github.io/startup/).

I want to grow in technical leadership while continuing hands-on development.

## Learning projects

[Recommendation system](https://github.com/akirakawashi/Anime_Recommendation_System) · [Diamond price prediction](https://github.com/akirakawashi/Diamond_Price_Prediction) · [Vehicle detection in ROI](https://github.com/akirakawashi/roi_detection_car)
