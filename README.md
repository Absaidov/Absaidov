# Джамал

Развиваюсь в направлении **DevOps и автоматизации**. В учебных проектах описываю облачную инфраструктуру с помощью Terraform, автоматизирую развертывание приложений в Yandex Cloud, настраиваю мониторинг и сбор логов.

Связаться со мной: [Telegram — @djoTarkinskiy](https://t.me/djoTarkinskiy).

## DevOps и автоматизация

Учебные проекты курса «DevOps-инженер».

### [Kubernetes и инфраструктура как код в Yandex Cloud](https://github.com/Absaidov/devops-engineer-from-scratch-project-319)

Перенос приложения в Managed Kubernetes. Сеть, кластер, PostgreSQL и Object Storage описаны в Terraform.

- Развертывание через Helm: настройки dev/prod, поэтапное обновление реплик, проверки готовности и миграции Flyway.
- Синхронизация секретов из Yandex Lockbox через External Secrets Operator и автоматический перезапуск приложения при их обновлении.
- Метрики в Managed Service for Prometheus, логи через Fluent Bit в Cloud Logging и оповещения через Alertmanager.

### [Мониторинг и наблюдаемость приложения](https://github.com/Absaidov/devops-engineer-from-scratch-project-318)

Продолжение проекта по развертыванию приложения: настройка метрик, логов и оповещений. Стек наблюдаемости разворачивается через Ansible на отдельной виртуальной машине.

- Сбор метрик приложения, Linux и Nginx в Prometheus, дашборды в Grafana.
- Централизованный сбор логов приложения и Nginx через Promtail в Loki, поиск с помощью LogQL.
- Алерты Grafana с уведомлениями по электронной почте о недоступности приложения, росте ошибок и времени ответа, нехватке ресурсов.

### [Развертывание приложения с Ansible и Docker в Yandex Cloud](https://github.com/Absaidov/devops-engineer-from-scratch-project-315)

Деплой контейнерного приложения с облачной базой данных и хранилищем изображений.

- Подготовка Ubuntu-сервера и управление Docker-контейнером через Ansible.
- Подключение Managed PostgreSQL и Object Storage, настройка HTTPS через Nginx и хранение секретов в Ansible Vault.
- Миграции базы данных, проверки готовности и возврат к предыдущей версии приложения.

### [Развертывание приложения на PaaS](https://github.com/Absaidov/devops-engineer-from-scratch-project-313)

Развертывание Python-приложения на FastAPI на платформе Render. Управление зависимостями через uv, команды запуска в Makefile, отслеживание ошибок с помощью Sentry.

## Технологии и инструменты

- **Системы и инструменты:** Linux (Ubuntu), Git, PowerShell, UFW.
- **Инфраструктура и автоматизация:** Terraform, Ansible, Jinja2.
- **Контейнеры и оркестрация:** Docker, Kubernetes, Helm.
- **Облачные сервисы:** Yandex Cloud (Managed Kubernetes, Container Registry, Managed Service for PostgreSQL, Object Storage), Render (PaaS).
- **Управление секретами:** Ansible Vault, Yandex Lockbox, External Secrets Operator.
- **Веб-сервер и HTTPS:** Nginx, Let's Encrypt, Certbot.
- **Базы данных и миграции:** PostgreSQL, Flyway.
- **Разработка и сборка:** Python, FastAPI, Make, uv.
- **Мониторинг и оповещения:** Prometheus, Grafana, Alertmanager, Yandex Monitoring.
- **Сбор и анализ логов:** Loki, Promtail, Fluent Bit, Logback, Yandex Cloud Logging.
- **Проверки и диагностика:** GitHub Actions, Sentry.
