# 🚀 SaaS Lab – Experimentos, MVPs y Productos con IA

Este monorepo contiene todos mis experimentos, MVPs y productos SaaS orientados a:
- Generación de múltiples fuentes de ingreso  
- Construcción de herramientas impulsadas por IA  
- Proyectos reales utilizando agentes, LLMs, RAG y LangGraph  
- Desarrollo serverless con AWS/GCP  
- Prototipos para founders y empresas  

Es mi **laboratorio oficial** para iterar, aprender, validar y lanzar productos.

---

## 📦 Estructura del Monorepo

/saas-lab  
  /apps  
    /web → Frontend (React / Next.js / Vite)  
    /api → Backend (FastAPI o NestJS)  
    /agents → Agentes LangGraph / MCP / RAG  
  /infrastructure  
    /scripts → DevOps, deploys, seeds  
  /docs → Arquitectura, diagramas, decisiones técnicas

---

## 🌟 Proyectos principales

### 1) LLM SEO / GEO Auditor (MVP 1)

Sistema para analizar la visibilidad de marcas en respuestas generadas por modelos de IA.

Incluye:
- Crawling de sitios  
- Generación de prompts estratégicos  
- Sistema RAG para análisis  
- Gap analysis y recomendaciones  
- UI para reportes  

**Estado:** En planificación – Sprint 1

---

### 2) Agente Bulk Ops (Inspired by Ads Automation)

Agente autónomo basado en LangGraph que:
- Recibe instrucciones complejas  
- Valida entradas  
- Ejecuta acciones masivas  
- Produce reportes estructurados  
- Reintenta fallos transitorios  

**Estado:** En desarrollo

---

### 3) MCP Server – SaaS Integrations

Servidor MCP con herramientas para:
- Consultar data  
- Ejecutar análisis  
- Generar reportes  
- Integrarse con APIs externas y bases de datos  

**Estado:** Alpha

---

## 🧰 Tecnologías principales

### Backend
- FastAPI o NestJS  
- PostgreSQL / DynamoDB  
- Redis  
- SQS / PubSub  
- OpenTelemetry  
- LangGraph / MCP  
- Python y Node.js  

### Frontend
- React (Vite o Next.js)  
- Zustand / Jotai  
- shadcnUI  
- TailwindCSS  
- Playwright (e2e)  

### Infra
- AWS (Lambda, API Gateway, DynamoDB, S3, CloudWatch)  
- GCP Cloud Run / PubSub  
- GitHub Actions para CI/CD  
- Terraform o CDK (opcional)  

---

## ▶️ Cómo correr el proyecto

Instalar dependencias:
pnpm install

Correr el frontend:
pnpm --filter web dev

Correr el backend:
pnpm --filter api dev

Correr agentes (LangGraph):
pnpm --filter agents dev

---

## 📚 Documentación

- /docs/architecture – Diagramas y decisiones  
- /docs/roadmap – Backlog y planificación  
- /docs/agents – Especificaciones de agentes  

---

## 🗺️ Roadmap (3 sprints)

### Sprint 1 — Foundations
- Estructura del monorepo  
- Endpoints base en API  
- Bootstrap del sistema RAG  
- UI inicial  
- Agente base (LangGraph)  

### Sprint 2 — LLM SEO Auditor
- Crawling  
- Entity extraction  
- Generación de prompts  
- Análisis + scoring  
- Dashboard básico  

### Sprint 3 — Producto & Integración
- Reportes  
- Export PDF  
- RAG avanzado  
- Pricing page  
- Demo pública  

---

## 📈 Objetivo del Repo

Convertir ideas en **SaaS reales**, aprender rápido y generar nuevas fuentes de ingreso.  
Cada archivo aquí es una posible feature, MVP o producto listo para ofrecer.

---

## 👤 Author

**Mizael Paredes**  
Software Engineer — IA, Frontend, Backend, Agents
