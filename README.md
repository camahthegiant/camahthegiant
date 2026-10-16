# Pablo Camahort Torres

Graduado en Ingeniería Informática (Itinerario Ingeniería de Computadores) por la Universitat Jaume I. Estoy orientando mi carrera hacia DevOps: despliegue automatizado, contenedores y monitorización. Vengo del IoT y los sistemas empotrados, y eso sigue en mis proyectos.

Busco mi primer puesto de DevOps (Castellón, Valencia o remoto).

## Stack

- **DevOps:** Docker, GitHub Actions, Prometheus, Grafana, Linux, Git
- **Lenguajes:** Python, C / C++, Java
- **Datos:** PostgreSQL, SQLite
- **Embebido e IoT:** POSIX, FreeRTOS, CMake, LoRa / LoRaWAN, MQTT

## Desplegado en un VPS

Aplicaciones propias que corren en un mismo VPS de Hetzner con Coolify, y la infraestructura que las vigila. Lo estoy construyendo paso a paso con Claude Code como copiloto. Los repos de las apps son copias públicas de proyectos en uso (sin historial ni datos personales).

- **[infra](https://github.com/camahthegiant/infra)**: monitorización del VPS como código con Prometheus, Grafana y Alertmanager (avisos a Telegram). CI propio que valida cada imagen construida y despliega en Coolify solo si todo pasa.
- **[paufer-horarios](https://github.com/camahthegiant/paufer-horarios)**: SaaS de horarios escolares multi-tenant (FastAPI, Next.js, PostgreSQL con RLS). En el repo de trabajo, un pipeline de Actions con tests, imágenes en GHCR y despliegue condicionado.
- **[gast-on-finanzas](https://github.com/camahthegiant/gast-on-finanzas)**: app personal de gastos e inversiones (PWA) con sincronización bancaria mediante Open Banking.
- **[multas-club](https://github.com/camahthegiant/multas-club)**: control de multas internas de un equipo de rugby (PWA).
- **[devops-directive-github-actions-course](https://github.com/camahthegiant/devops-directive-github-actions-course)**: repo de seguimiento del curso "GitHub Actions: Beginner to Pro".

Estado: Paufer e `infra` despliegan con Actions; Gast-On y Multas siguen con el auto deploy de Coolify y son lo siguiente que migraré.

## Hardware y embebido

- **[smartlock](https://github.com/camahthegiant/smartlock)**: app Android para una cerradura inteligente: apertura por Bluetooth Low Energy, dashboard de temperatura/humedad por MQTT y registro de accesos RFID vía API REST (proyecto personal; firmware ESP32 pendiente de publicar).
- **LORA-COCOON**: Trabajo de Final de Grado (9,5/10). Arquitectura IoT híbrida que combina una red mallada LoRa P2P con LoRaWAN para agricultura de precisión, desarrollada en prácticas de I+D en Ambimetrics S.L. (código no publicable por confidencialidad de la empresa).

## Proyectos universitarios

- **[tomasulo-simulator](https://github.com/camahthegiant/tomasulo-simulator)**: simulador a nivel de ciclo del algoritmo de Tomasulo en C, con estaciones de reserva, forwarding por CDB y bancos de registros enteros y flotantes separados (EI1061, UJI).
- **[clubesportiu](https://github.com/camahthegiant/clubesportiu)**: gestión de carreras en Java/Spring Boot + Thymeleaf con PostgreSQL, roles, autenticación BCrypt y cronometraje (EI1027, UJI, proyecto en grupo).
- **[xaes](https://github.com/camahthegiant/xaes)**: herramienta CLI en Python para cifrado AES-128-CBC compatible con OpenSSL, con derivación de clave PBKDF2-HMAC-SHA256 (Seguridad Informática, UJI).

## Contacto

- Email: pablocamahort@gmail.com
- Ubicación: Castelló de la Plana, España

---

# Pablo Camahort Torres

Computer Engineering graduate (Computer Architecture track) from Universitat Jaume I. I'm moving into DevOps: automated deployment, containers and monitoring. I come from IoT and embedded systems, and that still shows in my projects.

I'm looking for my first DevOps role (Castellón, Valencia or remote).

## Stack

- **DevOps:** Docker, GitHub Actions, Prometheus, Grafana, Linux, Git
- **Languages:** Python, C / C++, Java
- **Data:** PostgreSQL, SQLite
- **Embedded and IoT:** POSIX, FreeRTOS, CMake, LoRa / LoRaWAN, MQTT

## Deployed on a VPS

Personal applications running on one Hetzner VPS with Coolify, plus the infrastructure that watches them. I'm building it step by step with Claude Code as a copilot. The app repos are public copies of projects in use (no history, no personal data).

- **[infra](https://github.com/camahthegiant/infra)**: VPS monitoring as code with Prometheus, Grafana and Alertmanager (Telegram alerts). Its own CI validates every built image and deploys to Coolify only if everything passes.
- **[paufer-horarios](https://github.com/camahthegiant/paufer-horarios)**: multi-tenant school timetable SaaS (FastAPI, Next.js, PostgreSQL with RLS). The working repo has an Actions pipeline with tests, images on GHCR and gated deploys.
- **[gast-on-finanzas](https://github.com/camahthegiant/gast-on-finanzas)**: personal expense and investment tracker (PWA) with bank sync through Open Banking.
- **[multas-club](https://github.com/camahthegiant/multas-club)**: internal fines tracker for a rugby team (PWA).
- **[devops-directive-github-actions-course](https://github.com/camahthegiant/devops-directive-github-actions-course)**: companion repo for the "GitHub Actions: Beginner to Pro" course.

Status: Paufer and `infra` deploy through Actions; Gast-On and Multas still use Coolify's auto deploy and are next on my list.

## Hardware and embedded

- **[smartlock](https://github.com/camahthegiant/smartlock)**: Android app for a smart lock: Bluetooth Low Energy open/close, MQTT temperature/humidity dashboard and RFID access logging through a REST API (personal project; ESP32 firmware to be published separately).
- **LORA-COCOON**: Bachelor's thesis (9.5/10). Hybrid IoT architecture combining a LoRa P2P mesh with LoRaWAN for precision agriculture, built during an R&D internship at Ambimetrics S.L. (code not publishable due to company confidentiality).

## University projects

- **[tomasulo-simulator](https://github.com/camahthegiant/tomasulo-simulator)**: cycle-accurate implementation of the Tomasulo algorithm in C, with reservation stations, CDB forwarding and separate integer and floating-point register banks (EI1061, UJI).
- **[clubesportiu](https://github.com/camahthegiant/clubesportiu)**: race management system in Java/Spring Boot + Thymeleaf with PostgreSQL, role-based access, BCrypt authentication and timing (EI1027, UJI, group project).
- **[xaes](https://github.com/camahthegiant/xaes)**: Python CLI tool for OpenSSL-compatible AES-128-CBC encryption, with PBKDF2-HMAC-SHA256 key derivation (Information Security, UJI).

## Contact

- Email: pablocamahort@gmail.com
- Location: Castelló de la Plana, Spain
