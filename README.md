<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,55:2563EB,100:7C3AED&height=210&section=header&text=akirakawashi&fontSize=54&fontColor=FFFFFF&fontAlignY=37&desc=AI%20Engineer%20%7C%20Fullstack%20Developer%20%7C%20Team%20Lead&descSize=16&descAlignY=58" alt="akirakawashi profile banner"/>
</div>

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
  <a href="https://akirakawashi.github.io/my-profile/"><img src="https://img.shields.io/badge/%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5-6366F1?style=for-the-badge" alt="Резюме"/></a>
  <img src="https://komarev.com/ghpvc/?username=akirakawashi&style=for-the-badge&color=7c3aed" alt="Profile views"/>
</div>

<h2 align="center">Александр Ожерельев</h2>

<p align="center"><strong>AI Engineer / Fullstack Developer / Team Lead</strong></p>

<p align="center"><a href="README.en.md">English</a></p>

## Обо мне

Fullstack и AI-разработчик с 3 годами коммерческого опыта. Последние 4 месяца выполняю функции Team Lead: координирую двух разработчиков, преимущественно работающих с LLM. Планирую и распределяю задачи, проектирую архитектуру, провожу code review и продолжаю писать код вместе с командой.

Работаю в IT с 2020 года: системное администрирование Windows Server и Linux → техническая поддержка → backend → AI-инженерия и техническое руководство. В АйСи Эйт работаю с октября 2022 года.

Создаю AI-сервисы и веб-приложения: распознавание и анализ речи, компьютерное зрение, обработка документов, интеграции LLM/VLM, backend на Python/FastAPI и frontend на React/Next.js.

**За первые 4 месяца технического руководства вместе с командой вывел в production 3 AI-продукта:** видеоаналитику наружной рекламы, речевую аналитику и корпоративную LLM-платформу.

## Избранные проекты

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/akirakawashi/speech-backend">Речевая аналитика</a></h3>
      <p>Совместно с разработчиком переработал систему ASR и LLM-анализа звонков, разделил её на сервисы и внедрил GigaAM с Triton/TensorRT. Полный пайплайн достигал около 5 000 звонков в час в нагрузочных тестах. Система используется в production.</p>
      <p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&amp;logo=python&amp;logoColor=white" alt="Python"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&amp;logo=fastapi&amp;logoColor=white" alt="FastAPI"/> <img src="https://img.shields.io/badge/GigaAM-475569?style=flat-square" alt="GigaAM"/> <img src="https://img.shields.io/badge/LLM-475569?style=flat-square" alt="LLM"/></p>
      <p><a href="https://github.com/akirakawashi/speech-backend">Backend</a> · <a href="https://github.com/akirakawashi/speech-worker">Worker</a> · <a href="https://github.com/akirakawashi/speech-frontend">Frontend</a></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/akirakawashi/speech-gigaam">GigaAM ASR</a></h3>
      <p>HTTP-служба распознавания речи. Энкодер работает на GPU через Triton/TensorRT; подготовка аудио и декодирование — на CPU. Модели загружаются один раз в процесс, записи обрабатываются параллельно.</p>
      <p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&amp;logo=python&amp;logoColor=white" alt="Python"/> <img src="https://img.shields.io/badge/TensorRT-76B900?style=flat-square&amp;logo=nvidia&amp;logoColor=white" alt="TensorRT"/> <img src="https://img.shields.io/badge/NVIDIA%20Triton%20Inference%20Server-76B900?style=flat-square&amp;logo=nvidia&amp;logoColor=white" alt="NVIDIA Triton Inference Server"/></p>
      <p><a href="https://github.com/akirakawashi/speech-gigaam">speech-gigaam</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/akirakawashi/ai_ad_backend">AI Ad</a></h3>
      <p>Самостоятельно разработал и вывел в production видеоаналитику наружной рекламы: детекция конструкций, VLM-классификация брендов, геопривязка и аналитика маршрутов. Обрабатывает около 4–5 часов видео в неделю.</p>
      <p><img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&amp;logo=pytorch&amp;logoColor=white" alt="PyTorch"/> <img src="https://img.shields.io/badge/YOLO-475569?style=flat-square" alt="YOLO"/> <img src="https://img.shields.io/badge/VLM-475569?style=flat-square" alt="VLM"/></p>
      <p><a href="https://github.com/akirakawashi/ai_ad_backend">Backend</a> · <a href="https://github.com/akirakawashi/ai_ad_ml">ML</a> · <a href="https://github.com/akirakawashi/ai_ad_frontend">Frontend</a></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://akirakawashi.github.io/my-profile/#experience">Корпоративная LLM-платформа</a></h3>
      <p>Спроектировал архитектуру централизованной работы с LLM/VLM, guardrails и инструментами для AI-агентов. Координирую развитие, интеграции и оптимизацию GPU-инфраструктуры.</p>
      <p><img src="https://img.shields.io/badge/Qwen-475569?style=flat-square" alt="Qwen"/> <img src="https://img.shields.io/badge/LLM%20%2F%20VLM-475569?style=flat-square" alt="LLM / VLM"/> <img src="https://img.shields.io/badge/AI%20Agents-475569?style=flat-square" alt="AI Agents"/></p>
      <p><a href="https://akirakawashi.github.io/my-profile/#experience">Описание в резюме</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/akirakawashi/AiNoCraft_back">AiNoCraft</a></h3>
      <p>Действующая игровая платформа. Развиваю её совместно с другим разработчиком, отвечаю за архитектуру, backend, frontend и инфраструктуру. Пользователи могут зарегистрироваться, установить клиент и играть.</p>
      <p><img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&amp;logo=fastapi&amp;logoColor=white" alt="FastAPI"/> <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&amp;logo=react&amp;logoColor=white" alt="React"/> <img src="https://img.shields.io/badge/Kubernetes%20%2F%20k3s-326CE5?style=flat-square&amp;logo=kubernetes&amp;logoColor=white" alt="Kubernetes / k3s"/></p>
      <p><a href="https://github.com/akirakawashi/AiNoCraft_back">Backend</a> · <a href="https://github.com/akirakawashi/AiNoCraft_front">Frontend</a> · <a href="https://github.com/akirakawashi/AiNoCraft_dep">Deployment</a></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/akirakawashi/Ridebook-backend">Ridebook</a></h3>
      <p>Сервис бронирования междугородних поездок, находится в разработке. Проектирую учёт мест по сегментам маршрута, тарифы, идемпотентность бронирования и подтверждение телефона.</p>
      <p><img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&amp;logo=fastapi&amp;logoColor=white" alt="FastAPI"/> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&amp;logo=postgresql&amp;logoColor=white" alt="PostgreSQL"/> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&amp;logo=redis&amp;logoColor=white" alt="Redis"/></p>
      <p><a href="https://github.com/akirakawashi/Ridebook-backend">Backend</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/akirakawashi/volnateca_bot">Volnateca</a></h3>
      <p>Запущенная VK-платформа геймификации: задания, баллы, достижения, рефералы и магазин призов. Реализовал callback-сервер и административный интерфейс.</p>
      <p><img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&amp;logo=fastapi&amp;logoColor=white" alt="FastAPI"/> <img src="https://img.shields.io/badge/VK%20API-475569?style=flat-square" alt="VK API"/> <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&amp;logo=react&amp;logoColor=white" alt="React"/></p>
      <p><a href="https://github.com/akirakawashi/volnateca_bot">Backend</a> · <a href="https://github.com/akirakawashi/volnateca_admin">Admin</a></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/akirakawashi/integration_layer_tilda_api">Tilda → Nextcloud</a></h3>
      <p>Интеграционный сервис: приём webhook, идемпотентная очередь PostgreSQL, фоновая обработка архивов и загрузка по WebDAV с повторами при временных ошибках.</p>
      <p><img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&amp;logo=fastapi&amp;logoColor=white" alt="FastAPI"/> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&amp;logo=postgresql&amp;logoColor=white" alt="PostgreSQL"/> <img src="https://img.shields.io/badge/WebDAV-475569?style=flat-square" alt="WebDAV"/></p>
      <p><a href="https://github.com/akirakawashi/integration_layer_tilda_api">Integration service</a></p>
    </td>
  </tr>
</table>

## Основной стек

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
    <td><strong>Данные и интеграции</strong></td>
    <td><img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&amp;logo=postgresql&amp;logoColor=white" alt="PostgreSQL"/> <img src="https://img.shields.io/badge/Oracle%20%2F%20PL%2FSQL-475569?style=flat-square" alt="Oracle / PL/SQL"/> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&amp;logo=redis&amp;logoColor=white" alt="Redis"/> <img src="https://img.shields.io/badge/MinIO%20%2F%20S3-475569?style=flat-square" alt="MinIO / S3"/> <img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&amp;logo=apachekafka&amp;logoColor=white" alt="Kafka"/> <img src="https://img.shields.io/badge/Webhooks-475569?style=flat-square" alt="Webhooks"/> <img src="https://img.shields.io/badge/WebDAV-475569?style=flat-square" alt="WebDAV"/></td>
  </tr>
  <tr>
    <td><strong>Инфраструктура</strong></td>
    <td><img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&amp;logo=docker&amp;logoColor=white" alt="Docker"/> <img src="https://img.shields.io/badge/Docker%20Compose-2496ED?style=flat-square&amp;logo=docker&amp;logoColor=white" alt="Docker Compose"/> <img src="https://img.shields.io/badge/Kubernetes%20%2F%20k3s-326CE5?style=flat-square&amp;logo=kubernetes&amp;logoColor=white" alt="Kubernetes / k3s"/> <img src="https://img.shields.io/badge/Helm-0F1689?style=flat-square&amp;logo=helm&amp;logoColor=white" alt="Helm"/> <img src="https://img.shields.io/badge/GitLab%20CI%2FCD-FC6D26?style=flat-square&amp;logo=gitlab&amp;logoColor=white" alt="GitLab CI/CD"/> <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&amp;logo=githubactions&amp;logoColor=white" alt="GitHub Actions"/> <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&amp;logo=linux&amp;logoColor=white" alt="Linux"/></td>
  </tr>
</table>

## Как работаю

- Планирую и декомпозирую задачи, провожу code review и помогаю разработчикам с техническими решениями.
- Веду проекты от обсуждения требований и выбора архитектуры до внедрения и сопровождения.
- Разделяю API, фоновые процессы и модельный инференс; явно описываю контракты между компонентами.
- Учитываю повторы запросов, транзакции и восстановление после сбоев.
- Совмещаю техническое руководство с разработкой backend, frontend и AI-компонентов.

Помимо основной работы развиваю AiNoCraft. Заказные веб-сервисы, AI-решения, ботов и интеграции выполняю как независимый разработчик в рамках VoidLabs.

Хочу развиваться в техническом руководстве, сохраняя практическое участие в разработке.

## Учебные ML-проекты

[Рекомендательная система](https://github.com/akirakawashi/Anime_Recommendation_System) · [Прогнозирование стоимости бриллиантов](https://github.com/akirakawashi/Diamond_Price_Prediction) · [Детекция автомобилей в ROI](https://github.com/akirakawashi/roi_detection_car)

## GitHub-статистика

<div align="center">
  <img src="https://img.shields.io/badge/Work%20activity-private%20GitLab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white" alt="Private GitLab activity"/>
</div>

> Большая часть моей рабочей активности находится в закрытом GitLab компании. Поэтому GitHub-статистика ниже отражает в основном личные проекты, учебные работы и публичные репозитории.

<div align="center">
  <img width="64%" src="https://github-readme-streak-stats.herokuapp.com/?user=akirakawashi&theme=tokyonight&hide_border=true" alt="GitHub streak"/>
</div>

<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:7C3AED,55:2563EB,100:0F172A&height=120&section=footer" alt="footer"/>
</div>
