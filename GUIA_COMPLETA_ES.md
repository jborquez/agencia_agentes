# 🎭 La Agencia: Guía Completa en Español

## 📖 Tabla de Contenidos
1. [¿Qué es La Agencia?](#qué-es-la-agencia)
2. [Cómo Funciona](#cómo-funciona)
3. [Instalación y Configuración](#instalación-y-configuración)
4. [Cómo Empezar a Usarlo](#cómo-empezar-a-usarlo)
5. [Ejemplos Prácticos](#ejemplos-prácticos)
6. [Categorías de Agentes](#categorías-de-agentes)
7. [Preguntas Frecuentes](#preguntas-frecuentes)

---

## ¿Qué es La Agencia?

**"The Agency"** es una colección de más de 100 **personajes de agentes IA especializados**, cada uno diseñado para ser un experto en su dominio. 

Piénsalo como si tuvieras un **equipo de trabajo completo**:
- 👨‍💻 Desarrolladores frontend y backend
- 🎨 Diseñadores UI/UX
- 📱 Desarrolladores mobile
- 💰 Especialistas en ventas y marketing
- 🛡️ Ingenieros de seguridad
- 📊 Analistas de datos
- ...y mucho más

Cada agente tiene:
✅ **Personalidad única** - Voz, estilo y enfoque propios
✅ **Especialización profunda** - No son prompts genéricos
✅ **Procesos comprobados** - Flujos de trabajo reales
✅ **Resultados tangibles** - Código, documentos, estrategias

---

## Cómo Funciona

### El Concepto Básico

Cada agente es un **archivo Markdown (.md)** que contiene:

```
┌─────────────────────────────────────┐
│    PERFIL DEL AGENTE (Agent Name)   │
├─────────────────────────────────────┤
│ 🎯 Misión Principal                 │
│ 💼 Áreas de Especialidad            │
│ 📋 Procesos de Trabajo              │
│ 🔧 Herramientas Usadas              │
│ 📊 Métricas de Éxito                │
│ 💬 Estilo de Comunicación           │
│ 📝 Ejemplos Prácticos               │
└─────────────────────────────────────┘
```

### Cómo Usarlos

**Opción 1: Con Claude (Recommended) 🏆**
```
1. Accede a Claude.ai
2. Copia el contenido de un agente (ej: engineering-frontend-developer.md)
3. Pégalo en tu conversación
4. Claude adoptará ese rol automáticamente
```

**Opción 2: Con GitHub Copilot**
```
1. Instala la extensión de Copilot en VS Code
2. Los agentes se pueden usar como instrucciones personalizadas
3. Activa el agente que necesites
```

**Opción 3: Como Referencia**
```
1. Lee los archivos de los agentes
2. Copia y adapta el que necesites
3. Úsalo como guía en tu herramienta favorita
```

---

## Instalación y Configuración

### Requisitos Previos
- ✅ Git instalado
- ✅ Acceso a una IA (Claude, ChatGPT, GitHub Copilot, etc.)
- ✅ Básicamente eso

### Paso 1: El Repositorio ya está Clonado ✓

Como ya clonaste el repositorio, tienes todos los archivos localmente en:
```
/home/jborquez/Documentos/agencia_ti/agency-agents/
```

### Paso 2: Estructura del Proyecto

```
agency-agents/
├── engineering/           # Agentes de desarrollo
│   ├── frontend-developer.md
│   ├── backend-architect.md
│   ├── mobile-app-builder.md
│   ├── ai-engineer.md
│   └── ... (26+ más)
├── design/               # Agentes de diseño
│   ├── ui-designer.md
│   ├── ux-researcher.md
│   └── ... (8+)
├── marketing/            # Agentes de marketing
│   ├── content-creator.md
│   ├── growth-hacker.md
│   └── ... (25+)
├── sales/               # Agentes de ventas
│   └── ... (9)
├── product/             # Agentes de producto
│   └── ... (7+)
├── support/             # Agentes de soporte
│   └── ... (5+)
├── project-management/  # Agentes de proyecto
│   └── ... (3+)
├── examples/            # Ejemplos de uso completo
│   └── nexus-spatial-discovery.md
└── scripts/             # Scripts de instalación
    ├── install.sh
    └── convert.sh
```

### Paso 3: Configuración Inicial (Opcional)

Para usar con Claude Code (recomendado):
```bash
cd /home/jborquez/Documentos/agencia_ti/agency-agents
./scripts/install.sh --tool claude-code
```

O manualmente, simplemente copia los archivos `.md` que necesites.

---

## Cómo Empezar a Usarlo

### Método 1: Usar Directamente en Claude 🌟 (MÁS FÁCIL)

**Paso 1: Elige un Agente**
```
Necesito crear una página web con React
→ Usa: engineering-frontend-developer.md
```

**Paso 2: Copia el Contenido**
```bash
# Accede a tu agente favorito
cat /home/jborquez/Documentos/agencia_ti/agency-agents/engineering/engineering-frontend-developer.md
# Copia el contenido completo
```

**Paso 3: Pégalo en Claude**
1. Ve a claude.ai
2. Abre una nueva conversación
3. Pega el contenido del agente
4. Añade tu solicitud específica

**Ejemplo:**
```
[Aquí pegas el contenido del agente Frontend Developer]

Ahora, ayúdame a crear un componente React para un carrito de compras
con las siguientes características:
- Agregar/remover productos
- Calcular total
- Persistir en localStorage
```

---

### Método 2: Con GitHub Copilot

**En VS Code:**
```
1. Abre la paleta de comandos: Ctrl+Shift+P
2. Busca "Copilot: Edit Prompt"
3. Pega el contenido del agente
4. Usa Copilot normalmente
```

---

### Método 3: Crear tu Propio Agente Personalizado

Basándote en la estructura, puedes crear tu propio agente:

```markdown
# 🚀 Mi Agente Personalizado

## 🎯 Misión Principal
Describe qué hace este agente

## 💼 Especialidades
- Especialidad 1
- Especialidad 2

## 📋 Flujo de Trabajo
1. Paso 1
2. Paso 2
3. Paso 3

## 🔧 Herramientas
- Herramienta 1
- Herramienta 2

## 📊 Métricas de Éxito
- Métrica 1
- Métrica 2

## 💬 Estilo de Comunicación
Describe cómo se comunica este agente

## 📝 Ejemplos
```code
Ejemplos prácticos
```
```

---

## Ejemplos Prácticos

### Ejemplo 1: Crear una API REST Completa 🔧

**Objetivo:** Crear un API REST para una tienda en línea

**Agentes a Usar:**
- Backend Architect (diseño)
- Security Engineer (seguridad)
- Database Optimizer (base de datos)

**Pasos:**

1. **Copia el Backend Architect**
```bash
cat /home/jborquez/Documentos/agencia_ti/agency-agents/engineering/engineering-backend-architect.md
```

2. **Usa en Claude con tu solicitud:**
```
[Backend Architect prompt aquí]

Necesito que diseñes una API REST completa para una tienda en línea que:
- Gestione productos (CRUD)
- Tenga autenticación JWT
- Implemente carrito de compras
- Procese pagos
- Envíe notificaciones por email

Por favor, proporciona:
1. Arquitectura completa
2. Esquema de base de datos
3. Endpoints principales
4. Código base en Node.js + Express
```

3. **Complementa con Security Engineer**
```
[Security Engineer prompt aquí]

Ahora revisa el API anterior y asegúrate de que:
- Está protegido contra inyección SQL
- Valida entrada de usuarios
- Implementa rate limiting
- Tiene autenticación segura
```

---

### Ejemplo 2: Crear una Página Web Moderna 🎨

**Objetivo:** Landing page para un producto SaaS

**Agentes a Usar:**
- UI Designer (interfaz)
- UX Researcher (experiencia)
- Frontend Developer (código)

**Proceso:**

```markdown
## Paso 1: Research con UX Researcher
[Pega UX Researcher prompt]
Crea personas de usuario y journey maps para un SaaS de gestión de tareas

## Paso 2: Diseño con UI Designer
[Pega UI Designer prompt]
Basándote en el research anterior, crea el diseño de:
- Hero section
- Features section
- Pricing table
- Call-to-action buttons

## Paso 3: Desarrollo con Frontend Developer
[Pega Frontend Developer prompt]
Convierte el diseño anterior en código React:
- Componentes reutilizables
- Responsive design
- Optimización de performance
- SEO basics
```

**Resultado:** Una landing page completa, bien diseñada y optimizada.

---

### Ejemplo 3: Estrategia de Marketing Completa 📊

**Objetivo:** Lanzar un producto nuevo

**Agentes a Usar:**
- Growth Hacker
- Content Creator
- Social Media Strategist
- Trend Researcher

**Ejecución:**

1. **Trend Researcher:** Identifica el mercado
```
[Pega Trend Researcher prompt]

Analiza el mercado de herramientas de productividad:
- Competencia actual
- Tendencias emergentes
- Gaps en el mercado
- Oportunidades
```

2. **Growth Hacker:** Estrategia de crecimiento
```
[Pega Growth Hacker prompt]

Basándote en el análisis anterior, crea un plan de lanzamiento que:
- Genere buzz inicial
- Adquiera primeros 1000 usuarios
- Logre virality
- Proponga loops de crecimiento
```

3. **Content Creator:** Contenidos de marketing
```
[Pega Content Creator prompt]

Crea un calendário de contenidos para 4 semanas:
- Blog posts
- Social media
- Email sequences
- Landing page copy
```

---

### Ejemplo 4: Code Review y Mejora 👁️

**Objetivo:** Revisar y mejorar código existente

**Agentes a Usar:**
- Code Reviewer
- Security Engineer
- Senior Developer

**Cómo hacerlo:**

```bash
# 1. Obtén tu código a revisar
cat tu-archivo.py > codigo_a_revisar.txt

# 2. En Claude, usa este prompt:
[Pega Code Reviewer prompt]

Aquí está mi código Python para [descripción]:
[Pega tu código]

Por favor:
1. Revisa la calidad del código
2. Sugiere mejoras
3. Identifica problemas de seguridad
4. Propone refactorización

# 3. Luego usa Security Engineer
[Pega Security Engineer prompt]

Ahora enfócate en seguridad del código anterior:
- Vulnerabilidades
- Inyección de código
- Manejo de datos sensibles
```

---

### Ejemplo 5: Plan de Proyecto Completo 📅

**Objetivo:** Planificar el desarrollo de una aplicación móvil

**Agentes a Usar:**
- Project Shepherd
- Mobile App Builder
- Backend Architect
- Design UX Architect

**Proceso:**

```bash
# 1. Visión del Proyecto
[Pega Project Shepherd prompt]

Necesito un plan completo para desarrollar una app móvil de:
- Nombre: TaskMaster
- Plataforma: iOS + Android
- Características principales: tasks, subtasks, reminders, collaboration
- Timeline: 3 meses
- Equipo: 4 desarrolladores

Por favor proporciona:
1. Fases del proyecto (sprints)
2. Hitos importantes
3. Riesgos identificados
4. Timeline detallado

# 2. Arquitectura Técnica
[Pega Backend Architect prompt]

Basándote en el plan anterior, diseña la arquitectura técnica:
- Cómo se comunican frontend y backend
- Modelo de base de datos
- Autenticación
- Sincronización en tiempo real

# 3. Interfaz de Usuario
[Pega Design UX Architect prompt]

Basándote en el plan y la arquitectura, diseña:
- Estructura de pantallas
- Flujos de usuario
- Componentes principales
```

---

## Categorías de Agentes

### 💻 División de Ingeniería (Engineering)

| Agente | Especialidad | Cuándo Usar |
|--------|--------------|------------|
| **Frontend Developer** | React, Vue, Angular, UI | Aplicaciones web modernas |
| **Backend Architect** | APIs, bases de datos, escalabilidad | Sistemas servidor |
| **Mobile App Builder** | iOS, Android, React Native | Aplicaciones móviles |
| **AI Engineer** | Machine Learning, modelos, IA | Características IA |
| **DevOps Automator** | CI/CD, infraestructura | Automatización y deploy |
| **Security Engineer** | Seguridad, vulnerabilidades | Code review de seguridad |
| **Database Optimizer** | SQL, indexing, queries | Optimizar bases de datos |
| **Software Architect** | Diseño de sistemas, DDD | Decisiones arquitectónicas |
| **Technical Writer** | Documentación, tutoriales | Escribir documentación |

### 🎨 División de Diseño (Design)

| Agente | Especialidad | Cuándo Usar |
|--------|--------------|------------|
| **UI Designer** | Interfaz, componentes | Crear interfaces |
| **UX Researcher** | Testing, análisis de usuarios | Entender a usuarios |
| **UX Architect** | Arquitectura de experiencia | Diseñar experiencia |
| **Brand Guardian** | Identidad, consistencia | Estrategia de marca |
| **Whimsy Injector** | Personalidad, detalles | Añadir "magia" a UI |

### 💰 División de Ventas (Sales)

| Agente | Especialidad | Cuándo Usar |
|--------|--------------|------------|
| **Outbound Strategist** | Prospecting, sequences | Generar pipeline |
| **Discovery Coach** | Calls, qualification | Preparar discovery calls |
| **Deal Strategist** | MEDDPICC, ganadores | Cerrar deals |
| **Sales Engineer** | Demos técnicas, POCs | Presentaciones técnicas |
| **Proposal Strategist** | RFPs, narrativas | Escribir propuestas |

### 📢 División de Marketing (Marketing)

| Agente | Especialidad | Cuándo Usar |
|--------|--------------|------------|
| **Growth Hacker** | Adquisición, viral loops | Crecimiento rápido |
| **Content Creator** | Blogs, redes, copy | Crear contenido |
| **SEO Specialist** | Posicionamiento en buscadores | Tráfico orgánico |
| **Social Media Strategist** | Estrategia multi-plataforma | Redes sociales |
| **Reddit Community Builder** | Comunidad authentica | Engagement en Reddit |

### 📊 División de Producto (Product)

| Agente | Especialidad | Cuándo Usar |
|--------|--------------|------------|
| **Sprint Prioritizer** | Agile, priorización | Planificar sprints |
| **Trend Researcher** | Market research, competencia | Investigación de mercado |
| **Product Manager** | Estrategia, roadmap | Dirección del producto |

---

## Preguntas Frecuentes

### ¿Necesito pagar por usarlo?
**No.** Los archivos son código abierto (MIT License). Solo necesitas acceso a una IA como Claude.

### ¿Cómo puedo contribuir?
```bash
cd /home/jborquez/Documentos/agencia_ti/agency-agents
git checkout -b mi-nuevo-agente
# Crea tu archivo: agentes-tu-especialidad.md
git add .
git commit -m "Agrega nuevo agente: [nombre]"
git push origin mi-nuevo-agente
# Abre un PR en GitHub
```

### ¿Funcionan los agentes juntos?
**Sí.** Puedes usar múltiples agentes en la misma conversación. Claude entenderá todos los roles.

Ejemplo:
```
[Pega Frontend Developer prompt]

[Pega Backend Architect prompt]

Ahora trabajen juntos para crear una aplicación de [descripción]
```

### ¿Puedo personalizar un agente?
**Claro.** Copia el contenido, modifica lo que necesites. Son archivos Markdown simples.

### ¿Qué pasa si no me gusta un agente?
Prueba otro. Hay 100+ especialistas diferentes. Lo importante es encontrar el que funcione mejor para tu tarea.

### ¿Necesito internet?
Para usar con Claude.ai sí. Si usas localmente con una IA offline, depende del modelo que uses.

---

## 🚀 Próximos Pasos

1. **Explora los agentes:** Navega por `/agency-agents/` 
2. **Elige uno:** Pick un agente relacionado a tu tarea
3. **Copia y pega:** En Claude.ai
4. **Pide algo específico:** Sé claro en qué necesitas ayuda
5. **Itera:** Refina según los resultados

---

## 📚 Recursos Adicionales

- **Repositorio Original:** https://github.com/msitarzewski/agency-agents
- **Ejemplos Avanzados:** Ver `/agency-agents/examples/`
- **Licencia:** MIT (puedes usar libremente)

---

## 💡 Consejo Final

La verdadera magia ocurre cuando:
1. **Combinas múltiples agentes** en una conversación
2. **Les das contexto real** de tu proyecto
3. **Iteras y refinas** los resultados
4. **Personalizas** según tus necesidades

**¡Empieza ahora!** Elige un agente, abre Claude.ai, y comienza. 🎯

---

*Documentación creada: 7 de mayo de 2026*
*Proyecto: The Agency Agents*
*Traducción y adaptación: Guía Completa en Español*
