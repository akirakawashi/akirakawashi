# Alexander Ozhereliev

**Team Lead / AI Engineer · Python · Fullstack**

[Resume](https://akirakawashi.github.io/my-profile/) · [Telegram](https://t.me/akirakawashi) · [Email](mailto:akirakawashi@yandex.ru) · [Русский](README.md)

At IC8, I progressed from technical support through backend development to AI engineering and technical team leadership. I now serve as the development department lead: planning work, breaking down tasks, choosing technologies, and making architectural decisions. I continue writing code alongside the team.

I build AI services and web applications: speech recognition and analysis, computer vision, LLM/VLM integrations, Python/FastAPI backends, and React/Next.js frontends. I have also covered for the system architect.

## Selected projects

| Project | Problem and contribution | Source |
| --- | --- | --- |
| **Speech Analytics** | Develop an ASR and LLM pipeline for call topics, sales-script evaluation, transcript search, and reporting. Separate the API, audio processing, and model inference. | [Backend](https://github.com/akirakawashi/speech-backend) · [Worker](https://github.com/akirakawashi/speech-worker) · [Frontend](https://github.com/akirakawashi/speech-frontend) |
| **GigaAM ASR** | HTTP speech recognition service. The encoder runs on GPU through Triton/TensorRT; audio preparation and decoding run on CPU. Models load once per process, with parallel recording processing. | [speech-gigaam](https://github.com/akirakawashi/speech-gigaam) |
| **AI Ad** | Outdoor advertising video analytics at work. Lead backend, ML pipeline, and interface development: detection, tracking, brand classification, metrics, and mapped results. | [Backend](https://github.com/akirakawashi/ai_ad_backend) · [ML](https://github.com/akirakawashi/ai_ad_ml) · [Frontend](https://github.com/akirakawashi/ai_ad_frontend) |
| **AiNoCraft** | Created a gaming platform with accounts, a store, web portal, launcher, and game components. Responsible for architecture, core development, and contributor coordination. | [Backend](https://github.com/akirakawashi/AiNoCraft_back) · [Frontend](https://github.com/akirakawashi/AiNoCraft_front) · [Deployment](https://github.com/akirakawashi/AiNoCraft_dep) |
| **Ridebook** | Intercity trip booking. Design segment-based seat inventory, fares, booking idempotency, and phone verification. | [Backend](https://github.com/akirakawashi/Ridebook-backend) |
| **Volnateca** | VK gamification: tasks, points, achievements, referrals, and a reward store. Lead callback server and administration interface development. | [Backend](https://github.com/akirakawashi/volnateca_bot) · [Admin](https://github.com/akirakawashi/volnateca_admin) |
| **Tilda → Nextcloud** | Webhook integration with an idempotent PostgreSQL queue, background archive processing, WebDAV uploads, and transient-failure retries. | [Integration service](https://github.com/akirakawashi/integration_layer_tilda_api) |

## Core stack

| Area | Technologies |
| --- | --- |
| Backend | Python, FastAPI, asyncio, Pydantic, SQLAlchemy / SQLModel, Alembic, REST API |
| Frontend | React, Next.js, TypeScript, JavaScript, Vite |
| AI | LLM / VLM, RAG, PyTorch, Hugging Face, Qwen, YOLO, OpenCV |
| Speech & inference | Whisper, GigaAM, Silero VAD, NVIDIA Triton Inference Server, TensorRT |
| Data & integrations | PostgreSQL, Oracle / PL/SQL, Redis, MinIO / S3, Kafka, Webhooks, WebDAV |
| Infrastructure | Docker, Docker Compose, Kubernetes / k3s, Helm, CI/CD, Linux |

## Engineering approach

- Take projects from requirements and architecture through deployment and maintenance.
- Separate APIs, background processes, and model inference, with explicit component contracts.
- Account for request retries, transactions, and failure recovery.
- Combine technical leadership with backend, frontend, and AI development.

Alongside my primary role, I develop AiNoCraft and [VoidLabs](https://akirakawashi.github.io/startup/), my custom development practice for web services, AI solutions, bots, and integrations.

## Learning projects

[Recommendation system](https://github.com/akirakawashi/Anime_Recommendation_System) · [Diamond price prediction](https://github.com/akirakawashi/Diamond_Price_Prediction) · [Vehicle detection in ROI](https://github.com/akirakawashi/roi_detection_car)
