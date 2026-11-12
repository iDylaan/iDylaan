<!-- GitHub Profile Header -->
<div align="center">

# 👋 Daniel Chaparro Marín

### **Full Stack Developer | Backend Developer | Data Engineer**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/daniel-chaparro-marin/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/iDylaan)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:daniel.marin92@hotmail.com)

---

</div>

## 🎯 Acerca de Mí

Ingeniero en Gestión y Desarrollo de Software con **3+ años de experiencia profesional** en arquitectura de sistemas, desarrollo full stack y data engineering. Apasionado por resolver problemas complejos a través de la tecnología y mejorar procesos operativos. Destaco por:

- 🏆 **Liderazgo técnico**: Desarrollo de proyectos end-to-end con impacto medible
- ⚙️ **Optimización**: Reducción de tiempos de procesamiento (600ms → 200ms) y automatización de flujos operativos
- 🤖 **IA/ML**: *Fine-tuning* de modelos de IA con datasets de 20GB+
- 🔄 **Escalabilidad**: Migración de monolitos a microservicios manejando millones de registros

---

## 💼 Experiencia Profesional

### **GNerd — Senior Software Engineer** `Abril 2024 - Enero 2026`

#### Proyecto Principal: **G Cobros** (CRM con Cobro y Facturación Automática)
- 🎯 **Rol**: Desarrollador Full Stack único del proyecto
- 📊 **Escala**: ~113 customers | ~50,000 licencias Google Workspace | $400K MXN+ procesados mensualmente

**Impacto (Resultados Cuantificados):**
- ⏱️ Ciclo de facturación: **1 semana → <1 día** (-80-90% tiempo operativo)
- 💰 Flujo de caja: Eliminó desfase mensual (el partner pagaba con retraso; ahora los customers pagan adelantado)
- 🔄 Automatización: Cobro en suscripción mensual sin intervención manual

**Stack Técnico:**
- **Frontend**: React + Material Design
- **Backend**: Node.js | REST API
- **Base de datos**: PostgreSQL
- **Pagos**: Stripe (Google Pay, múltiples métodos)
- **Facturación**: API Doc Digitales (automatizada)
- **Infraestructura**: GCP (Cloud Run, Compute Engine, Cloud SQL)
- **Autenticación**: SSO Google
- **CI/CD**: Cloud Run pipelines

---

### **Secretaría de Hacienda y Crédito Público (SHCP)** `Enero 2023 - Actualidad`

#### 🔹 **SAMADI** — Sistema de Administración y Monitoreo de Datos e Información

**Rol**: Desarrollador y Arquitecto | Rediseño y Modernización

**Problema Original:**
- Monolito con monitoreo lento (600ms de latencia)
- ~15 incidencias/semana
- Escalabilidad limitada para nuevos usuarios

**Solución:**
- ✅ Migración a **Microservicios** (Docker + Docker Compose)
- ✅ API Gateway con **NGINX** (validación y enrutamiento)
- ✅ Estado en tiempo real con **Redis** (Pub/Sub)
- ✅ Frontend SPA con **Vue.js 3 + Pinia**
- ✅ Comunicación real-time con **Server-Sent Events (SSE)**
- ✅ Sistema de permisos escalables (grafo en JSON)
- ✅ Servidor de repositorios con **Samba**

**Resultados Medibles:**
- ⚡ Latencia: **600ms → 200ms** (-66%)
- 🐛 Incidencias: **~15/semana → ~4/semana** (-73%)
- 📈 Volumen monitoreado: **200K → 5M registros** (archivos hasta 30M registros)
- 🌍 Habilitó exposición a usuarios externos

---

#### 🔹 **ORBIT** — Orquestador de Repositorios y Bases para la Ingesta Tabular

**Rol**: Desarrollador End-to-End (diseño, backend, despliegue) | Proyecto en solitario

- API con **FastAPI** (Python) + **Polars** y **pandas**
- Validación automática de datasets antes de carga
- **Impacto**: Redujo ~90% las incidencias de cargas/ETL del equipo BI

---

#### 🔹 **SAISD** — Sistema de Administración de Instrumentos del Seguimiento del Desempeño

**Rol**: Desarrollador Full Stack único | Negociación directa con stakeholders

**Escala:**
- ~6,348 usuarios/dependencias
- ~9,642 solicitudes anuales

**Problema Original:**
- Evaluación manual de solicitudes con Excel (hasta >1 mes por solicitud)
- Revisión campo por campo de métricas entrelazadas complejas

**Solución:**
- **Frontend**: Vue.js 3 + Pinia
- **Backend**: Flask + Pydantic
- **BD**: PostgreSQL + réplicas Oracle
- **Modelado flexible**: JSON para adaptabilidad
- **Detección automática**: Solo muestra cambios detectados (no revisa todo)

**Resultados Medibles:**
- 📊 Tiempo de revisión: **>1 mes → ≤7 días** (-85%)
- ⏱️ Revisión por solicitud: **hasta 1 semana → ~6 horas** (-85%)

---

#### 🔹 **iTop** — Gestor de Tickets de Mesa Integral de Soluciones (MIS)

**Rol**: Mantenimiento, Migración Tecnológica y Soporte

- Migración **iTop 2.7 → 3.2** (sin downtime perceptible para usuarios)
- **9 integraciones** con APIs de proveedores (Mainbit, Bestel, Theos, NOVANDI, Hol4)
- Procesamiento de **~2,600-2,800 tickets/mes**
- Desarrollo de interfaces nativas: cierres masivos, encuestas de satisfacción

---

#### 🔹 **Servidor SAS & Gobernanza de Datos**

**Responsabilidades:**
- Monitoreo de servicios SAS con **auto-recuperación automática**
- Análisis de logs (inicios de sesión, mapas de calor de usuarios)
- Gobernanza de datasets (hasta 96 TB)
- Cronjobs con notificaciones automáticas

**Impacto:**
- 🎯 **0 incidencias en 7+ meses** (vs. intervenciones frecuentes en fines de semana/madrugadas)

---

### **Proyecto Académico Destacado: "Kenai"** `2024`

#### Chatbot Conversacional para Práctica de Inglés Coloquial

**Logro**: 🥈 **2.º lugar en Expo de Proyectos (Exproy 2024)**

**Equipo**: 4 personas | **Rol**: Líder técnico y desarrollador principal

**Stack Técnico:**
- **Frontend**: Vue.js 3
- **Backend/IA**: Python con **LangChain**, **PyTorch**, **NumPy**
- **Modelo**: *Fine-tuning* de **Gemma** (20GB de datos conversacionales, ~2 días de entrenamiento)
- **Despliegue**: **OCI (Oracle Cloud Infrastructure)** (configuración y despliegue por Daniel)

**Propuesta de Valor:**
- Interacción tipo "amigo" (no formal)
- Enseñanza de slang, acrónimos y phrasal verbs
- Explicaciones contextuales automáticas

**Impacto Comercial:**
- ✅ Vendido a la academia
- ✅ Propuesta del grupo Comercial Mexicana

---

## 🛠️ Stack Tecnológico

<table>
<tr>
<td>
<b>Lenguajes</b><br/>
Python · JavaScript/TypeScript · PHP · Java · Dart · SQL
</td>
<td>
<b>Frontend</b><br/>
React · Vue.js 3 · PrimeVue v4 · Pinia · Material Design · HTML/CSS · SPA/PWA
</td>
</tr>
<tr>
<td>
<b>Backend</b><br/>
Node.js · FastAPI · Flask · Django · Spring Boot
</td>
<td>
<b>Bases de Datos</b><br/>
PostgreSQL · Oracle · SQL Server · Redis · MongoDB
</td>
</tr>
<tr>
<td>
<b>IA/ML</b><br/>
Fine-tuning (Gemma, Llama) · LangChain · PyTorch · NumPy
</td>
<td>
<b>Infraestructura</b><br/>
Docker · Docker Compose · NGINX · GCP · OCI · Apache
</td>
</tr>
<tr>
<td>
<b>Datos/Análisis</b><br/>
pandas · Polars · SAS · ETL · SSIS
</td>
<td>
<b>DevOps/Herramientas</b><br/>
Git · GitHub (PRs, Code Review) · CI/CD · Directorio Activo
</td>
</tr>
</table>

---

## 🎓 Certificaciones

### 🖥️ Frontend
- **Certified Mid-Level Vue.js Developer** — Certificates.dev (Ago. 2025)

### ☁️ Cloud & AI
- **AWS Academy Graduate** — Cloud Foundations, Intro to Cloud Semester 1 & 2 (2023-2024)
- **Google Cloud Contact Center AI (CCAI)** (Mayo 2024)
  - 8 Skill Badges completadas (Vertex AI, Dialogflow CX, CCAI Platform, etc.)

---

## 🎯 Logros Cuantificados

| Proyecto | Métrica | Impacto |
|----------|---------|--------|
| **G Cobros** | Ciclo de facturación | 1 semana → <1 día (-80%) |
| **G Cobros** | Licencias manejadas | ~50,000 licencias Google Workspace |
| **SAMADI** | Latencia de respuesta | 600ms → 200ms (-66%) |
| **SAMADI** | Incidencias semanales | ~15 → ~4 (-73%) |
| **SAMADI** | Volumen de datos | 200K → 5M registros |
| **ORBIT** | Reducción de incidencias | -90% en cargas/ETL |
| **SAISD** | Tiempo de solicitud | >1 mes → ≤7 días |
| **SAISD** | Usuarios impactados | ~6,348 usuarios |
| **SAISD** | Solicitudes anuales | ~9,642 solicitudes |
| **SAS** | Incidencias críticas | 0 en 7+ meses |
| **iTop** | Volumen de tickets | ~2,600-2,800 tickets/mes |
| **Kenai** | Posición en expo | 🥈 2.º lugar |

---

## 🤝 Habilidades Blandas & Perfil

- 🎯 **Ownership**: Proyectos end-to-end (diseño, desarrollo, despliegue) en solitario (SAISD, ORBIT)
- 💬 **Comunicación**: Negociación directa con stakeholders y traducción de necesidades a requerimientos técnicos
- ⚙️ **Mejora Continua**: Enfoque obsesivo en optimización y automatización de procesos
- 🧠 **Curiosidad Técnica**: Pasión por aprender y experimentar con tecnologías emergentes
- 👥 **Trabajo en Equipo**: Experiencia en esports competitivos; campeón LMV 2019
- 📊 **Metodologías Ágiles**: Scrum, Kanban, DAST (extensión de Scrum de SHCP)

---

## 📚 Formación Académica

- **Ingeniería en Gestión y Desarrollo de Software** — UTN (Sep. 2023 - Abr. 2024)
- **Técnico en Desarrollo de Software Multiplataforma** — UTN (2021 - 2023)

### Tecnologías Académicas
API, SPA/PWA, Monolitos, Microservicios, Spring Boot, React, Vue.js, Flutter, HTML/CSS/JavaScript

---

## 📞 Contacto

<div align="center">

| Medio | Enlace |
|-------|--------|
| 💼 **LinkedIn** | [daniel-chaparro-marin](https://www.linkedin.com/in/daniel-chaparro-marin/) |
| 💻 **GitHub** | [@iDylaan](https://github.com/iDylaan) |
| 📧 **Email** | daniel.marin92@hotmail.com |
| 📱 **Teléfono** | +52 55 2766 6122 |
| 🌍 **Idiomas** | Inglés B1 (Conversacional) |

</div>

---

<div align="center">

### ✨ Enfoque Profesional

**Full Stack Developer** · **Backend Developer** · **Data Engineer**

*Especializado en arquitectura escalable, optimización de procesos y soluciones data-driven*

</div>
