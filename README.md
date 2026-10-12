<img align="left" width="140" height="140" src="./avatar.png" alt="Anton Prilovsky" />

# Привет, я Антон

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&duration=3500&pause=900&color=58A6FF&center=false&vCenter=true&width=480&lines=Go+%26+Java+%2F+Spring+backend;architecture+%26+system+design;queues%2C+traces%2C+integrations)](https://git.io/typing-svg)

Backend · архитектура · system design

[![Telegram](https://img.shields.io/badge/Telegram-@sheisangel-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/sheisangel)
[![Email](https://img.shields.io/badge/Email-okey.exe%40yandex.ru-FF0000?style=flat-square&logo=maildotru&logoColor=white)](mailto:okey.exe@yandex.ru)
[![Bulkhead CRM](https://img.shields.io/badge/Bulkhead_CRM-live-111111?style=flat-square&logo=googlechrome&logoColor=white)](https://bulkheadcrm.ru)
[![Резюме](https://img.shields.io/badge/CV-резюме-555555?style=flat-square&logo=github&logoColor=white)](https://github.com/Yolowhok/Golang-Backend-developer-CV/blob/main/Anton-Prilovsky-Go-Backend-Developer-CV.html)

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white) ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)

<br clear="both" />

---

## Чем занимаюсь

- Разрабатываю высоконагруженные интеграции на Go и Java / Spring.
- Проектирую и разрабатываю backend на Go и Java / Spring: сервисы, API, модель данных, вывод в прод. Выношу куски из монолита в сервисы без простоя.
- Строю интеграции между системами: очереди, внешние API, ERP (1С), идемпотентность, outbox, DLQ, согласованность данных.
- Делаю так, чтобы инцидент искался по трейсу.
- Веду свой SaaS [Bulkhead CRM](https://bulkheadcrm.ru) — от схемы и контрактов до эксплуатации: мультитенантность, внешние CRM, SLO.

---

## 🏛️ Архитектура & Практика

Не занимаюсь оверхедом ради паттернов — подбираю архитектуру под задачу:

- **DDD & Clean / Hexagonal** — для доменов со сложной бизнес-логикой, где важно изолировать домен от инфраструктуры и сторонних API.
- **Vertical Slice** — для быстрых и изолированных фич без раздувания слоёв abstractions-over-abstractions.
- **Capability Core** — для продукта с несколькими каналами и поставщиками: стабильное ядро возможностей, вокруг — сменные адаптеры.
- **Интеграционные контуры** — проектирую межсервисное взаимодействие с учетом ненадёжности сети: transactional outbox, idempotency keys, DLQ, CDC, дедупликация на стороне consumer.
- **Observability** — выстраиваю сквозную трассировку (gRPC/Kafka context propagation) в OpenTelemetry, чтобы любой инцидент трекался от входа до SQL-запроса.

---

## Стек

<p>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=go,java,spring,postgres,redis,kafka,rabbitmq,docker,kubernetes,prometheus,grafana,linux,git&perline=7" alt="Tech stack" />
  </a>
</p>

gRPC / Protobuf · OpenTelemetry / Tempo / Loki · CI/CD (GitLab CI, GitHub Actions)

---

## Тестирование

Unit, integration, e2e, table-driven tests, моки через интерфейсы, sqlmock, race detector.

Отдельные тесты на инварианты интеграций: дедупликация, конфликты версий, изоляция тенанта.

---

## GitHub

<p>
  <img height="165" src="./assets/github-stats.svg" alt="GitHub stats" />
  <img height="165" src="./assets/top-langs.svg" alt="Top languages" />
</p>

<p>
  <img width="100%" src="./assets/activity-graph.svg" alt="Contribution activity graph" />
</p>
