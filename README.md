# FootballAgentsApp-Showcase

<img width="2880" height="1704" alt="Captură de ecran 2026-05-10 182452" src="https://github.com/user-attachments/assets/b62b7cc3-8b4b-4aaf-ae4e-f1679917a463" />

### Status: În Dezvoltare (Proiect sub mentorat)
Această aplicație este un sistem de management dedicat impresarilor și agențiilor de scouting, dezvoltat sub îndrumarea unui **Development Manager**. Proiectul pune accent pe gestionarea eficientă a datelor complexe și pe integritatea relațiilor dintre baze de date.

---

## Conceptul Proiectului
Aplicația servește drept instrument de lucru pentru agenți, oferindu-le un control total asupra portofoliului de jucători și cluburi partenere. Este o soluție digitală pentru monitorizarea talentelor și centralizarea informațiilor logistice din fotbal.

## Arhitectură și Funcționalități (CRUD)
Aplicația utilizează arhitectura **ASP.NET Core MVC** și se bazează pe operațiuni de tip **CRUD** (Create, Read, Update, Delete) conectate la o bază de date relațională:

### Managementul Jucătorilor
Permite stocarea și editarea unor profile detaliate:
* **Date Biometrice:** Greutate, înălțime, vârstă.
* **Informații Personale:** Data nașterii, țara de origine.
* **Profil Sportiv:** Poziția în teren și afilierea actuală la club.

### Managementul Cluburilor
Organizarea entităților sportive după criterii geografice și competiționale:
* Țara de origine a clubului.
* Liga profesionistă și stadionul de reședință.

<img width="2880" height="1688" alt="Captură de ecran 2026-05-10 182537" src="https://github.com/user-attachments/assets/5cb275b4-ec49-442c-929f-ebc0bc3e396f" />
Implementarea logică a serviciului de gestionare a jucătorilor, utilizând Entity Framework Core pentru interacțiunea cu baza de date și asigurând integritatea datelor prin gestionarea excepțiilor de concurență.

## Dezvoltarea planificată
1. **Integrarea unui API (Young Talents):** Implementarea unui modul de scouting automatizat care preia liste de „tinere talente” dintr-un API extern.
2. **Sistem de Favorite:** Posibilitatea agenților de a salva și monitoriza jucători promițători într-o secțiune dedicată.
3. **Filtrare Avansată:** Căutare după parametrii biometrice (ex: toți jucătorii cu înălțimea peste 1.90m).

## Stack Tehnic
* **Limbaj:** C#
* **Framework:** ASP.NET Core MVC
* **Date:** SQL Server (Entity Framework / ADO.NET)
* **Logică:** Relații de tip One-to-Many între cluburi și jucători.

---

### Despre Dezvoltator
Proiect dezvoltat de un elev la profilul **Umanist**, pasionat de fotbal și tehnologie. Acest proiect demonstrează capacitatea de a lucra cu baze de date și de a înțelege fluxurile de business dintr-o industrie reală.

> *Notă: Acest repository este destinat prezentării arhitecturii și documentației. Codul sursă complet și detaliile de conectare la baza de date sunt stocate într-un repository privat pentru securitate.*
