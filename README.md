<h1 align="center">Enrique Muñoz</h1>
<h3 align="center">Ingeniero de software · IA y automatización · Banca y fintech</h3>

<p align="center"><a href="https://enriquemunoz.lat"><strong>Portafolio · enriquemunoz.lat ↗</strong></a></p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.herokuapp.com?font=Fira+Code&amp;size=20&amp;duration=3200&amp;pause=1600&amp;color=7EE787&amp;center=true&amp;vCenter=true&amp;width=520&amp;height=52&amp;lines=IA+y+automatizaci%C3%B3n;Software+para+banca+y+fintech;Mobile%2C+backend+e+infraestructura" />
    <source media="(prefers-color-scheme: light)" srcset="https://readme-typing-svg.herokuapp.com?font=Fira+Code&amp;size=20&amp;duration=3200&amp;pause=1600&amp;color=1A7F37&amp;center=true&amp;vCenter=true&amp;width=520&amp;height=52&amp;lines=IA+y+automatizaci%C3%B3n;Software+para+banca+y+fintech;Mobile%2C+backend+e+infraestructura" />
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&amp;size=20&amp;duration=3200&amp;pause=1600&amp;color=1A7F37&amp;center=true&amp;vCenter=true&amp;width=520&amp;height=52&amp;lines=IA+y+automatizaci%C3%B3n;Software+para+banca+y+fintech;Mobile%2C+backend+e+infraestructura" alt="IA y automatización · Software para banca y fintech · Mobile, backend e infraestructura" width="520" />
  </picture>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/enrique-mu%C3%B1oz-aa6345267/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge" alt="Contactar en LinkedIn" /></a>
  <a href="mailto:enriquemunozdev@gmail.com"><img src="https://img.shields.io/badge/Email-163B2A?style=for-the-badge&amp;logo=gmail&amp;logoColor=white" alt="Contactar por correo electrónico" /></a>
</p>

<p align="center">
  <a href="#experiencia-profesional">Trayectoria</a> ·
  <a href="#proyectos-de-ia">Proyectos de IA</a> ·
  <a href="#tecnologias-y-areas-de-trabajo">Tecnologías</a> ·
  <a href="#formacion-y-reconocimientos">Formación</a>
</p>

---

Ingeniero de software con experiencia en inteligencia artificial, automatización y soluciones para banca y fintech. Combino desarrollo móvil, backend e infraestructura con integración de LLMs y herramientas avanzadas de IA para resolver problemas de negocio. Actualmente curso una **Maestría en Inteligencia Artificial**, profundizando mi experiencia práctica con formación especializada.

**Nicaragua · Full Stack · Mobile · Backend · Infraestructura**

## Experiencia profesional

**Tribal WorldWide Guatemala · Desarrollo Full Stack**  
Junio de 2026 — actualidad

- Desarrollo de productos para banca, comercio electrónico y bienes raíces, desde los requerimientos hasta la implementación.
- Actualmente trabajo con **microservicios en Go, OpenShift, Kubernetes y aplicaciones móviles bancarias nativas**.

**Grupo LAFISE / Sistemática Internacional · Desarrollo móvil**  
Junio de 2025 — junio de 2026

- Desarrollo y liderazgo técnico de módulos para **LAFISE Digital**, aplicación bancaria construida con **React Native, Expo y TypeScript**.
- Trabajo en equipos ágiles, optimización de funcionalidades y código mantenible, con atención a la experiencia de usuario.

**Itel (anteriormente CooTel) · Ingeniería de software**  
Diciembre de 2023 — junio de 2025

- Liderazgo de proyectos de **automatización en telecomunicaciones** con React y Laravel.
- Modernización de sistemas existentes, migración de servidores y refactorización para mejorar rendimiento y escalabilidad.

**Proyectos freelance · Desarrollo de software a medida**  
Desde 2023

- Colaboración directa con clientes para entender sus procesos y construir módulos ERP y sistemas de información con Laravel, PHP, MySQL y React.

---

## Proyectos de IA

### [Finest Computer Use — automatización de escritorio para agentes](https://github.com/enriquemdev/finest-computer-use)

Desarrollé un motor de integración y control para habilitar **computer use en agentes de IA**, probado con Gemini en Antigravity sobre macOS mediante **Peekaboo MCP**.

- Capa propia en Python que intercepta herramientas y aplica autorización por tarea, límites de acciones y aislamiento de estado.
- Ciclo de observación, acción y verificación; controles para reducir acciones no autorizadas y recuperar el flujo ante cambios inesperados de la interfaz.
- Instalación con respaldo y rollback, diagnósticos, suites de regresión y documentación de arquitectura.

**Python · Agentes de IA · MCP · Gemini/Antigravity · Automatización macOS**

### [Global Chatbot — asistentes con conocimiento de negocio](https://github.com/enriquemdev/Global-Chatbot)

Construí una plataforma de asistentes configurables para sitios web: **RAG con fuentes citadas**, panel administrativo y un widget aislado que se integra mediante un script.

- Importación de texto, FAQ, PDF y URL; revisión y publicación del conocimiento por negocio.
- Recuperación híbrida con embeddings E5 y PostgreSQL/pgvector; integración de Gemini para responder con contexto y fuentes.
- Aislamiento multi-tenant con RLS, control de consumo, idempotencia y registro de conversaciones y contactos con consentimiento.
- MVP desplegado en Vercel + Neon, con demo pública y evidencia documentada de consultas reales.

**TypeScript · Next.js · RAG · Gemini · PostgreSQL/pgvector · Vercel · Neon**

[Probar demo](https://global-chatbot-mvp.vercel.app/demo/aurora) · [Repositorio y documentación](https://github.com/enriquemdev/Global-Chatbot)

### [Banking77 — clasificación de consultas bancarias](https://github.com/enriquemdev/banking77-transformers-demo)

Segundo proyecto de mi **Maestría en Inteligencia Artificial**: ajuste de DistilRoBERTa para clasificar consultas en inglés en **77 intenciones bancarias**, comparado con un baseline TF-IDF + regresión logística.

- **92,82 % de accuracy y 92,82 % de F1 macro** en el test oficial de 3.080 consultas; baseline: 85,03 % de accuracy.
- Análisis de errores con Falcon-7B-Instruct en el notebook académico.
- Demo de inferencia con FastAPI y Modal; notebook ejecutado, métricas e informe disponibles.

**Python · Transformers · NLP · DistilRoBERTa · FastAPI · Modal**

### Otros proyectos de IA

- **[NexTalk](https://github.com/enriquemdev/NexTalk):** conversaciones en tiempo real y resúmenes con GPT-4o, Vercel AI SDK, Next.js y Convex.
- **[Oxford-IIIT Pet](https://github.com/enriquemdev/Ai-Oxford-IIIT-Pet-Dataset):** primer proyecto de maestría, grupal y con implementación completa a mi cargo. Clasificación de 37 razas con TensorFlow/Keras y MobileNetV2; seis experimentos, **86,14 % de accuracy y 85,10 % de F1 macro en test**.

## Contribuciones open source

### [Filament Map Picker](https://github.com/dotswan/filament-map-picker)

Contribuí a este componente del ecosistema **Laravel / Filament** para permitir actualizaciones de ubicación en tiempo real sin depender de que el mapa fuera arrastrable, y configurar el intervalo de actualización.

**[Pull request #33 — aceptado e integrado](https://github.com/dotswan/filament-map-picker/pull/33)** · Septiembre de 2024

---

<a id="tecnologias-y-areas-de-trabajo"></a>
## Tecnologías y áreas de trabajo

### IA y automatización

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&amp;logo=python&amp;logoColor=white" />
  <img alt="TensorFlow" src="https://img.shields.io/badge/TensorFlow-C65D09?style=for-the-badge&amp;logo=tensorflow&amp;logoColor=white" />
  <img alt="OpenAI" src="https://img.shields.io/badge/OpenAI-345A50?style=for-the-badge" />
  <img alt="Vercel AI SDK" src="https://img.shields.io/badge/Vercel%20AI%20SDK-181717?style=for-the-badge&amp;logo=vercel&amp;logoColor=white" />
</p>

Integración de LLMs y automatización con Python; TensorFlow/Keras y evaluación de modelos en proyectos académicos.

**Desarrollo asistido por IA:** Claude Code, Codex, Cursor y GitHub Copilot.

### Desarrollo móvil y web

<p>
  <img alt="React Native" src="https://img.shields.io/badge/React%20Native-176B80?style=for-the-badge&amp;logo=react&amp;logoColor=white" />
  <img alt="Expo" src="https://img.shields.io/badge/Expo-181717?style=for-the-badge&amp;logo=expo&amp;logoColor=white" />
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&amp;logo=typescript&amp;logoColor=white" />
  <img alt="React" src="https://img.shields.io/badge/React-176B80?style=for-the-badge&amp;logo=react&amp;logoColor=white" />
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-181717?style=for-the-badge&amp;logo=nextdotjs&amp;logoColor=white" />
</p>

Aplicaciones móviles con React Native y Expo, trabajo con aplicaciones bancarias nativas **Android e iOS**, e interfaces web con React y Next.js.

### Backend y microservicios

<p>
  <img alt="Go" src="https://img.shields.io/badge/Go-087F99?style=for-the-badge&amp;logo=go&amp;logoColor=white" />
  <img alt="Laravel" src="https://img.shields.io/badge/Laravel-C43B32?style=for-the-badge&amp;logo=laravel&amp;logoColor=white" />
  <img alt="PHP" src="https://img.shields.io/badge/PHP-626DA8?style=for-the-badge&amp;logo=php&amp;logoColor=white" />
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-397A32?style=for-the-badge&amp;logo=nodedotjs&amp;logoColor=white" />
  <img alt="Express" src="https://img.shields.io/badge/Express-30363D?style=for-the-badge&amp;logo=express&amp;logoColor=white" />
</p>

Servicios, APIs REST y sistemas de información con Go, Laravel y el ecosistema Node.js.

### Infraestructura y datos

<p>
  <img alt="OpenShift" src="https://img.shields.io/badge/OpenShift-C32228?style=for-the-badge&amp;logo=redhatopenshift&amp;logoColor=white" />
  <img alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&amp;logo=kubernetes&amp;logoColor=white" />
  <img alt="Docker" src="https://img.shields.io/badge/Docker-1769AA?style=for-the-badge&amp;logo=docker&amp;logoColor=white" />
  <img alt="Linux" src="https://img.shields.io/badge/Linux-30363D?style=for-the-badge&amp;logo=linux&amp;logoColor=white" />
  <img alt="Git" src="https://img.shields.io/badge/Git-C74630?style=for-the-badge&amp;logo=git&amp;logoColor=white" />
</p>

<p>
  <img alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&amp;logo=mysql&amp;logoColor=white" />
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169A1?style=for-the-badge&amp;logo=postgresql&amp;logoColor=white" />
  <img alt="SQL Server" src="https://img.shields.io/badge/SQL%20Server-8F263B?style=for-the-badge" />
  <img alt="SQLite" src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&amp;logo=sqlite&amp;logoColor=white" />
  <img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-357B36?style=for-the-badge&amp;logo=mongodb&amp;logoColor=white" />
</p>

<details>
<summary><strong>Más herramientas de mi experiencia full stack</strong></summary>

<br />

<p>
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-6B5900?style=for-the-badge&amp;logo=javascript&amp;logoColor=white" />
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-B84322?style=for-the-badge&amp;logo=html5&amp;logoColor=white" />
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-245CA6?style=for-the-badge" />
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind%20CSS-087F99?style=for-the-badge&amp;logo=tailwindcss&amp;logoColor=white" />
  <img alt="Flask" src="https://img.shields.io/badge/Flask-30363D?style=for-the-badge&amp;logo=flask&amp;logoColor=white" />
  <img alt="Django" src="https://img.shields.io/badge/Django-0C4B33?style=for-the-badge&amp;logo=django&amp;logoColor=white" />
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-007D72?style=for-the-badge&amp;logo=fastapi&amp;logoColor=white" />
  <img alt="NestJS" src="https://img.shields.io/badge/NestJS-BA2348?style=for-the-badge&amp;logo=nestjs&amp;logoColor=white" />
  <img alt="Postman" src="https://img.shields.io/badge/Postman-B94416?style=for-the-badge&amp;logo=postman&amp;logoColor=white" />
</p>

También he trabajado con Bootstrap, Material UI, shadcn/ui, jQuery, Inertia.js y CodeIgniter.

</details>

## Cómo trabajo

- **Problema antes que herramienta:** entender el proceso y la necesidad del negocio.
- **Construcción de extremo a extremo:** conectar interfaz, servicios, datos e infraestructura.
- **IA con criterio:** integrar herramientas y modelos, comprobar resultados y documentar limitaciones.
- **Colaboración:** trabajo en equipo, código mantenible y aportes open source.

---

<a id="formacion-y-reconocimientos"></a>
## Formación y reconocimientos

- **Maestría en Inteligencia Artificial — en curso.**
- **Ingeniería de Sistemas — Universidad Nacional de Ingeniería (UNI).**
- **Técnico Contable — Universidad Anunciata.**
- **CS50x — completado en 2023.** [Ver certificado](https://cs50.harvard.edu/certificates/465f76db-93e6-464e-a930-f037e42667ce).
- **Scrum Foundation — CertiProf.**
- **Primer lugar en la categoría Impacto Social, sede UNI-IES, Nicaragua — Rally Latinoamericano de Innovación 2023**, como integrante del equipo participante.

## Actividad en GitHub

<p align="center">
  <a href="https://github.com/enriquemdev?tab=overview"><img src="https://github-readme-streak-stats.herokuapp.com/?user=enriquemdev&amp;theme=dark&amp;hide_border=true&amp;background=0D1117&amp;ring=7EE787&amp;fire=7EE787&amp;currStreakLabel=7EE787&amp;sideLabels=C9D1D9&amp;currStreakNum=F0F6FC&amp;sideNums=F0F6FC&amp;dates=8B949E" alt="Actividad y rachas de contribución en GitHub" width="420" /></a>
  <a href="https://github.com/enriquemdev?tab=repositories"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=enriquemdev&amp;layout=compact&amp;theme=github_dark&amp;hide_border=true&amp;langs_count=8&amp;title_color=7EE787&amp;text_color=C9D1D9&amp;bg_color=0D1117" alt="Distribución de lenguajes en repositorios públicos" width="360" /></a>
</p>

<sub>Distribución de lenguajes en mis repositorios públicos.</sub>

---

### Conectemos

Me interesa construir soluciones que conecten **IA, automatización e ingeniería de software** con necesidades reales del negocio.

[LinkedIn](https://www.linkedin.com/in/enrique-mu%C3%B1oz-aa6345267/) · [enriquemunozdev@gmail.com](mailto:enriquemunozdev@gmail.com)
