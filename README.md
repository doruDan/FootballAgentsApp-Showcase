# FootballAgentsApp-Showcase

<img width="2880" height="1704" alt="Captură de ecran 2026-05-10 182452" src="https://github.com/user-attachments/assets/b62b7cc3-8b4b-4aaf-ae4e-f1679917a463" />

**Status: In Development (Mentored Project)**

This application is a management system tailored for sports agents and scouting agencies, developed under the guidance of a Development Manager. The project focuses on efficient complex data management and database relationship integrity.

**Project Concept**

The application serves as a working tool for agents, giving them full control over their portfolio of players and partner clubs. It is a digital solution for tracking talent and centralizing football-related logistical information.

**Architecture and Features (CRUD)**

The application utilizes the ASP.NET Core MVC architecture and relies on CRUD (Create, Read, Update, Delete) operations connected to a relational database:

**Player Management**

Allows storing and editing detailed profile information:
* **Biometric Data:** Weight, height, age.
* **Personal Information:** Date of birth, country of origin.
* **Sports Profile:** On-pitch position and current club affiliation.

**Club Management**

Organizes sports entities by geographic and competitive criteria:
* The club's country of origin.
* Professional league and home stadium.

**Planned Development**

1. **API Integration (Young Talents):** Implementing an automated scouting module that fetches lists of "young talents" from an external API.
2. **Favorites System:** Enabling agents to save and track promising players in a dedicated section.
3. **Advanced Filtering:** Searching by biometric parameters (e.g., all players over 1.90m in height).

**Tech Stack**
* **Language:** C#
* **Framework:** ASP.NET Core MVC
* **Data:** SQL Server (Entity Framework / ADO.NET)
* **Logic:** One-to-Many relationships between clubs and players.

---
