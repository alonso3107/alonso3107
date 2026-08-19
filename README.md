<div align="center">

# Alonso Flores

<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=19&pause=1400&color=F5F5F5&center=true&vCenter=true&width=520&height=40&lines=Desarrollador+full-stack;Software+apoyado+en+IA%2C+criterio+propio;Del+c%C3%B3digo+a+producci%C3%B3n">
<img alt="Desarrollador full-stack · Software apoyado en IA, criterio propio · Del código a producción" src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=19&pause=1400&color=1A1A1A&center=true&vCenter=true&width=520&height=40&lines=Desarrollador+full-stack;Software+apoyado+en+IA%2C+criterio+propio;Del+c%C3%B3digo+a+producci%C3%B3n">
</picture>

Ingeniería de Sistemas e Informática · UTP (9.° ciclo) · Ica, Perú · GMT-5

[Portafolio](https://portafolio.alonsocr2453.workers.dev/) · [Correo](mailto:alonsocr2453@gmail.com) · [GitHub](https://github.com/alonso3107)

</div>

---

## Sobre mí

Estudiante de 9.° ciclo de Ingeniería de Sistemas e Informática en la UTP (Ica). Desarrollo software apoyado en IA, no reemplazado por ella: el criterio de arquitectura, el manejo del código y las buenas prácticas siguen siendo míos. En paralelo doy tutoría de matemáticas avanzadas hace más de 2 años y mantengo proyectos personales con foco en llegar a producción de verdad: contenedores, CI/CD e infraestructura como código.

## Ahora

- Curso el 9.° ciclo en la UTP y doy tutoría de matemáticas avanzadas y razonamiento lógico.
- Desarrollo como freelance e independiente, con foco en proyectos que llegan a producción real (**SATA**, **Cruz Corcovada**).
- Apoyo mi flujo de desarrollo en agentes de IA (Claude Code, Codex, Hermes Agent, Antigravity) conectados por MCP, sin delegarles las decisiones de arquitectura ni de diseño.

---

## Stack

**Backend**
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white) ![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**Frontend**
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Astro](https://img.shields.io/badge/Astro-BC52EE?style=flat-square&logo=astro&logoColor=white) ![SolidJS](https://img.shields.io/badge/SolidJS-2C4F7C?style=flat-square&logo=solid&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**Datos y Cloud**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white) ![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)

**Entrega**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Podman](https://img.shields.io/badge/Podman-892CA0?style=flat-square&logo=podman&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Caddy](https://img.shields.io/badge/Caddy-1F88C0?style=flat-square&logo=caddy&logoColor=white)

**IA y automatización**
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square) ![CrewAI](https://img.shields.io/badge/CrewAI-FF5A1F?style=flat-square)

---

## Proyectos

### [SATA](https://github.com/alonso3107/SATA) · digitalización de trabajo de campo

`ASP.NET Core` `.NET 10` `Angular 22` `PostgreSQL` `Podman`

Reemplaza el WhatsApp y el Excel con los que una empresa de unos 15 usuarios diarios coordinaba sus trabajos de campo: el admin crea y asigna órdenes, el técnico sube evidencia fotográfica desde el celular, y al aprobar se genera un PDF que llega solo al Drive de la empresa vía un robot de n8n con acceso de solo lectura. Monolito modular con RBAC, auditoría por escritura y un asistente LLM aislado (sin acceso a base de datos ni herramientas).

<sub>958 pruebas automatizadas (333 unitarias, 164 de integración con Testcontainers, 440 de frontend, 20 de arquitectura, 1 smoke E2E) · MIT · v3.0.0 · CI/CD e infraestructura como código en GitHub Actions</sub>

### [Cruz Corcovada](https://cruzcorcovada.com) · landing inmobiliaria en producción

`Astro` `SolidJS` `Supabase` `Resend` `Cloudflare Workers`

Landing del condominio de lotes Cruz Corcovada en Ica, con plano interactivo, agenda de visitas y Libro de Reclamaciones. Sitio estático por defecto y dinámico solo donde importa (dos rutas corren como funciones edge), arquitectura limpia por capas, cabeceras de seguridad estrictas y resiliencia ante caídas de base de datos. La desarrollé como colaborador principal en una colaboración con Studio Sinclair; repositorio en [StudioSinclair/Cruz-Corcovada](https://github.com/StudioSinclair/Cruz-Corcovada).

### [Clínica San Martín](https://clinica-san-martin.pages.dev) · plataforma para clínica dental

`Astro` `Cloudflare Pages` `Cloudflare Access`

Monorepo con panel administrativo y panel de doctores independientes, desplegado en Cloudflare Pages con autenticación protegida mediante Cloudflare Access.

### [Puerba Ria](https://puerbaria.alonsocr2453.workers.dev) · Coastal Luxury

`Angular` `Java` `Spring Boot` `Terraform`

Web para un proyecto costero de lujo, con frontend en Angular y API en Java sobre Spring Boot; infraestructura declarada con Terraform y desplegada en Cloudflare. Repositorio: [PuerbaRia](https://github.com/alonso3107/PuerbaRia).

<sub>También en GitHub: [boticavr](https://github.com/alonso3107/boticavr), interfaz en React y API en FastAPI para la Botica V&R.</sub>

---

## Flujos de trabajo con IA

Uso IA como apoyo en el desarrollo, no como reemplazo del criterio: las decisiones de arquitectura, el manejo del código y las buenas prácticas siguen siendo mías. Dentro de eso, integro agentes de IA (Claude Code, Codex, Hermes Agent, Antigravity) como ejecutores, planificadores y orquestadores, con técnicas de prompting y looping para iterar hasta resultados sólidos y QA guiada por mi propio criterio. Los conecto a mis herramientas con el protocolo MCP (gestión de conocimiento en Obsidian, componentes con shadcn/ui y PrimeNG) y construyo mis propios conectores con MCP Builder. Incorporo skills reutilizables que descubro con find-skills, y uso CrewAI como framework de orquestación multiagente en proyectos personales.

---

## Actividad

<div align="center">

<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/alonso3107/alonso3107/output/github-snake-dark.svg">
<img alt="Serpiente comiéndose mis contribuciones" src="https://raw.githubusercontent.com/alonso3107/alonso3107/output/github-snake.svg">
</picture>

</div>

---

## Contacto

**[Portafolio](https://portafolio.alonsocr2453.workers.dev/)** · **[Correo](mailto:alonsocr2453@gmail.com)** · [Facebook](https://www.facebook.com/alonso.flores.221342/) · [Instagram](https://www.instagram.com/namealonsox_/) · [TikTok](https://www.tiktok.com/@namealonsox)

Abierto a colaborar, escríbeme por cualquiera de estos canales.

<div align="center">
<br>
<img alt="Visitas al perfil" src="https://komarev.com/ghpvc/?username=alonso3107&style=flat-square&label=Visitas+al+perfil&color=6e7681">
</div>
