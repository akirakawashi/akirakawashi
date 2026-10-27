# Александр Ожерельев

**Team Lead / AI Engineer · Python · Fullstack**

[Резюме](https://akirakawashi.github.io/my-profile/) · [Telegram](https://t.me/akirakawashi) · [Email](mailto:akirakawashi@yandex.ru) · [English](README.en.md)

В АйСи Эйт прошёл путь от технической поддержки через backend-разработку к AI-инженерии и техническому руководству командой. Сейчас выполняю функции руководителя отдела разработки: планирую работу, декомпозирую задачи, выбираю технологии и отвечаю за архитектурные решения. Продолжаю писать код вместе с командой.

Создаю AI-сервисы и веб-приложения: распознавание и анализ речи, компьютерное зрение, интеграции LLM/VLM, backend на Python/FastAPI и frontend на React/Next.js. Замещал архитектора системы.

## Избранные проекты

| Проект | Задача и мой вклад | Исходники |
| --- | --- | --- |
| **Речевая аналитика** | Разработка системы ASR и LLM-анализа звонков: темы обращений, оценка по скриптам продаж, поиск и отчёты. Разделение API, обработки аудио и модельного инференса. | [Backend](https://github.com/akirakawashi/speech-backend) · [Worker](https://github.com/akirakawashi/speech-worker) · [Frontend](https://github.com/akirakawashi/speech-frontend) |
| **GigaAM ASR** | HTTP-служба распознавания речи. Энкодер работает на GPU через Triton/TensorRT; подготовка аудио и декодирование — на CPU. Модели загружаются один раз в процесс, записи обрабатываются параллельно. | [speech-gigaam](https://github.com/akirakawashi/speech-gigaam) |
| **AI Ad** | Рабочий проект видеоаналитики наружной рекламы. Веду разработку backend, ML-пайплайна и интерфейса: детекция, трекинг, классификация брендов, метрики и карта результатов. | [Backend](https://github.com/akirakawashi/ai_ad_backend) · [ML](https://github.com/akirakawashi/ai_ad_ml) · [Frontend](https://github.com/akirakawashi/ai_ad_frontend) |
| **AiNoCraft** | Автор игровой платформы: аккаунты, магазин, веб-портал, лаунчер и игровые компоненты. Отвечаю за архитектуру, ключевую разработку и координацию участников. | [Backend](https://github.com/akirakawashi/AiNoCraft_back) · [Frontend](https://github.com/akirakawashi/AiNoCraft_front) · [Deployment](https://github.com/akirakawashi/AiNoCraft_dep) |
| **Ridebook** | Сервис бронирования междугородних поездок. Проектирую учёт мест по сегментам маршрута, тарифы, идемпотентность бронирования и подтверждение телефона. | [Backend](https://github.com/akirakawashi/Ridebook-backend) |
| **Volnateca** | VK-платформа геймификации: задания, баллы, достижения, рефералы и магазин призов. Веду разработку callback-сервера и административного интерфейса. | [Backend](https://github.com/akirakawashi/volnateca_bot) · [Admin](https://github.com/akirakawashi/volnateca_admin) |
| **Tilda → Nextcloud** | Интеграционный сервис: приём webhook, идемпотентная очередь PostgreSQL, фоновая обработка архивов и загрузка по WebDAV с повторами при временных ошибках. | [Integration service](https://github.com/akirakawashi/integration_layer_tilda_api) |

## Основной стек

| Область | Технологии |
| --- | --- |
| Backend | Python, FastAPI, asyncio, Pydantic, SQLAlchemy / SQLModel, Alembic, REST API |
| Frontend | React, Next.js, TypeScript, JavaScript, Vite |
| AI | LLM / VLM, RAG, PyTorch, Hugging Face, Qwen, YOLO, OpenCV |
| Speech & inference | Whisper, GigaAM, Silero VAD, NVIDIA Triton Inference Server, TensorRT |
| Данные и интеграции | PostgreSQL, Oracle / PL/SQL, Redis, MinIO / S3, Kafka, Webhooks, WebDAV |
| Инфраструктура | Docker, Docker Compose, Kubernetes / k3s, Helm, CI/CD, Linux |

## Как работаю

- Веду проекты от обсуждения требований и выбора архитектуры до внедрения и сопровождения.
- Разделяю API, фоновые процессы и модельный инференс; явно описываю контракты между компонентами.
- Учитываю повторы запросов, транзакции и восстановление после сбоев.
- Совмещаю техническое руководство с разработкой backend, frontend и AI-компонентов.

Помимо основной работы развиваю AiNoCraft и [VoidLabs](https://akirakawashi.github.io/startup/) — направление заказной разработки веб-сервисов, AI-решений, ботов и интеграций.

## Учебные ML-проекты

[Рекомендательная система](https://github.com/akirakawashi/Anime_Recommendation_System) · [Прогнозирование стоимости бриллиантов](https://github.com/akirakawashi/Diamond_Price_Prediction) · [Детекция автомобилей в ROI](https://github.com/akirakawashi/roi_detection_car)
