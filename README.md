<h1 align="center">Михаил Акулов · Go Backend Developer</h1>

<p align="center">
  Микросервисы · асинхронные очереди · надёжная доставка сообщений · PostgreSQL на чистом SQL
</p>

<p align="center">
  <a href="https://t.me/zero_tolerr"><img src="https://img.shields.io/badge/Telegram-zero__tolerr-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="mailto:mikhail.mikhail.akulov@gmail.com"><img src="https://img.shields.io/badge/Email-написать-0e2f3a?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Пермь-удалённо%20·%20релокация-1ba3c6?style=flat-square" alt="Location">
</p>

---

### 👋 Обо мне

Пишу backend на **Go**. Уже полтора года в **ЭР-Телеком Холдинге** веду разработку версии 2.0 коммерческой «Платформы анализа защищённости» и переношу бизнес-логику с Python на Go. Люблю разбираться, почему система тормозит или теряет данные, и чинить это архитектурно, а не костылём.

Студент 4 курса «Программной инженерии» НИУ ВШЭ (выпуск 2027).

### 📈 Чем могу похвастаться

| | |
|---|---|
| **× 725** | ускорил тяжёлый аналитический SQL-запрос в PostgreSQL |
| **× 20** | снизил потребление ресурсов сервиса |
| **× 4** | рост пропускной способности сервиса приёма телеметрии (Worker Pool + RabbitMQ Quorum) |
| **at-least-once** | спроектировал отказоустойчивую доставку задач агентам: RabbitMQ + Transactional Outbox |

### 🛠 Стек

**Языки:** Go · Python · SQL
<br>
**Данные:** PostgreSQL · pgvector · Redis
<br>
**Брокеры и оркестрация:** Kafka · RabbitMQ · Temporal
<br>
**API:** gRPC · REST · WebSockets
<br>
**Архитектура:** микросервисы · Clean Architecture · EDA · Transactional Outbox
<br>
**Безопасность:** TLS / mTLS · JWT · Casbin (RBAC)
<br>
**Инфраструктура и наблюдаемость:** Docker · CI/CD · Linux · Prometheus · Grafana · Loki · Jaeger

<p>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis">
  <img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" alt="Kafka">
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white" alt="RabbitMQ">
  <img src="https://img.shields.io/badge/Temporal-000000?style=flat-square&logo=temporal&logoColor=white" alt="Temporal">
  <img src="https://img.shields.io/badge/gRPC-244c5a?style=flat-square&logo=grpc&logoColor=white" alt="gRPC">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" alt="Prometheus">
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" alt="Grafana">
  <img src="https://img.shields.io/badge/Jaeger-66CFE3?style=flat-square&logo=jaeger&logoColor=black" alt="Jaeger">
</p>

### 🚀 Проекты

#### [AI-HR-Platform](https://github.com/PluxuryPascal/AI-HR-Platform) — ИИ-скрининг резюме
Бэкенд на Go из микросервисов (auth, hiring, ai-engine, ai-worker, notification): Clean Architecture, gRPC (Buf), Temporal-воркфлоу для обработки кандидатов, RabbitMQ, PostgreSQL + pgvector для семантического поиска по резюме, Casbin RBAC. LLM-скоринг кандидатов, сравнение и генерация писем.

`Go` `gRPC` `Temporal` `RabbitMQ` `PostgreSQL` `pgvector` `Casbin` `Next.js`

#### [Импульс Города](https://github.com/andres1m/impuls-goroda) — хакатон MAX, 2026 · командный проект
Планировщик городского досуга в мессенджере MAX (чат-бот + Mini App): за 10–15 секунд строит персональный маршрут на день. Микросервисы на Go, Temporal, Kafka + DLQ, PostgreSQL + PostGIS + pgvector, Redis, трассировка в Jaeger.

`Go` `gRPC` `Temporal` `Kafka` `PostGIS` `Redis` `OpenTelemetry`

#### [SameVibe](https://github.com/PluxuryPascal/samevibe_back) — мессенджер по интересам
Асинхронный сервер на Django Channels: WebSockets, Redis channel layer, JWT-аутентификация на handshake, медиа через Cloudinary, Docker. [Фронтенд на Next.js](https://github.com/PluxuryPascal/SameVibe).

`Python` `Django Channels` `WebSockets` `Redis` `Docker`

---

<p align="center"><sub>Открыт к предложениям: full-time, удалённо или с релокацией</sub></p>
