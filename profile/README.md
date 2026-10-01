<p align="center">
  <img src="https://raw.githubusercontent.com/Q-Vision3/.github/codex/org-profile/assets/banner.svg" alt="Q-Vision3 — Eoqul, Hanvon BW и инфраструктура" width="100%">
</p>

<p align="center">
  <b>Приложения, устройства и сервисы в одной экосистеме.</b><br>
  Eoqul · Hanvon N10Pro BW · Web · OTA
</p>

<p align="center">
  <a href="#с-чего-начать">С чего начать</a> ·
  <a href="#eoqul">Eoqul</a> ·
  <a href="#hanvon-bw">Hanvon BW</a> ·
  <a href="#инструменты-и-материалы">Инструменты и материалы</a> ·
  <a href="https://github.com/orgs/Q-Vision3/repositories">Все репозитории ↗</a>
</p>

---

## С чего начать

| Что нужно | Точка входа |
| :--- | :--- |
| **Работать над приложением Eoqul** | [eoqul](https://github.com/Q-Vision3/eoqul) — основной клиент |
| **Найти веб-приложения и сервисы** | [Раздел Eoqul ↓](#eoqul) — фронтенды, backend и связанные сервисы |
| **Собрать прошивку планшета** | [hanvon-firmware](https://github.com/Q-Vision3/hanvon-firmware) — общий workspace, команды сборки и документация |
| **Подготовить и доставить обновление** | [hanvon-ota-tool](https://github.com/Q-Vision3/hanvon-ota-tool) → [hanvon-ota-builder](https://github.com/Q-Vision3/hanvon-ota-builder) → [hanvon-ota-server](https://github.com/Q-Vision3/hanvon-ota-server) |

## Eoqul

Основной клиент и связанные веб-приложения, сервисы и инструменты.

| Репозиторий | Назначение |
| :--- | :--- |
| **[eoqul](https://github.com/Q-Vision3/eoqul)** | Основное приложение · Flutter / Android |
| [eoqul-backend](https://github.com/Q-Vision3/eoqul-backend) | Backend |
| [eoqul-admin-web](https://github.com/Q-Vision3/eoqul-admin-web) | Веб-панель администрирования |
| [eoqul-messanger-web](https://github.com/Q-Vision3/eoqul-messanger-web) | Веб-мессенджер |
| [eoqul-bilim](https://github.com/Q-Vision3/eoqul-bilim) | Веб-проект Bilim |
| [eoqul-live-viewer](https://github.com/Q-Vision3/eoqul-live-viewer) | Просмотр потока рисования Eoqul в браузере |
| [eoqul-discovery-pilot](https://github.com/Q-Vision3/eoqul-discovery-pilot) | Обнаружение устройств и ретрансляция потоков |

## Hanvon BW

Прошивка и системные компоненты **Hanvon N10Pro**, единый профиль **BW**.

| Репозиторий | Назначение |
| :--- | :--- |
| **[hanvon-firmware](https://github.com/Q-Vision3/hanvon-firmware)** | Главная точка входа: сборщик, общие утилиты, workspace и runbooks |
| [hanvon-hvsettings](https://github.com/Q-Vision3/hanvon-hvsettings) | Системное приложение настроек |
| [HeliBoard](https://github.com/Q-Vision3/HeliBoard) | Клавиатура для устройства |
| [hanvon-ota-tool](https://github.com/Q-Vision3/hanvon-ota-tool) | CLI подготовки OTA-релизов |
| [hanvon-ota-builder](https://github.com/Q-Vision3/hanvon-ota-builder) | Сборка и проверка recovery OTA-архивов |
| [hanvon-ota-server](https://github.com/Q-Vision3/hanvon-ota-server) | OTA API, nginx и реестр релизов |

<details>
<summary><b>Сборка, большие файлы и подпись</b></summary>

Работу со сборкой начинайте с [README сборщика](https://github.com/Q-Vision3/hanvon-firmware#readme). В нём описаны bootstrap, структура workspace, приложения, упаковка образов и OTA.

Исходные образы, APK и результаты сборки распространяются отдельно в силу своего веса. Git хранит исходники, конфигурации, документацию, ассеты и необходимые инструменты.

Материалы подписи находятся в отдельном приватном [hanvon-signing-keys](https://github.com/Q-Vision3/hanvon-signing-keys). Доступ определяется правами организации.

</details>

## Инструменты и материалы

| Репозиторий | Раздел |
| :--- | :--- |
| [eoqul-docforge](https://github.com/Q-Vision3/eoqul-docforge) | Инструменты Docforge |
| [adal_azamat_brandbook](https://github.com/Q-Vision3/adal_azamat_brandbook) | Брендбук Adal Azamat |
| [.github](https://github.com/Q-Vision3/.github) | Оформление и навигация этой организации |

---

<p align="center">
  Большинство репозиториев приватные. Для перехода по ссылкам войдите в GitHub с аккаунтом, у которого есть доступ.<br>
  <sub><a href="https://github.com/orgs/Q-Vision3/repositories">Каталог репозиториев</a> · <a href="https://github.com/orgs/Q-Vision3/projects">Проекты</a></sub>
</p>
