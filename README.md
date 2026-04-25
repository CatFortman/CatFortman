# Hi, I'm Cat 🐱  
Technical Lead / Software Developer focused on backend systems, full-stack development, and software architecture.

I work primarily on building reliable, maintainable software systems and exploring areas across backend engineering, cloud services, and game development.

---

## Technologies

| Skills | Applied Work |
|--------|-------------|
| ⚙️ .NET / ASP.NET Core | Full-stack web applications (MatchConnect, Auth systems) |
| ☁️ Azure Cloud Services | Event-driven architecture exploration (in progress) |
| 🔐 Authentication / OAuth2 / JWT | OpenIddictAuthorizationServer |
| 🗄️ SQL Server / Data Design | MigrationTracker, SQL toolkit |
| 🌐 SPA Development (TypeScript) | Angular-based client architecture |
| 🎮 Game Development (MonoGame) | MonoGameTemplate.Net8 |
| 🧱 System Design | MigrationTracker + tooling architecture |
| 🔄 Data Pipelines | Transaction analysis + logging concepts (planned) |

---

## Highlighted Projects

### [MigrationTracker](https://github.com/CatFortman/MigrationTracker)  
![.NET](https://img.shields.io/badge/.NET-8.0-blue)

Database migration tracking and execution tool inspired by SQL source control and schema versioning systems.

---

### [MonoGameTemplate.Net8](https://github.com/CatFortman/MonoGameTemplate.Net8)  
![.NET](https://img.shields.io/badge/.NET-8.0-blue)

Reusable MonoGame 3.8 template for .NET 8, structured for rapid 2D game development with shared architecture and content pipeline support.

---

### [SqlServer.EngineeringToolkit](https://github.com/CatFortman/SqlServer.EngineeringToolkit)  
![SQL Server](https://img.shields.io/badge/SQL_Server-2019-CC2927?style=flat&logo=microsoft-sql-server&logoColor=white)

Collection of SQL Server scripts covering database operations, debugging, schema analysis, and maintenance patterns.

---

### [OpenIddict.AuthorizationServer](https://github.com/CatFortman/OpenIddict.AuthorizationServer)  
![.NET](https://img.shields.io/badge/.NET-9.0-blue)

OAuth2 / OpenID Connect authorization server implementing authentication flows using OpenIddict.

---
## 🧭 Architecture Map

```mermaid
graph LR

%% =====================
%% Application Systems
%% =====================
subgraph A[Application Systems]
    MC[MatchConnect.FullStack]
    MG[MonoGameTemplate.Net8]
end

%% =====================
%% Platform Systems
%% =====================
subgraph B[Platform & Infrastructure Systems]
    AUTH[OpenIddict.AuthorizationServer]
    MIG[MigrationTracker]
end

%% =====================
%% Data Systems
%% =====================
subgraph C[Data & Operational Systems]
    SQL[SqlServer.EngineeringToolkit]
end

%% =====================
%% Future Work
%% =====================
subgraph D[Future Direction]
    AZ[Azure Event-Driven Pipeline]
end

%% =====================
%% Main system flow (left → right)
%% =====================

MC --> AUTH
MC --> SQL

MG --> MC

AUTH --> MC

MIG --> SQL
SQL --> MIG

AZ --> SQL
AZ --> MIG
```

## GitHub Stats

[![GitHub stats](https://github-readme-stats.vercel.app/api?username=CatFortman&show_icons=true&theme=gruvbox)](https://github.com/CatFortman)

[![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=CatFortman&layout=compact&langs_count=6&theme=gruvbox)](https://github.com/CatFortman)

---

![](https://komarev.com/ghpvc/?username=CatFortman&color=orange)
