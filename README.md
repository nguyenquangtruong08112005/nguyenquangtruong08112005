# Nguyen Quang Truong

**Backend Developer Intern | Software Engineering Student**

Final-year Software Engineering student at Ton Duc Thang University with hands-on experience building backend services for ticketing and real-time communication systems. I focus on API design, data consistency, authentication, asynchronous processing, and cloud-backed delivery.

I have completed my taught coursework and am available for a full-time internship from August 2026 for three to six months.

[LinkedIn](https://www.linkedin.com/in/quangtruong0811/) | [Email](mailto:nguyenquangtruong08112005@gmail.com)

## Featured Projects

### Eventing - Multi-platform Event Ticketing Platform

A ticketing platform for attendees and organizers across web and Android clients.

- Implemented PostgreSQL checkout that locks inventory and creates orders, tickets, discounts, attendee answers, and payment state within one transaction.
- Built authenticated idempotency with replay and conflict detection, plus Elasticsearch synchronization through a transactional outbox with retry and recovery tooling.
- Implemented rotating sessions, CSRF validation, role-based access control, organizer permissions, and resource-ownership checks.
- Configured Docker delivery through GitHub Actions, AWS ECR/EC2/SSM, Terraform, Ansible, and Cloudflare.

**Stack:** Node.js, Express, PostgreSQL, Redis, Elasticsearch, Next.js, Kotlin, Docker, AWS

[Repository](https://github.com/nguyenquangtruong08112005/Eventing-Portfolio) | [Live Demo](https://eventing.moteo.fun)

### Moteo Chat - Real-time Chat and Video Call Platform

A communication platform supporting direct/group messaging and audio/video calls.

- Built seven independently runnable Node.js services for authentication, users, messaging, groups, calls, assets, and the Socket.IO gateway.
- Implemented persisted messaging with MongoDB history, Redis/Socket.IO delivery, seen states, revocation, search, attachments, and RabbitMQ group fan-out.
- Delivered rotating sessions, email verification, password recovery, TOTP MFA, and PIN-protected account changes.
- Validated 219 passing Jest/Vitest unit and component tests across the backend services and React client.

**Stack:** React, TypeScript, Node.js, Express, Socket.IO, WebRTC, MongoDB, Prisma, Redis, RabbitMQ, Docker, Nginx

[Repository](https://github.com/nguyenquangtruong08112005/moteo-chat) | [Video Demo](https://drive.google.com/drive/folders/17I_Spd6XXIROV2VkQmyBjEnEmmJF-fnq?usp=sharing)

## Freelance & Production Work

### WordPress Hosting Migration and Production Cutover

A client migration from legacy hosting with WordPress Admin as the only surviving access path to a customer-controlled DirectAdmin/LiteSpeed environment.

- Restored the existing WordPress site from an application-level archive, verified database/content integrity, and preserved forms, media, themes, plugins, and administrator access.
- Diagnosed production blockers across the effective PHP runtime, upload limits, REST/permalink routing, serialized URLs, Elementor/LiteSpeed caches, DNS, and ACME certificate validation.
- Delivered a customer-approved demo phase followed by production DNS/TLS cutover, canonical URL verification, rollback controls, and a sanitized evidence pack without publishing client identifiers or credentials.

**Stack:** WordPress, PHP 8.2, MySQL, DirectAdmin, LiteSpeed, DNS, ACME/Let's Encrypt

[Case Study and Runbook](https://github.com/nguyenquangtruong08112005/wordpress-directadmin-migration-runbook)

## More Projects

| Project | What it demonstrates | Stack |
| --- | --- | --- |
| [Product Price Crawler](https://github.com/nguyenquangtruong08112005/product-price-crawl) | Desktop crawler with HTTP/browser fallbacks, structured price extraction, confidence signals, and Excel export. | Python, Playwright, CustomTkinter |
| [TDTU Schedule Crawler](https://github.com/nguyenquangtruong08112005/Schedule-Crawler-TDTU) | CLI that manages authenticated sessions, retrieves university schedules, exports data, and tests browser flows. | Node.js, Axios, Cheerio, Playwright |
| [Pacman AI](https://github.com/nguyenquangtruong08112005/Pacman-AI-2025) | Pac-Man game with A* pathfinding, ghost avoidance, rotating mazes, experiments, and a visual map editor. | Python, Pygame, A*, BFS |

## Selected Contributions

- [DevOps Final Project](https://github.com/DinhQuocCuong28664/DevOps_Final_Project/commits?author=nguyenquangtruong08112005) - contributed CI linting, a CD pipeline, Docker fixes, and Kubernetes ingress with HTTPS.
- [Final Design Patterns](https://github.com/DinhQuocCuong28664/Final_Design_Patterns/commits?author=nguyenquangtruong08112005) - initialized the Express application and order controller, then implemented observer-based notification handling and tests.
- [Smartphone Garden](https://github.com/ngphuctoan/softeng-finalterm-smartphone-garden/commits?author=nguyenquangtruong08112005) - contributed user and records administration, Prisma-backed data changes, checkout views, and VNPay-related flows.

## Technical Skills

- **Languages:** JavaScript, TypeScript, Python, SQL, Java
- **Backend:** Node.js, Express, REST APIs, Socket.IO, JWT, OAuth
- **Data and messaging:** PostgreSQL, MongoDB, Prisma, Redis, RabbitMQ, Elasticsearch
- **Cloud and delivery:** Docker, Nginx, AWS, GitHub Actions, Terraform, Ansible
- **Developer tools:** Git, Postman, Swagger/OpenAPI, AI-assisted development with manual review and test/build validation

## Education and Credentials

- **Ton Duc Thang University** - Software Engineering, 2023 to expected 2027; GPA: 8.62/10
- **Aptis ESOL** - CEFR B2 Overall, 2024
- **Agile Development and Scrum Framework Course** - Techbase Viet Nam, May 2025

## Availability

- Available full-time from August 2026 for a three- or six-month internship
- Based in Tay Ninh and open to relocating to Ho Chi Minh City
- Interested primarily in Backend Developer Intern roles, with Full-stack Developer Intern as a secondary direction
