<h1 align="center">👋 Hola, soy José Miguel Aristía Gordillo</h1>

<h3 align="center">
  Desarrollador Flutter Senior · Inteligencia Artificial · Firebase<br/>
  Construyendo productos digitales escalables, centrados en el usuario y de alto rendimiento.
</h3>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=waterproof82&label=Visitas%20al%20perfil&color=1F4E79&style=flat" alt="waterproof82" />
</p>

---

## 🚀 Sobre mí

- 🏢 Actualmente trabajando en **entornos educativos del Gobierno de Canarias** con Flutter multiplataforma
- 🤖 **Experto en Desarrollo con Inteligencia Artificial** — Doble certificación BIG school + Universidad Isabel I (2025)
- 📱 +5 años de experiencia desarrollando apps **Flutter** para iOS, Android y Web
- 🔬 Especialista en integración de **LLMs, RAG Systems, APIs de IA** (OpenAI, Anthropic, ElevenLabs, Gemini)
- 🏗️ Creador y CTO de múltiples productos SaaS propios en producción
- 💻 Todos mis proyectos disponibles en [github.com/Waterproof82](https://github.com/Waterproof82)
- 📫 Contacto: **aristiagordillo@gmail.com**

---

## 🤖 Inteligencia Artificial & LLMs

Certificado como **Experto en Desarrollo con Inteligencia Artificial** — Doble certificación: **Título Profesional de BIG school** + **Certificado de la Universidad Isabel I**, con experiencia práctica en:

| Área | Tecnologías |
|------|------------|
| Modelos de lenguaje | OpenAI GPT, Anthropic Claude, Google Gemini |
| Frameworks de IA | LangChain, LlamaIndex, Vercel AI SDK |
| Sistemas avanzados | RAG, Embeddings, pgvector, Fine-tuning, LLMOps |
| Herramientas de desarrollo | Cursor, Claude Code, GitHub Copilot, Gemini CLI |
| Automatización (WPS) | n8n, CodeRabbit, Figma AI, v0, Lovable |
| APIs de voz e IA | ElevenLabs, OpenAI Whisper |
| Infraestructura | Bases de datos vectoriales, Docker, CI/CD con IA |
| Seguridad IA | OWASP Top 10, EU AI Act, IA responsable |

---

## 📱 Flutter & Firebase — Stack Principal

Con más de 5 años de experiencia en **Flutter / Dart** desarrollando soluciones multiplataforma:

- ✅ Arquitectura limpia: **Clean Architecture**, **MVVM**, separación de capas
- ✅ State Management: **BLoC**, **Provider**, **Riverpod**, **GetX**
- ✅ Firebase: Auth, Firestore, Realtime DB, Storage, Cloud Functions, Push Notifications
- ✅ Testing: Unit testing, Widget testing, TDD con IA
- ✅ Publicación en **App Store**, **Google Play** y despliegue **Web**
- ✅ Integración de APIs REST, GraphQL y consumo de servicios backend

---

## 🏆 Proyectos Destacados

---

### 🤖 SmartConnect AI – Business Accelerator
> Proyecto Final de Máster en Desarrollo con IA · Acceso Público

Plataforma orientada a la captación y conversión de clientes que integra **Inteligencia Artificial**, **automatización de procesos (WPS)** y una arquitectura escalable en la nube.

**🧠 IA aplicada — RAG + Generativa**
- Chatbot basado en arquitectura **RAG** (Retrieval-Augmented Generation)
- Convierte consultas en **embeddings vectoriales** y realiza búsqueda semántica en PostgreSQL (**pgvector**)
- Genera respuestas con **Gemini** usando únicamente contexto relevante del negocio
- Respuestas precisas, contextualizadas y alineadas con el conocimiento del negocio

**⚙️ Automatización inteligente — WPS con n8n**
- Recibe leads desde formularios o eventos externos
- Analiza automáticamente cada entrada con IA (intención, valor, prioridad)
- Activa flujos automatizados: notificaciones, emails, almacenamiento en base de datos
- Automatización completa del ciclo de captación y gestión de clientes

**🗄️ Backend — Supabase (PostgreSQL)**
- Base de datos relacional + vectorial (**pgvector**)
- Seguridad mediante **Row Level Security (RLS)**
- **Edge Functions** para lógica serverless e integración con IA

**🏗️ Arquitectura & Stack**

| Capa | Tecnologías |
|------|------------|
| Frontend | React · TypeScript · Vite · Tailwind CSS |
| Backend | Supabase (PostgreSQL + pgvector + Edge Functions) |
| Inteligencia Artificial | Gemini (embeddings + generación) |
| Automatización | n8n (WPS) |
| Testing & CI/CD | Jest · GitHub Actions · Vercel |

> Diseñado bajo **Clean Architecture** y principios **SOLID**, garantizando escalabilidad, mantenibilidad y separación clara de responsabilidades.

---

### 🛒 Carta Digital Multi-idioma — SaaS Ecommerce
> Plataforma multi-tenant de menú digital con pedidos online, panel de administración y campañas por email

Sistema SaaS completo con soporte multi-tenant, seguridad de nivel empresarial e internacionalización en 5 idiomas.

**🌐 Funcionalidades principales**
- Menú digital QR multi-idioma (es/en/fr/it/de) con carrito de compra
- Panel de administración completo: productos, categorías, pedidos, clientes, promociones
- Sistema de descuento de bienvenida con código único y validación server-side
- Campañas de email (Brevo) con gestión de suscripciones GDPR/CAN-SPAM
- Integración **Too Good To Go** — campañas, reservas, cupones y gestión de horarios
- Panel **Super Admin** para gestión centralizada de múltiples empresas

**🔒 Seguridad de nivel empresarial**
- JWT HS256 en cookie HttpOnly + revocación en Redis (fail-closed)
- CSRF con HMAC-SHA256 y `timingSafeEqual`
- CSP dinámico con nonce criptográfico por request
- Rate limiting Upstash Redis (fail-closed en login)
- RBAC, RLS, mínimo privilegio, anti-enumeración
- Validación de precios server-side (anti-tampering), OWASP Top 10

**🏗️ Arquitectura & Stack**

| Capa | Tecnologías |
|------|------------|
| Framework | Next.js 16 (Turbopack) · React 19 · TypeScript |
| Base de datos | Supabase (PostgreSQL) · Upstash Redis |
| Storage | Cloudflare R2 |
| Estilos | Tailwind CSS 4.x |
| Auth & Seguridad | JWT (jose) · CSRF HMAC · CSP Nonce |
| Email | Brevo |
| Arquitectura | Clean Architecture · SOLID · MVVM |

> Multi-tenant con aislamiento completo por `empresaId`, soporte de subdominios (`pedidos.dominio.com`) y dominios propios.

---

### 📲 QR iBar — Plataforma SaaS de Carta Digital Inteligente
> En producción con clientes reales desde 2021 · Evolución continua

Plataforma SaaS completa de **carta digital multiusuario e interactiva**, diseñada para optimizar la operativa de restaurantes mediante automatización, tiempo real y enfoque en conversión.

**⚡ Core del sistema**
- Carta digital QR autogestionable (productos, categorías, salas y mesas)
- Pedidos en tiempo real enviados directamente a **Barra y Cocina**
- Sistema multiusuario con interacción simultánea por mesa o grupo
- Historial completo de pedidos y control de usuarios conectados

**🚀 Optimización operativa**
- Eliminación de tiempos de espera del cliente
- Incremento del ticket medio mediante pedidos autónomos
- Interconexión de múltiples dispositivos en cocina/barra
- Flujo de pedidos totalmente automatizado sin intervención del camarero

**💰 Sistema de cobro & experiencia**
- Compatible con cualquier sistema de caja (POS)
- Envío de tickets y facturas por email (paperless)
- Mejora de propinas mediante experiencia digital optimizada

**📢 Motor de ventas integrado**
- Promoción dinámica de productos mediante:
  - Imágenes
  - Vídeos
  - Descripciones enriquecidas
- Activación/desactivación de productos en tiempo real
- Gestión de productos perecederos y campañas instantáneas

**📊 Analítica avanzada**
- Estadísticas de ventas
- Productos más vendidos
- Clientes frecuentes
- Pedidos procesados / cancelados
- Métricas clave para toma de decisiones

**🌐 Ecosistema extendido**
- Plataforma web para visibilidad de restaurantes
- Búsqueda por ubicación
- Pedidos para recoger o a domicilio

**📱 App complementaria**
- Notificaciones push (ofertas, menú del día, promociones)
- Guardado de favoritos y métodos de pago (1 clic)
- Historial de pedidos
- Pedidos remotos (sin estar en el local)
- Sistema de fidelización con descuentos

**🏗️ Stack tecnológico**
- Flutter (Web · iOS · Android)
- Firebase (Auth · Firestore · Realtime DB · Storage · Functions)
- Arquitectura MVVM + Clean Architecture

> Un sistema diseñado no solo para digitalizar la carta, sino para convertirla en una **herramienta activa de ventas y optimización operativa**.
---

## 🛠️ Tecnologías & Herramientas

### Mobile & Frontend
<p>
  <img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" alt="flutter" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/dartlang/dartlang-icon.svg" alt="dart" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original-wordmark.svg" alt="android" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/reactjs/reactjs-icon.svg" alt="react" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/>
</p>

### Cloud & Backend
<p>
  <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dot-net/dot-net-original-wordmark.svg" alt="dotnet" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/>
</p>

### Bases de Datos
<p>
  <img src="https://www.svgrepo.com/show/303229/microsoft-sql-server-logo.svg" alt="mssql" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/sqlite/sqlite-icon.svg" alt="sqlite" width="40" height="40"/>
</p>

### DevOps & Herramientas
<p>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/jenkins/jenkins-icon.svg" alt="jenkins" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/jestjsio/jestjsio-icon.svg" alt="jest" width="40" height="40"/>
</p>

---

## 🌐 Conecta conmigo

<p align="left">
  <a href="https://linkedin.com/in/jmaristia" target="_blank">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="jmaristia" height="30" width="40" />
  </a>
  &nbsp;
  <a href="https://github.com/Waterproof82" target="_blank">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/github.svg" alt="Waterproof82" height="30" width="40" />
  </a>
</p>

---

<p align="center">
  <em>Flutter · Dart · Firebase · Inteligencia Artificial · LLMs · RAG · pgvector · LangChain · n8n · Next.js · Supabase · Clean Architecture · MVVM · CI/CD · Docker · Prompt Engineering</em>
</p>
