# AMRIT - Accessible Medical Records via Integrated Technologies

**AMRIT** (Accessible Medical Records via Integrated Technologies) is an open-source digital health platform developed by **Piramal Swasthya Management and Research Institute (PSMRI)** to advance accessible primary healthcare in India. This repository is the central hub for community-driven enhancements, issue tracking, and collaboration, inviting developers and healthcare enthusiasts alike to contribute to AMRIT's growth. Together, we’re building a scalable, interoperable healthcare solution aimed at transforming primary care for millions.

## 🚀 Getting Started

Excited to get involved? Check out the resources below to dive right in:

- **[JIRA for Issue Tracking and Management](https://support.piramalfoundation.org/jira/projects/AMM/issues)**: Find user stories, upcoming features and bugs that are actively getting worked on by PSMRI.
- **[Confluence for Product Documentation](https://pmp.piramalswasthya.org/confluence/display/AMRIT)**: Access detailed product documentation and learn more about AMRIT’s features.
- **[Developer Documentation](https://piramal-swasthya.gitbook.io/amrit)**: Step-by-step setup and development guides to get you started.

## 📦 Repositories  

Below is the list of AMRIT's UI and API repositories with details:  

#### UI repositories

All UI repositories are built with Angular.
To run UI repositories locally, please follow the guide [here](https://piramal-swasthya.gitbook.io/amrit/developer-guide/development-environment-setup/installation-instructions/for-ui-repositories).

| Repository Name | Link | Description |
|------------------|------|-------------|
| Inventory-UI | [Inventory-UI](https://github.com/PSMRI/Inventory-UI) | AMRIT UI module for Inventory management. This module works along with Inventory-API microservice. |
| Common-UI | [Common-UI](https://github.com/PSMRI/Common-UI) | AMRIT common UI components that are used across different service lines. |
| MMU-UI | [MMU-UI](https://github.com/PSMRI/MMU-UI) | AMRIT UI module for Mobile Medical Units (MMU). This module works along with MMU-API microservice.  |
| TM-UI | [TM-UI](https://github.com/PSMRI/TM-UI) | AMRIT UI module for Telemedicine centres. This module works along with TM-API microservice.  |
| HWC-UI | [HWC-UI](https://github.com/PSMRI/HWC-UI) | AMRIT UI module for Health and Wellness Centre (HWC). This module works along with HWC-API microservice. |
| ADMIN-UI | [ADMIN-UI](https://github.com/PSMRI/ADMIN-UI) | AMRIT UI module for configuration management of deployments for Admins. This module works along with Admin-API microservice. |
| HWC-Scheduler-UI | [HWC-Scheduler-UI](https://github.com/PSMRI/HWC-Scheduler-UI) | AMRIT UI module for appointment schedule management in Health and Wellness Centre (HWC). This module works along with Scheduler-API microservice. |
| HWC-Inventory-UI | [HWC-Inventory-UI](https://github.com/PSMRI/HWC-Inventory-UI) | AMRIT UI module for Inventory management in Health and Wellness Centre (HWC). This module works along with Inventory-API microservice. |
| Scheduler-UI | [Scheduler-UI](https://github.com/PSMRI/Scheduler-UI) | AMRIT UI module for appointment schedule management. This module works along with Scheduler-API microservice. |
| ECD-UI | [ECD-UI](https://github.com/PSMRI/ECD-UI) | AMRIT UI module for Early Childhood Development (ECD) application. This module works along with ECD-API microservice. |
| Helpline1097-UI | [Helpline1097-UI](https://github.com/PSMRI/Helpline1097-UI) | AMRIT UI module for running 1097 health information helpline. This module works along with Helpline1097-API microservice. |
| Helpline104-UI | [Helpline104-UI](https://github.com/PSMRI/Helpline104-UI) | AMRIT UI module for running 104 health information helpline. This module works along with Helpline104-API microservice. |

#### API repositories

All API repositories are built with Spring Boot.
To run API repositories locally, please follow the guide [here](https://piramal-swasthya.gitbook.io/amrit/developer-guide/development-environment-setup/installation-instructions/for-api-repositories).

| Repository Name | Link | Description |
|------------------|------|-------------|
| FLW-API | [FLW-API](https://github.com/PSMRI/FLW-API) | AMRIT API microservice for handling REST API requests from FLW mobile application |
| Admin-API | [Admin-API](https://github.com/PSMRI/Admin-API) | AMRIT Configuration management API microservice for Admins to configure the platform as per deployment needs. |
| Common-API | [Common-API](https://github.com/PSMRI/Common-API) | Common services that are used across various AMRIT modules are encapsulated in common-api. Integrations like DMS, call centre to AMRIT are through common-api service |
| ECD-API | [ECD-API](https://github.com/PSMRI/ECD-API) | AMRIT API microservice to run Early Childhood Development (ECD) call centre and drive ECD UI service. |
| HWC-API | [HWC-API](https://github.com/PSMRI/HWC-API) | AMRIT Health and Wellness centre (HWC) API microservice to run HWC UI and other dependent UI components. |
| Inventory-API | [Inventory-API](https://github.com/PSMRI/Inventory-API) | Inventory service exposes REST APIs for managing medicine inventory and dispensing medicine according to the prescription to the patient. |
| MMU-API | [MMU-API](https://github.com/PSMRI/MMU-API) | AMRIT REST API endpoints for driving Mobile Medical Unit deployments and UI. MMU-API runs are a microservice. |
| Scheduler-API | [Scheduler-API](https://github.com/PSMRI/Scheduler-API) | Service that exposes REST endpoints to schedule consultation with specialist doctors. Provides various features to publish available slots, cancel slots and day views for specialists |
| TM-API | [TM-API](https://github.com/PSMRI/TM-API) | AMRIT REST API endpoints for driving Telemedicine deployments and UI. TM-API runs are a microservice. |
| Helpline1097-API | [Helpline1097-API](https://github.com/PSMRI/Helpline1097-API) | AMRIT API microservice for running 1097 pan-India AIDS health information helpline. Integrates with telephony services.  |
| Helpline104-API | [Helpline104-API](https://github.com/PSMRI/Helpline104-API) | AMRIT API microservice for running 104 health information helplines. Integrates with telephony services. |
| BeneficiaryID-Generation-API | [BeneficiaryID-Generation-API](https://github.com/PSMRI/BeneficiaryID-Generation-API) | AMRIT API microservice for generation and management of unique beneficiary IDs. |
| FHIR-API | [FHIR-API](https://github.com/PSMRI/FHIR-API) | Service that implements FHIR standard for healthcare information exchange between various systems that are used by clinicians and organisations |
| Identity-API | [Identity-API](https://github.com/PSMRI/Identity-API) | Identity API is a microservice that is used for the creation and management of beneficiaries. |

#### Mobile application repositories

Mobile applications are built with Kotlin and powered by AMRIT Platform REST APIs.

| Repository Name | Link | Description |
|------------------|------|-------------|
| FLW-Mobile-App | [FLW-Mobile-App](https://github.com/PSMRI/FLW-Mobile-App) | Android Application built in Kotlin. Powered by AMRIT Platform. FLW Mobile App is designed for healthcare programs and consultation services rendered by ASHAs to serve pregnant women, mothers, and newborns in India. |
| HWC-Mobile-App | [HWC-Mobile-App](https://github.com/PSMRI/HWC-Mobile-App) | Android Application built with Kotlin for Health and Wellness Centre management. Takes care of workflows of CHOs, Doctors, Nurses, Lab technicians and Pharmacists. |

#### Documentation repositories

The following repositories contain documentation related to AMRIT Platform.

| Repository Name | Link | Description |
|------------------|------|-------------|
| AMRIT-Docs | [AMRIT-Docs](https://github.com/PSMRI/AMRIT-Docs) | AMRIT developer documentation synced with GitBook. |
| AMRIT-DB | [AMRIT-DB](https://github.com/PSMRI/AMRIT-DB) | DB service to simplify database schema management and setting up local environments. Using Flyway for migrations, it ensures consistency in DB schema for deployments.. |
| AMRIT-Website | [AMRIT-Website](https://github.com/PSMRI/AMRIT-Website) | Website for AMRIT. This is a forked repo to create AMRIT Website. |
| AMRIT-DevOps | [AMRIT-DevOps](https://github.com/PSMRI/AMRIT-DevOps) | All things DevOps related for AMRIT are housed in this repo |

## ✍️ Contributing

Explore the **Issues** section for active tickets and opportunities to contribute. Your contributions are empowering healthcare access and innovation across India!

Join us in the mission to make primary healthcare more accessible and efficient through technology.

## Filing Issues

If you encounter any issues, bugs, or have feature requests, please file them in the [main AMRIT repository](https://github.com/PSMRI/AMRIT/issues). Centralizing all feedback helps us streamline improvements and address concerns efficiently.  

## Join Our Community

We’d love to have you join our community discussions and get real-time support!  
Join our [Discord server](https://discord.gg/FVQWsf5ENS) to connect with contributors, ask questions, and stay updated.  

