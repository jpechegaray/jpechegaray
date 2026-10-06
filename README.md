# Juan Pablo Echegaray

**Information Systems Engineering student · Cybersecurity & Backend**
Mendoza, Argentina · UTN Facultad Regional Mendoza

I build software that real clients use, with a focus on authentication, access control and data protection.
Right now I'm going deeper into application security: secure code review, web vulnerabilities and CTFs.

> **Open to:** remote internships or projects in security or backend — full-time from **Dec 30, 2026 to Mar 20, 2027**, part-time afterwards.

---

### What I've built

**Barbershop management system** · `Python` `PySide6` `SQLite` · *real client, in production (v1.2.1)*
Commercial desktop app that replaced a business's spreadsheets: shifts, cash register by payment method, commissions, reports and statistics.
Offline licenses signed with **Ed25519** and bound to each machine, local token protected with **DPAPI**, **PBKDF2** password hashing and account lockout.
After a signing-key leak, I rotated the key, rejected the old license format and added a build check that blocks any private key from shipping.
*Private repository (client code).*

**Turismo San Juan** · `Java 21` `Spring Boot` `Spring Security` `JPA` `JavaScript`
Tourism platform with a REST API, session-based authentication, BCrypt and role-based access control for admins, providers and tourists, plus a provider approval and moderation workflow.
*Repository and security review coming soon.*

**Multi-tenant SaaS for fitness coaches** · `Next.js` `Spring Boot` `PostgreSQL` · *real client, in development*
Architecture with three layers of tenant isolation (service-level authorization, tenant-scoped queries and PostgreSQL Row Level Security), JWT validated against JWKS and signed URLs for private files.
*Private repository (client code).*

**Compilers coursework** · `ANTLR4` `Node.js`
Lexer, parser and translator to JavaScript for small teaching languages — [Analizador](https://github.com/jpechegaray/Analizador).

---

### Toolbox

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Security:** password hashing (BCrypt, PBKDF2) · digital signatures (Ed25519) · RBAC · multi-tenant isolation & RLS · secrets management

**Languages:** Spanish (native) · English (B2, certified)

---

<details>
<summary><b>En español</b></summary>

<br>

Estudiante de Ingeniería en Sistemas de Información en la UTN Facultad Regional Mendoza, orientado a **ciberseguridad y backend**.
Desarrollo software que usan clientes reales, con foco en autenticación, control de acceso y protección de datos.

**Disponible** para pasantías o proyectos remotos en seguridad o backend: full-time del 30/12/2026 al 20/03/2027 y part-time después.

</details>

<!-- Contact: add your LinkedIn and email here, e.g.
[LinkedIn](https://linkedin.com/in/your-handle) · your@email.com -->
