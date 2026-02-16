<p align="center">
   <img src="https://raw.githubusercontent.com/CRMS-FRAMEWORK/.github/main/profile/assets/logo.svg" alt="CRMS Framework" width="120" />
 </p>

 <h1 align="center">CRMS Framework</h1>

 <p align="center">
   <strong>Pan-African Digital Public Good</strong><br/>
   Open-source Criminal Record Management System for law enforcement agencies across Africa
 </p>

 <p align="center">
   <a href="https://github.com/CRMS-FRAMEWORK/crms-server"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="License" /></a>
   <a href="https://github.com/CRMS-FRAMEWORK/crms-server/issues"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs Welcome" 
 /></a>
 </p>

 ---

 ## What is CRMS?

 The **Criminal Record Management System (CRMS) Framework** is a production-ready, open-source platform built to modernize how law enforcement agencies
 manage criminal records, cases, evidence, and inter-agency coordination. Designed for the African context — supporting offline-first operations, USSD
 for feature phones, and WhatsApp integration for citizen services.

 **Pilot deployment:** Sierra Leone Police Force

 ---

 ## Core Features

 | Feature | Description |
 |---------|-------------|
 | **Case Management** | End-to-end criminal case lifecycle with automatic numbering and status workflows |
 | **Evidence Tracking** | Chain-of-custody management with QR codes and file storage |
 | **Person Records** | Suspects, victims, and witnesses with encrypted PII and biometrics support |
 | **GeoCrime Analytics** | Spatial crime mapping with heatmaps, hotspot detection, and trend analysis |
 | **Offline-First PWA** | Full functionality in low-connectivity environments via Service Worker and IndexedDB |
 | **USSD Integration** | Field officers can run background checks from any feature phone |
 | **WhatsApp Integration** | Citizens can request background checks and receive alerts via WhatsApp |
 | **Inter-Agency** | REST API and webhook integration with courts, prisons, and immigration |
 | **Alerts & Warrants** | Amber alerts and wanted person broadcasts |
 | **RBAC & Audit** | Role-based access control with immutable audit trail |

 ---

 ## Repositories

 | Repository | Description |
 |-----------|-------------|
 | [**crms-server**](https://github.com/CRMS-FRAMEWORK/crms-server) | Backend API — NestJS 11, Prisma, PostgreSQL (22 modules, 29 data models) |
 | [**crms-client**](https://github.com/CRMS-FRAMEWORK/crms-client) | Web Dashboard — Next.js 16 PWA with 127+ components (shadcn/ui, Tailwind CSS,
 Leaflet maps) |
 | [**crms-docs**](https://github.com/CRMS-FRAMEWORK/crms-docs) | Official documentation — 8 sections, 91+ pages (architecture, API reference, deployment
  guides) |
 | [**crms-install**](https://github.com/CRMS-FRAMEWORK/crms-install) | Deployment — Docker Compose, Dockerfiles, and infrastructure scripts |

 ---

 ## Tech Stack

 <p align="center">
   <img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" alt="NestJS" />
   <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
   <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
   <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
   <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" alt="Prisma" />
   <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
   <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />
   <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
 </p>

 ---

 ## Quick Start

 ```bash
 # Clone the server and client
 git clone https://github.com/CRMS-FRAMEWORK/crms-server.git
 git clone https://github.com/CRMS-FRAMEWORK/crms-client.git

 # Or use Docker for the full stack
 git clone https://github.com/CRMS-FRAMEWORK/crms-install.git
 cd crms-install
 docker compose up

 See the documentation for full setup instructions.

 ---
 Designed for Africa

 - Offline-first — works on 2G/3G networks with automatic sync when connectivity returns
 - USSD support — field officers can query records from basic feature phones
 - Configurable — adaptable national ID systems, legal frameworks, police rank hierarchies, and offense codes
 - Multi-country — designed to deploy across African nations with country-specific configuration
 - Cross-border — inter-agency coordination and INTERPOL integration capabilities

 ---
 Get Involved

 - Report issues on the relevant repository
 - Submit PRs — contributions are welcome
 - Discussions — join the conversation on GitHub Discussions

 ---