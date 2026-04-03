# Links

Links is a platform that allows users to find local events they are interested in while facilitating organic friend groups—allowing users to connect without the friction of traditional social "cold-calling."
<p align="center">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" />
  <img src="https://img.shields.io/badge/API-RESTful-4CAF50?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Client-Kamloops%20Art%20Party-purple?style=for-the-badge" />
</p>

## Flutter

Originally prototyped in React Native, the project was strategically ported to Flutter for the V8 release to support our flagship client, Kamloops Art Party. Streamlining the logic for the "Group-Formation" engine into a single Dart codebase reduced technical debt and simplified the integration of local BC event metrics. Flutter also allows for faster MVP development cycle for the initial pilot launch.

## Getting Started

The platform is currently in active development, focusing on high-reliability infrastructure and a modular UI.

## Database Schema
(pic goes here)
The platform utilizes a PostgreSQL relational schema optimized for geo-spatial event discovery and high-integrity social matching. By leveraging PostGIS, the architecture supports high-precision location coordinates, while a centralized Entities and Profiles system ensures a secure, audited relationship between event organizers and community members.

## Roadmap

- [x] Technical Migration from React Native to Flutter

- [x] Relational Schema Design (PostgreSQL/Supabase)

- [x] Geographic Data Infrastructure (PostGIS Integration)

- [ ] Group-Formation Matching Engine (Phase 1: Interest Mapping)

- [ ] Real-time Chat & In-app Notifications

- [ ] Beta Pilot Launch with Kamloops Art Party

