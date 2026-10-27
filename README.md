# Александр Ожерельев

**AI Engineer / Fullstack Developer / Team Lead**

[Резюме](https://akirakawashi.github.io/my-profile/) · [Telegram](https://t.me/akirakawashi) · [Email](mailto:akirakawashi@yandex.ru) · [English](README.en.md)

Fullstack и AI-разработчик с 3 годами коммерческого опыта. Последние 4 месяца выполняю функции Team Lead: координирую двух разработчиков, преимущественно работающих с LLM. Планирую и распределяю задачи, проектирую архитектуру, провожу code review и продолжаю писать код вместе с командой.

Работаю в IT с 2020 года: системное администрирование Windows Server и Linux → техническая поддержка → backend → AI-инженерия и техническое руководство. В АйСи Эйт работаю с октября 2022 года.

Создаю AI-сервисы и веб-приложения: распознавание и анализ речи, компьютерное зрение, обработка документов, интеграции LLM/VLM, backend на Python/FastAPI и frontend на React/Next.js.

**За первые 4 месяца технического руководства вместе с командой вывел в production 3 AI-продукта:** видеоаналитику наружной рекламы, речевую аналитику и корпоративную LLM-платформу.

## Избранные проекты

| Проект | Задача и мой вклад | Исходники |
| --- | --- | --- |
| **Речевая аналитика** | Совместно с разработчиком переработал систему ASR и LLM-анализа звонков, разделил её на сервисы и внедрил GigaAM с Triton/TensorRT. Полный пайплайн достигал около 5 000 звонков в час в нагрузочных тестах. Система используется в production. | [Backend](https://github.com/akirakawashi/speech-backend) · [Worker](https://github.com/akirakawashi/speech-worker) · [Frontend](https://github.com/akirakawashi/speech-frontend) |
| **GigaAM ASR** | HTTP-служба распознавания речи. Энкодер работает на GPU через Triton/TensorRT; подготовка аудио и декодирование — на CPU. Модели загружаются один раз в процесс, записи обрабатываются параллельно. | [speech-gigaam](https://github.com/akirakawashi/speech-gigaam) |
| **AI Ad** | Самостоятельно разработал и вывел в production видеоаналитику наружной рекламы: детекция конструкций, VLM-классификация брендов, геопривязка и аналитика маршрутов. Обрабатывает около 4–5 часов видео в неделю. | [Backend](https://github.com/akirakawashi/ai_ad_backend) · [ML](https://github.com/akirakawashi/ai_ad_ml) · [Frontend](https://github.com/akirakawashi/ai_ad_frontend) |
| **Корпоративная LLM-платформа** | Спроектировал архитектуру централизованной работы с LLM/VLM, guardrails и инструментами для AI-агентов. Координирую развитие, интеграции и оптимизацию GPU-инфраструктуры. | [Описание в резюме](https://akirakawashi.github.io/my-profile/#experience) |
| **AiNoCraft** | Действующая игровая платформа. Развиваю её совместно с другим разработчиком, отвечаю за архитектуру, backend, frontend и инфраструктуру. Пользователи могут зарегистрироваться, установить клиент и играть. | [Backend](https://github.com/akirakawashi/AiNoCraft_back) · [Frontend](https://github.com/akirakawashi/AiNoCraft_front) · [Deployment](https://github.com/akirakawashi/AiNoCraft_dep) |
| **Ridebook** | Сервис бронирования междугородних поездок, находится в разработке. Проектирую учёт мест по сегментам маршрута, тарифы, идемпотентность бронирования и подтверждение телефона. | [Backend](https://github.com/akirakawashi/Ridebook-backend) |
| **Volnateca** | Запущенная VK-платформа геймификации: задания, баллы, достижения, рефералы и магазин призов. Реализовал callback-сервер и административный интерфейс. | [Backend](https://github.com/akirakawashi/volnateca_bot) · [Admin](https://github.com/akirakawashi/volnateca_admin) |
| **Tilda → Nextcloud** | Интеграционный сервис: приём webhook, идемпотентная очередь PostgreSQL, фоновая обработка архивов и загрузка по WebDAV с повторами при временных ошибках. | [Integration service](https://github.com/akirakawashi/integration_layer_tilda_api) |

## Основной стек

| Область | Технологии |
| --- | --- |
| Backend | Python, FastAPI, asyncio, Pydantic, SQLAlchemy / SQLModel, Alembic, REST API |
| Frontend | React, Next.js, TypeScript, JavaScript, Vite |
| AI | LLM / VLM, RAG, PyTorch, Hugging Face, Qwen, vLLM, YOLO, OpenCV |
| Speech & inference | Whisper, GigaAM, Silero VAD, NVIDIA Triton Inference Server, TensorRT |
| Данные и интеграции | PostgreSQL, Oracle / PL/SQL, Redis, MinIO / S3, Kafka, Webhooks, WebDAV |
| Инфраструктура | Docker, Docker Compose, Kubernetes / k3s, Helm, GitLab CI/CD, GitHub Actions, Linux |

## Как работаю

- Планирую и декомпозирую задачи, провожу code review и помогаю разработчикам с техническими решениями.
- Веду проекты от обсуждения требований и выбора архитектуры до внедрения и сопровождения.
- Разделяю API, фоновые процессы и модельный инференс; явно описываю контракты между компонентами.
- Учитываю повторы запросов, транзакции и восстановление после сбоев.
- Совмещаю техническое руководство с разработкой backend, frontend и AI-компонентов.

Помимо основной работы развиваю AiNoCraft. Заказные веб-сервисы, AI-решения, ботов и интеграции выполняю как независимый разработчик в рамках [VoidLabs](https://akirakawashi.github.io/startup/).

Хочу развиваться в техническом руководстве, сохраняя практическое участие в разработке.

## Учебные ML-проекты

[Рекомендательная система](https://github.com/akirakawashi/Anime_Recommendation_System) · [Прогнозирование стоимости бриллиантов](https://github.com/akirakawashi/Diamond_Price_Prediction) · [Детекция автомобилей в ROI](https://github.com/akirakawashi/roi_detection_car)
