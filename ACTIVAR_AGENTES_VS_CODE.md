# 🎭 Activando Agentes en VS Code

## Cómo Funcionará

Vamos a crear un sistema simple pero poderoso donde:

1. **Los agentes están disponibles como referencia** en tu proyecto
2. **Creas un archivo de trabajo** con las instrucciones del agent
3. **VS Code te ayuda siguiendo el rol** del agent
4. **Iteras sobre el resultado**

---

## 📋 Pasos Para Empezar

### Paso 1: Abre un Agent

Elige uno de estos comandos según qué necesites:

```bash
# Para crear código React
cat agency-agents/engineering/engineering-frontend-developer.md

# Para revisar seguridad
cat agency-agents/engineering/engineering-security-engineer.md

# Para planificar proyecto
cat agency-agents/project-management/project-shepherd.md

# O cualquier otro de:
ls agency-agents/engineering/
ls agency-agents/design/
ls agency-agents/marketing/
```

### Paso 2: Copia el contenido

El contenido del agent se ve así:

```markdown
# 🎨 Frontend Developer

Tu misión...
Tu especialidad...
Cómo trabajas...
Tu estilo...
```

**Cópialo completo** (Ctrl+A en el terminal o selecciona todo)

### Paso 3: Crea un Archivo de Trabajo

En VS Code, abre la Terminal integrada y haz:

```bash
# Crea una carpeta para tu trabajo
mkdir mi-proyecto-test
cd mi-proyecto-test

# Crea un archivo con el rol del agent
cat > AGENTE_ACTIVADO.md << 'EOF'
# 🎨 Frontend Developer

[Aquí pegas el contenido del agent]

---

## Mi Tarea Hoy

[Aquí escribes lo que necesitas]

EOF
```

### Paso 4: Abre el Archivo en VS Code

```bash
code AGENTE_ACTIVADO.md
```

### Paso 5: Pide a Copilot que Ayude

Usa Copilot (Ctrl+Shift+I) o escribe comentarios:

```javascript
// Necesito crear un componente React para un carrito de compras
// Que muestre productos, calcule total, persista en localStorage
// Usa TailwindCSS

// El agente Frontend Developer te ayudará
```

---

## 🔄 Workflow Completo

```
1. Terminal abierta aquí en VS Code
   ↓
2. Copia el agent que necesites
   ↓
3. Crea archivo AGENTE_ACTIVADO.md
   ↓
4. Abre en VS Code
   ↓
5. Describe tu tarea (en comentarios o markdown)
   ↓
6. Usa Copilot Chat (Ctrl+I)
   ↓
7. Pide: "Siguiendo al Frontend Developer, crea..."
   ↓
8. ¡Obtienes código/resultado!
```

---

## 📚 Ejemplos Rápidos

### Ejemplo 1: Crear un Componente React

**Archivo: `AGENTE_ACTIVADO.md`**
```markdown
# 🎨 Frontend Developer
[contenido del agent aquí]

---

## Mi Tarea
Crea un componente React de login con:
- Email y password
- Validación
- Error messages
- TailwindCSS
```

**En VS Code Terminal:**
```bash
# Presiona Ctrl+I (o Ctrl+Shift+I) para abrir Copilot Chat
# Escribe: "Soy el Frontend Developer. Crea el componente de arriba"
```

### Ejemplo 2: Revisar Código por Seguridad

**Archivo: `AGENTE_ACTIVADO.md`**
```markdown
# 🔒 Security Engineer
[contenido del agent aquí]

---

## Código a Revisar
[Tu código aquí]

## Mi Tarea
Revisa por vulnerabilidades, sugiere mejoras
```

### Ejemplo 3: Planificar un Proyecto

**Archivo: `AGENTE_ACTIVADO.md`**
```markdown
# 📅 Project Shepherd
[contenido del agent aquí]

---

## Mi Proyecto
Nombre: TaskMaster
Descripción: App de gestión de tareas
Timeline: 3 meses
Equipo: 2 developers

## Tarea
Crea un plan con sprints
```

---

## 🚀 Hazlo Ahora Mismo

Abre tu terminal integrada en VS Code y copia-pega esto:

```bash
# 1. Navega a tu carpeta de proyecto
cd /home/jborquez/Documentos/agencia_ti

# 2. Abre VS Code
code .

# 3. Abre la Terminal integrada (Ctrl+`)

# 4. Copia un agent
cat agency-agents/engineering/engineering-frontend-developer.md > AGENTE_FRONTEND.md

# 5. Abre el archivo
code AGENTE_FRONTEND.md

# 6. ¡Listo! Ya tienes el agent en VS Code
```

---

## 💡 Consejos Prácticos

### Organiza tu Trabajo

```
mi-proyecto/
├── AGENTE_ACTIVADO.md      (El agent que estás usando)
├── TAREA_ACTUAL.md         (Tu tarea/descripción)
├── CODIGO.js/py/jsx        (Tu código)
└── RESULTADOS.md           (Lo que creaste)
```

### Usa Comentarios para Comunicar

```javascript
// @AGENT: Frontend Developer
// TAREA: Crea un modal de confirmación
// REQUISITOS:
//   - Dos botones: Cancelar, Confirmar
//   - Animación suave
//   - TailwindCSS
//   - Accessible (a11y)

export function ConfirmModal({ title, onConfirm, onCancel }) {
  // Tu código aquí
}
```

### Combina Múltiples Agents

```markdown
# 🎨 Frontend Developer
[contenido]

---

# 🔒 Security Engineer  
[contenido]

---

## Tarea
Juntos, creen una página de login segura
```

---

## 🎯 Patrones Que Funcionan

### Patrón 1: Agent + Código
```
Abre: AGENTE_ACTIVADO.md
Escribe: Tu código
Usa Copilot: "Basándote en el agent, mejora esto"
```

### Patrón 2: Agent + Descripción
```
Abre: AGENTE_ACTIVADO.md
Escribe: Tu descripción de qué necesitas
Usa Copilot: "Crea exactamente esto"
```

### Patrón 3: Multiple Agents
```
Abre: AGENTES_MULTIPLES.md (con varios agents)
Escribre: Tu tarea grande
Usa Copilot: "Trabajen juntos para..."
```

---

## ⚡ Atajos Útiles en VS Code

| Atajo | Función |
|-------|---------|
| `Ctrl+`Backtick`` | Abre/cierra Terminal |
| `Ctrl+Shift+P` | Paleta de Comandos |
| `Ctrl+I` | Copilot Inline |
| `Ctrl+/` | Comenta líneas |
| `Ctrl+F` | Busca en archivo |
| `Ctrl+H` | Busca y reemplaza |

---

## 📂 Estructura Recomendada

```bash
# Crea carpetas de trabajo
mkdir -p proyectos/{frontend,backend,security,planning}

# Cada carpeta tiene su agent
cp agency-agents/engineering/engineering-frontend-developer.md proyectos/frontend/AGENTE.md
cp agency-agents/engineering/engineering-backend-architect.md proyectos/backend/AGENTE.md

# Trabajas en cada una
code proyectos/frontend/
```

---

## ✨ Ejemplo Paso a Paso Completo

```bash
# 1. Crea carpeta de trabajo
mkdir mi-app-react
cd mi-app-react

# 2. Copia el Frontend Developer
cat ../agency-agents/engineering/engineering-frontend-developer.md > AGENTE.md

# 3. Abre todo en VS Code
code .

# 4. En VS Code, abre Terminal (Ctrl+`)

# 5. Crea tu tarea
cat > TAREA.md << 'EOF'
# Mi Tarea

Crea un componente React de carrito de compras que:
- Muestre productos
- Permita aumentar/disminuir cantidad
- Calcule total
- Persista en localStorage
- Use TailwindCSS

EOF

# 6. En AGENTE.md, al final, escribe:
# ---
# ## MI TAREA
# [ver TAREA.md]
# 
# Por favor, crea el componente completo.

# 7. Abre Copilot (Ctrl+I) y pide:
# "Soy el Frontend Developer. Crea el componente de mi tarea."

# 8. ¡Listo! Tendrás código completo
```

---

## 🎓 Próximos Pasos

1. **Hoy:** Prueba con un agent simple (Frontend Developer)
2. **Mañana:** Prueba combinar 2 agents
3. **Pronto:** Domina tu agente favorito
4. **Después:** Crea tus propios agents

---

## 📞 Si Necesitas Ayuda

```bash
# Ver todos los agents disponibles
ls -la agency-agents/engineering/
ls -la agency-agents/design/
ls -la agency-agents/marketing/

# Ver contenido de un agent
cat agency-agents/engineering/engineering-frontend-developer.md | less

# Buscar un agent específico
grep -r "Especialidad" agency-agents/ | grep "React"
```

---

## 🚀 ¡EMPIEZA AHORA!

```bash
# En tu VS Code, abre Terminal (Ctrl+`)

# Copia y pega esto:
mkdir agentes-test && cd agentes-test && \
cat ../agency-agents/engineering/engineering-frontend-developer.md > AGENTE.md && \
code .

# Listo, tienes un agent activo en VS Code
```

---

**¡Los agentes están activados en tu VS Code!**

Ahora puedes trabajar con ellos de forma natural y poderosa. 🎭

