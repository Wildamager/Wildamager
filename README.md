<div align="center">

# Sergey M.

**Full-stack developer · Python / Django / FastAPI · React · Docker**

I build web applications end to end — relational models, background jobs and
APIs on the backend, the interface people actually touch on the frontend, and a
Docker Compose stack that runs the whole thing.

[![Telegram](https://img.shields.io/badge/Telegram-@mchlv_srg-2AABEE?logo=telegram&logoColor=white)](https://t.me/mchlv_srg)
[![GitHub](https://img.shields.io/badge/GitHub-Wildamager-181717?logo=github&logoColor=white)](https://github.com/Wildamager)

</div>

---

## About

Python is my main language. Most of my work is a Django or FastAPI service with
a REST API, asynchronous tasks, a database and a containerised deployment, plus
a frontend in React or in server-rendered templates.

| Area | Technologies |
|---|---|
| Backend | Python 3 · Django · FastAPI · DRF · Celery · JWT · SQLAlchemy/Alembic |
| Frontend | React · Next.js · JavaScript (ES6+) · HTML5 · CSS3 · Bootstrap |
| Data | PostgreSQL · SQLite · Redis · Elasticsearch · pandas / NumPy |
| ML and CV | OpenCV · dlib · face_recognition · scikit-learn · Haar cascades |
| Automation | aiogram 2/3 · Selenium · Playwright · Telethon · APScheduler |
| Infra | Docker Compose · Gunicorn · Nginx · WhiteNoise · Linux · Git |
| Quality | pytest · unittest · Ruff · mypy · GitHub Actions |

Beyond web applications I work with data and hardware: async scraping of
marketplaces, data visualisation on maps, computer vision on camera streams and
security research on embedded devices.

## Featured work

| Project | What it does | Stack |
|---|---|---|
| [`campus-security-analytics`](https://github.com/Wildamager/campus-security-analytics) | Video analytics for IP cameras: live stream, face and licence-plate recognition, person and car database, dashboard. Recognition runs in Celery workers so the web request never blocks on computer vision | Django · Celery · Redis · PostgreSQL · OpenCV · dlib · Docker Compose |
| [`vk-spotify-extension`](https://github.com/Wildamager/vk-spotify-extension) | Chrome extension (Manifest V3): right-click a track on VK, find it in the Spotify catalog and save it to your library | JavaScript · Chrome APIs · Spotify Web API |
| [`sports-infrastructure-map`](https://github.com/Wildamager/sports-infrastructure-map) | Interactive map of a city sports-facility dataset: linked object list, accessibility heat maps, per-sport layers, analytics and recommendations. Hackathon team RA1NF0RCE | Flask · Leaflet · Mapbox GL · GeoJSON · jQuery |
| [`marketplace-scraper`](https://github.com/Wildamager/marketplace-scraper) | Scrapers for Russian drone and electronics marketplaces: category trees, pagination and structured JSON output | Python · requests · BeautifulSoup · lxml |
| [`lct2026_task_2`](https://github.com/Wildamager/lct2026_task_2) | Security research on an RP2040 board: BOOTSEL flash dump, automated PIN brute force, hardware attack vectors | Python · Raspberry Pi GPIO · reverse engineering |
| [`psb_sport`](https://github.com/Wildamager/psb_sport) | Telegram bot for a sports school: schedule, student records, group announcements (work in progress) | Python · aiogram 2 · SQLAlchemy · APScheduler |

## Private and client work

These repositories are not public, so the code stays where it belongs, but the
work is real:

- **DanceSpace** — commercial platform for the dance industry: FastAPI service
  with JWT auth, media storage in MinIO, background jobs and a Next.js frontend.
- **VPNservice** — Django control panel that provisions OpenVPN containers per
  user and hands out `.ovpn` profiles.
- **PriceRanker (BestBuyBot)** — Telegram bot and Mini App that tracks prices
  across Wildberries, Ozon and Yandex.Market, with Playwright parsers and
  Telegram Stars payments.
- **Product catalogue search** — React SPA plus Django, Elasticsearch and Celery;
  currently a prototype.
- Two Telegram bots: a job-application collector and a hackathon admission bot.

## Current focus

Building the product catalogue search service: catalogue models, a REST API for
listings and products, Celery tasks for parsing and indexing into Elasticsearch,
and the SPA wired to that API.

## What I care about in my own code

- No secrets in the repository: everything comes from the environment, `.env` is
  ignored, and `.env.example` documents what is needed.
- Pinned dependencies and a documented setup path, so a fresh clone runs.
- Tests where behaviour matters: the camera analytics API has a test suite, the
  bots have unit tests, and the FastAPI service runs pytest in CI.
- READMEs that say what actually works — including the parts that do not.

## Contributing

Issues and pull requests are welcome. Each project README has its own setup
instructions and an honest status section.

---

<div align="center">

### RU — коротко

Привет, я Сергей, full-stack разработчик: Python (Django, FastAPI) + React,
PostgreSQL, Redis, Elasticsearch, Docker Compose.

Открытые проекты: аналитика с камер видеонаблюдения с распознаванием лиц и
автомобильных номеров, расширение VK → Spotify, интерактивная карта спортивных
объектов с тепловыми картами доступности, парсеры маркетплейсов, исследование
прошивки RP2040 и Telegram-бот для спортивной школы.

Часть работы закрыта: коммерческая платформа для танцевальной индустрии
(FastAPI + Next.js), панель управления VPN-контейнерами, Telegram-бот с
отслеживанием цен маркетплейсов и телеграм-боты для откликов на вакансии и
заявок на хакатон.

Пишу код с тестами, зафиксированными зависимостями, настройками из окружения и
README, который честно описывает состояние проекта.

Открыт к предложениям и задачам: [Telegram](https://t.me/mchlv_srg)

</div>