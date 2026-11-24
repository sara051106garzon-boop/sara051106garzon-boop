<div align="center">
  <img src="assets/banner.svg" alt="Sara Garzón — Desarrolladora de software en formación" width="100%" />
</div>

<div align="center">

# 👋 Hola, soy Sara Garzón

**Construyendo productos digitales de principio a fin**

Construyo aplicaciones con **Flutter** en el front-end y **Python / Flask** en el back-end,
con pruebas automatizadas y flujo de trabajo en equipo sobre Git.

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-sara051106garzon--boop-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/sara051106garzon-boop)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sara_Garzón-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sara-yeilyn-garz%C3%B3n-81a11734a)
[![Email](https://img.shields.io/badge/Email-sara051106garzon%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:sara051106garzon@gmail.com)
[![Instagram](https://img.shields.io/badge/Instagram-_saraaaa.g_-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/_saraaaa.g_/)

</div>

---

## 🚀 Sobre mí

**Desarrolladora Full Stack / de Software** enfocada en construir aplicaciones web
y móviles, APIs backend, bases de datos, automatización y despliegue en la nube,
desde el diseño y la lógica hasta producción.

- 🎨 Interfaces web y móviles con **Flutter**.
- ⚙️ Backend y APIs REST con **Python / Flask**.
- 🗄️ Bases de datos relacionales con **MySQL** y **SQLAlchemy**.
- 🐳 Contenedores con **Docker** y despliegue en la nube (**AWS EC2**, **Vercel**).
- 🤖 Automatización / RPA y calidad de software con **pytest** y **CI/CD**.
- 🌱 Aprendiendo buenas prácticas de arquitectura, testing y trabajo colaborativo con Git.
- 📍 Bogotá, Colombia.

---

## 🚗 ParkLink — proyecto estrella

Sistema completo de gestión de parqueaderos para **Redeban**: control de acceso,
celdas, vehículos, usuarios, roles, monitoreo y operación; con autenticación por
JWT y una app conectada a la API.

| Componente | Stack | Repositorio |
| :--- | :--- | :--- |
| **Frontend** | Flutter Web · Vercel | [`parklink-app`](https://github.com/sara051106garzon-boop/parklink-app) |
| **Backend** | Python · Flask · Gunicorn · MySQL | [`parklink-backend`](https://github.com/sara051106garzon-boop/parklink-backend) |

[![Pruebas](https://github.com/sara051106garzon-boop/parklink-backend/actions/workflows/tests.yml/badge.svg)](https://github.com/sara051106garzon-boop/parklink-backend/actions/workflows/tests.yml)
[![Rama protegida](https://img.shields.io/badge/main-protegida%20por%20CI-success?style=flat-square)](https://github.com/sara051106garzon-boop/parklink-backend/blob/main/.github/workflows/tests.yml)
[![Vercel](https://img.shields.io/badge/Vercel-Producci%C3%B3n-000000?style=flat-square&logo=vercel&logoColor=white)](https://parklink-app.vercel.app)

> API REST documentada, 10 pruebas unitarias con pytest y un pipeline en GitHub Actions
> que bloquea el merge a `main` si alguna prueba falla.

### 🏗️ Arquitectura y capacidades clave

```text
🖥️  Flutter Web (Vercel)
      │ https://parklink-app.vercel.app
      │ proxy /api/* (rewrites) → evita Mixed Content y CORS
      ▼
☁️  AWS EC2 — Docker (parklink-production-web)
      │ puerto 8001 → 5000 interno
      ▼
🐍  Gunicorn + Flask (wsgi:app)
      │ JWT · Flask-Bcrypt ($2b$) · SQLAlchemy
      ▼
🗄️  MySQL 8.0 (parklink_production)
```

- **Frontend** en Flutter Web desplegado en Vercel, con proxy inverso `/api/*`
  (`rewrites` en `vercel.json`) hacia el backend para evitar *Mixed Content* y CORS.
- **Backend** en Flask / Gunicorn ejecutándose en AWS EC2 sobre Docker
  (`parklink-production-web`, puerto `8001` → `5000`) conectado a MySQL 8.0, con
  autenticación segura con Flask-Bcrypt (`$2b$`).
- Gestión de vehículos, celdas, accesos, roles, reportes, pruebas y flujos de
  despliegue continuo.

---

## 🛠️ Stack tecnológico

**Lenguajes**

[![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)](https://dart.dev/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/es/docs/Web/JavaScript)
[![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)](https://www.java.com/)

**Frontend**

[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)](https://flutter.dev/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/es/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/es/docs/Web/CSS)

**Backend**

[![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)](https://www.sqlalchemy.org/)
[![Gunicorn](https://img.shields.io/badge/Gunicorn-499848?style=flat-square&logo=gunicorn&logoColor=white)](https://gunicorn.org/)

**Bases de datos**

[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)](https://www.mysql.com/)

**Cloud & DevOps**

[![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square&logo=amazonaws&logoColor=white)](https://aws.amazon.com/ec2/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://www.docker.com/)
[![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)](https://vercel.com/)
[![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)](https://github.com/features/actions)
[![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)](https://git-scm.com/)

**Herramientas / QA / Automatización**

[![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)](https://pytest.org/)

---

## 🎓 Formación

**FORMACIÓN ACADÉMICA**

- **Tecnólogo en Análisis y Desarrollo de Software** — Servicio Nacional de Aprendizaje (SENA) · Bogotá
  *Cursando · Egreso previsto: julio 2027 · Etapa productiva: enero 2027*
  - Formación en análisis, diseño y desarrollo de software, con programación orientada a objetos (Java) y bases de datos relacionales.
  - Metodologías de desarrollo y aseguramiento de la calidad del software.
  - Etapa productiva (práctica empresarial) en búsqueda activa de empresa patrocinadora registrada ante el SENA Bogotá.
- **Técnico en Programación de Software** — Servicio Nacional de Aprendizaje (SENA) · Bogotá
  *Graduada: diciembre 2024*
  - Desarrollo de software con Python, JavaScript y SQL aplicados a soluciones reales.
  - Creación y maquetación de páginas web con HTML5, CSS3 y JavaScript en Visual Studio Code.
  - Manejo de bases de datos relacionales, consultas SQL y principios de programación orientada a objetos.
- **Bachillerato Académico** — Colegio Gabriel Betancourt Mejía · Bogotá
  *Graduada: diciembre 2024*

**CERTIFICACIONES**

- **English Does Work — Niveles 1, 2 y 3** · SENA (2025)
- **Inmersión en Inteligencia Artificial en la Práctica** · Daxus (octubre 2026)

---

## 📂 Otros proyectos

| Proyecto | Descripción | Stack |
| :--- | :--- | :--- |
| [`world-cup-database`](https://github.com/sara051106garzon-boop/world-cup-database) | Base de datos relacional de los mundiales: esquema, carga desde CSV y consultas de análisis | SQL · PostgreSQL · Bash |
| [`practica-sqlalchemy`](https://github.com/sara051106garzon-boop/practica-sqlalchemy) | Modelado de datos con SQLAlchemy y migraciones de Alembic | Python · SQLAlchemy |
| [`practica-sqlalchemy-roles`](https://github.com/sara051106garzon-boop/practica-sqlalchemy-roles) | Modelos relacionales: usuarios, roles, canciones y álbumes | Python · SQLAlchemy |
| [`rutas-sara`](https://github.com/sara051106garzon-boop/rutas-sara) | Rutas, controladores y modelos del back-end de ParkLink | Python · Flask |
| [`parklink-backend-v1`](https://github.com/sara051106garzon-boop/parklink-backend-v1) | Primera versión del back-end de ParkLink | Python · Flask |

---

## 🐍 Contribuciones

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/sara051106garzon-boop/sara051106garzon-boop/output/snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/sara051106garzon-boop/sara051106garzon-boop/output/snake.svg" />
  <img alt="Serpiente recorriendo el gráfico de contribuciones" src="https://raw.githubusercontent.com/sara051106garzon-boop/sara051106garzon-boop/output/snake.svg" width="100%" />
</picture>

</div>

## 📊 GitHub

<div align="center">

[![Seguidores](https://img.shields.io/github/followers/sara051106garzon-boop?label=Seguidores&style=flat-square&color=2f81f7&labelColor=1f2328)](https://github.com/sara051106garzon-boop?tab=followers)
![Repos públicos](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2Fsara051106garzon-boop&query=%24.public_repos&label=Repos%20p%C3%BAblicos&style=flat-square&color=2f81f7&labelColor=1f2328)
![Último commit](https://img.shields.io/github/last-commit/sara051106garzon-boop/parklink-backend?label=%C3%9Altimo%20commit&style=flat-square&color=2f81f7&labelColor=1f2328)

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=sara051106garzon-boop&show_icons=true&hide_border=true&bg_color=1f2328&title_color=2f81f7&text_color=c9d1d9&icon_color=2f81f7" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=sara051106garzon-boop&show_icons=true&hide_border=true&bg_color=ffffff&title_color=2f81f7&text_color=1f2328&icon_color=2f81f7" />
  <img alt="Estadísticas de GitHub" src="https://github-readme-stats.vercel.app/api?username=sara051106garzon-boop&show_icons=true&hide_border=true&bg_color=ffffff&title_color=2f81f7&text_color=1f2328&icon_color=2f81f7" width="48%" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=sara051106garzon-boop&layout=compact&hide_border=true&bg_color=1f2328&title_color=2f81f7&text_color=c9d1d9" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=sara051106garzon-boop&layout=compact&hide_border=true&bg_color=ffffff&title_color=2f81f7&text_color=1f2328" />
  <img alt="Lenguajes más usados" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sara051106garzon-boop&layout=compact&hide_border=true&bg_color=ffffff&title_color=2f81f7&text_color=1f2328" width="42%" />
</picture>

</div>

---

<div align="center">

## 🤝 Contacto

[![GitHub](https://img.shields.io/badge/GitHub-sara051106garzon--boop-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/sara051106garzon-boop)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sara_Garzón-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sara-yeilyn-garz%C3%B3n-81a11734a)
[![Email](https://img.shields.io/badge/Email-sara051106garzon%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:sara051106garzon@gmail.com)
[![Instagram](https://img.shields.io/badge/Instagram-_saraaaa.g_-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/_saraaaa.g_/)

<sub>Abierta a prácticas, proyectos colaborativos y oportunidades de aprendizaje.</sub>

</div>
