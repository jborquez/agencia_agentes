# 🔥 Ejemplos Prácticos Paso a Paso

## Cómo Usar Esta Guía

Esta guía contiene **5 ejemplos completos y listos para usar**. Solo copia, pega en Claude.ai y sigue los pasos.

---

## Ejemplo 1: Crear un Componente React de Carrito de Compras

### Objetivo
Construir un componente React funcional para un carrito de compras.

### Pasos

**1. Abre Claude.ai** → Nueva Conversación

**2. Copia el siguiente contenido (Frontend Developer Agent):**

```
# 🎨 Frontend Developer

## Propósito
Diseñar e implementar interfaces de usuario modernas, funcionales y performantes. Mi enfoque es en la experiencia del usuario, la accesibilidad y el código limpio.

## Especialidades
- React, Vue, Angular
- HTML5, CSS3, TailwindCSS
- Responsive design
- Web performance
- Accesibilidad (a11y)
- Testing (Vitest, Jest, Cypress)

## Procesos de Trabajo
1. **Análisis de requisitos** - Entiendo qué necesitas construir
2. **Diseño de componentes** - Planifico la estructura
3. **Implementación** - Código limpio y mantenible
4. **Testing** - Pruebas unitarias y de integración
5. **Optimización** - Performance y accesibilidad

## Estilo de Comunicación
- Pragmático y orientado a resultados
- Explico conceptos claramente
- Proporciono ejemplos de código
- Sugiero mejores prácticas

## Cuando Usarme
- Construir interfaces de usuario
- Resolver problemas de React/Vue
- Optimizar rendimiento
- Implementar componentes complejos
```

**3. Pega en Claude y añade tu solicitud:**

```
Crea un componente React llamado ShoppingCart que:

1. Muestre una lista de productos con:
   - Nombre del producto
   - Precio
   - Cantidad
   - Botón para aumentar/disminuir cantidad
   - Botón para remover

2. Calcule y muestre:
   - Subtotal
   - Impuesto (10%)
   - Total

3. Características adicionales:
   - Contador de items
   - Persistencia en localStorage
   - Estilos con TailwindCSS
   - Animaciones suaves

Por favor proporciona:
- Código completo del componente
- Ejemplo de datos de prueba
- Instrucciones de instalación
```

**4. Claude te proporcionará:**
- ✅ Componente React completo
- ✅ Código reutilizable
- ✅ Estilos TailwindCSS
- ✅ Ejemplos de datos

---

## Ejemplo 2: Analizar y Mejorar tu Código

### Objetivo
Hacer un code review profesional de tu código Python/JavaScript.

### Pasos

**1. Copia tu código** (por ejemplo, un archivo Python):

```python
# archivo_con_problemas.py
def get_user_data(user_id):
    import requests
    url = "https://api.example.com/users/" + user_id
    response = requests.get(url)
    data = response.json()
    return data

def process_users():
    for i in range(100000):
        user = get_user_data(str(i))
        print(user['name'])
```

**2. En Claude, copia este agent:**

```
# 👁️ Code Reviewer

## Propósito
Revisar código con ojo crítico, identificar problemas y sugerir mejoras.

## Áreas de Expertise
- Calidad del código (DRY, SOLID)
- Performance
- Seguridad
- Mantenibilidad
- Testing

## Procesos de Revisión
1. **Análisis estático** - Leo el código
2. **Identificación de issues** - Problemas potenciales
3. **Sugerencias** - Mejoras concretas
4. **Ejemplos** - Código mejorado

## Estilo
- Constructivo y educativo
- Explico el "por qué"
- Propongo soluciones
```

**3. Pega en Claude:**

```
Aquí está mi código Python. Por favor:

1. Identifica problemas de performance
2. Sugiere mejoras de seguridad
3. Propone refactorización
4. Proporciona código mejorado

[PEGA TU CÓDIGO AQUÍ]
```

**4. Obtendrás:**
- ✅ Análisis de problemas
- ✅ Código refactorizado
- ✅ Explicaciones
- ✅ Mejores prácticas

---

## Ejemplo 3: Crear un Plan de Proyecto Completo

### Objetivo
Planificar el desarrollo de una aplicación de inicio a fin.

### Pasos

**1. Copia este Agent:**

```
# 📅 Project Shepherd

## Propósito
Planificar proyectos complejos en fases manejables, con riesgos identificados.

## Especialidades
- Planificación ágil
- Sprints y milestones
- Gestión de riesgos
- Estimación
- Comunicación de proyecto

## Enfoque
1. **Descubrimiento** - Entiendo el scope
2. **Planificación** - Creo timeline
3. **Desglose** - Creo sprints y tareas
4. **Riesgos** - Identifico problemas potenciales

## Salida
- Timeline detallado
- Sprints planificados
- Riesgos identificados
- KPIs de seguimiento
```

**2. Pide un plan en Claude:**

```
Necesito un plan completo para un proyecto:

PROYECTO: Sistema de Gestión de Tareas (Task Management)

Características:
- Usuarios pueden crear, editar, eliminar tareas
- Asignación a otros usuarios
- Prioridades (baja, media, alta)
- Categorías/etiquetas
- Dashboard con estado
- Notificaciones por email
- API REST
- Apps web y móvil

Requisitos Técnicos:
- Frontend: React
- Backend: Node.js
- Base de datos: PostgreSQL
- Hosting: AWS/Heroku

Equipo:
- 1 fullstack developer
- 1 frontend developer
- 1 DevOps engineer
- 1 QA tester

Por favor proporciona:
1. Timeline estimado (en semanas)
2. Sprints desglosados (cada sprint con tareas)
3. Hitos principales
4. Riesgos potenciales
5. Plan de testing
6. Matriz RACI (responsabilidades)
```

**3. Claude creará:**
- ✅ Timeline de 12-16 semanas
- ✅ 4-6 sprints planificados
- ✅ Tareas específicas por sprint
- ✅ Hitos y deliverables
- ✅ Identificación de riesgos

---

## Ejemplo 4: Estrategia de Lanzamiento de Producto

### Objetivo
Crear un plan de go-to-market completo para un producto nuevo.

### Pasos

**1. Usa estos 2 agents en secuencia:**

**AGENT 1 - Trend Researcher:**
```
# 📊 Trend Researcher

## Propósito
Investigar mercados, identificar oportunidades y tendencias.

## Especialidades
- Market research
- Análisis competitivo
- Identificación de gaps
- Validación de ideas
- Análisis SWOT

## Proceso
1. Analizo el mercado existente
2. Identifico competencia
3. Busco gaps y oportunidades
4. Propongo estrategias
```

**AGENT 2 - Growth Hacker:**
```
# 🚀 Growth Hacker

## Propósito
Diseñar estrategias para crecimiento exponencial.

## Especialidades
- Adquisición de usuarios
- Loops virales
- Retención
- Activación
- Revenue optimization

## Procesos
1. Defino KPIs clave
2. Diseño loops de crecimiento
3. Identifico canales
4. Propongo experimentos
```

**2. En Claude, usa ambos agents:**

```
[PEGA Trend Researcher]

Analiza el mercado de herramientas de productividad para equipos remotos:
- ¿Qué soluciones existen?
- ¿Cuáles son los gaps?
- ¿Qué tendencias ves?

[PEGA Growth Hacker]

Basándote en el análisis anterior, diseña un plan de lanzamiento para:
- PRODUCTO: TaskMaster (plataforma colaborativa de tareas)
- TARGET: Equipos de 5-20 personas
- OBJETIVO: 1000 usuarios en 3 meses

Incluye:
1. Estrategia de adquisición
2. Canales principales
3. Loops de crecimiento
4. Plan de pricing
5. Viral loops específicos
```

**3. Obtendrás:**
- ✅ Análisis de mercado
- ✅ Estrategia de lanzamiento
- ✅ Canales de adquisición
- ✅ KPIs a seguir
- ✅ Experimentos a probar

---

## Ejemplo 5: Hacer un Code Refactor Completo

### Objetivo
Refactorizar código existente con mejores prácticas.

### Pasos

**1. Prepara tu código (cualquier lenguaje)**

Por ejemplo, un archivo JavaScript con problemas:

```javascript
// index.js - Código con problemas
const users = [];

function addUser(name, email, age, city, country) {
  const user = {
    id: Math.random(),
    name: name,
    email: email,
    age: age,
    city: city,
    country: country,
    created: new Date()
  };
  users.push(user);
  return user;
}

function getUser(id) {
  for (let i = 0; i < users.length; i++) {
    if (users[i].id === id) {
      return users[i];
    }
  }
}

function updateUser(id, name, email, age, city, country) {
  const user = getUser(id);
  if (user) {
    user.name = name;
    user.email = email;
    user.age = age;
    user.city = city;
    user.country = country;
    return user;
  }
}

function deleteUser(id) {
  for (let i = 0; i < users.length; i++) {
    if (users[i].id === id) {
      users.splice(i, 1);
      return true;
    }
  }
  return false;
}

function listUsers() {
  let output = "";
  for (let i = 0; i < users.length; i++) {
    output += users[i].name + " - " + users[i].email + "\n";
  }
  console.log(output);
}
```

**2. En Claude, copia estos agents:**

```
# 🔧 Senior Developer

## Propósito
Código excepcional con patrones avanzados.

## Especialidades
- Refactoring
- Patrones de diseño
- Testing
- Arquitectura de código
- Performance

# 👁️ Code Reviewer

## Propósito
Revisar con criterio profesional.

## Áreas
- Calidad
- Seguridad
- Testing
```

**3. Pega en Claude:**

```
Aquí tengo código JavaScript que necesita refactoring.

[PEGA TU CÓDIGO]

Por favor:
1. Identifica problemas principales
2. Refactoriza el código
3. Añade validaciones
4. Propone unit tests
5. Explica los cambios

Quiero que el código sea:
- Más mantenible
- Más eficiente
- Más seguro
- Mejor testeado
```

**4. Claude te dará:**
- ✅ Código refactorizado
- ✅ Explicación de cambios
- ✅ Ejemplos de tests
- ✅ Mejores prácticas aplicadas

---

## Ejemplo 6: Crear Documentación Técnica

### Objetivo
Generar documentación profesional para tu proyecto.

### Pasos

**1. Copia el agent:**

```
# 📚 Technical Writer

## Propósito
Documentación clara, completa y accesible.

## Especialidades
- API documentation
- User guides
- Architecture docs
- Tutorials
- README files

## Estilo
- Claro y conciso
- Bien estructurado
- Ejemplos abundantes
- Fácil de seguir
```

**2. En Claude:**

```
Necesito documentación para mi API REST.

Mi API es un sistema de:
- Gestión de usuarios
- Autenticación JWT
- CRUD de productos
- Carrito de compras
- Procesamiento de pagos

Tecnología:
- Node.js + Express
- MongoDB
- Documentación: OpenAPI 3.0

Por favor crea:
1. README.md (setup y overview)
2. API documentation (todos los endpoints)
3. Authentication guide
4. Error handling guide
5. Examples (curl, JavaScript, Python)
6. Troubleshooting

Usa Markdown y OpenAPI 3.0 format.
```

**3. Obtendrás:**
- ✅ README completo
- ✅ API docs
- ✅ Ejemplos de código
- ✅ Guías de uso

---

## 🎯 Consejos Para Mejores Resultados

### 1. **Sé Específico**
❌ Malo: "Ayúdame con código"
✅ Bueno: "Crea un componente React que muestre una tabla de usuarios con paginación"

### 2. **Proporciona Contexto**
```
Aquí está mi estructura de datos:
[muestra los datos]

Aquí está mi código actual:
[muestra el código]

Necesito que hagas:
[describe específicamente]
```

### 3. **Usa Múltiples Agents**
Una tarea importante = múltiples perspectivas
```
[Pega Architect Agent]
[Pega Security Agent]
[Pega Senior Developer Agent]

Ahora, juntos, diseñen la solución completa para [tarea]
```

### 4. **Itera y Refina**
Si la primera respuesta no es perfecta:
```
El código está bien pero:
- Necesito que funcione con [caso especial]
- Quiero [característica adicional]
- El styling debería ser [especificación]

Por favor ajusta...
```

### 5. **Personaliza Según Necesites**
```
Ahora, adapta lo anterior para:
- Otro lenguaje de programación
- Otro framework
- Escala diferente
- Requisitos adicionales
```

---

## 📊 Tabla Rápida de Agents Comunes

| Necesito... | Usa Este Agent |
|-------------|----------------|
| Crear un componente UI | Frontend Developer |
| Diseñar una API | Backend Architect |
| Revisar mi código | Code Reviewer |
| Mejorar rendimiento | Senior Developer |
| Documentar proyecto | Technical Writer |
| Asegurar el código | Security Engineer |
| Optimizar DB | Database Optimizer |
| Lanzar producto | Growth Hacker |
| Plan de proyecto | Project Shepherd |
| Entender usuarios | UX Researcher |
| Investigar mercado | Trend Researcher |

---

## ✅ Checklist Para Empezar

- [ ] He leído la Guía Completa
- [ ] He clonado el repositorio ✓
- [ ] Tengo acceso a Claude.ai
- [ ] He elegido un agent
- [ ] He probado con un ejemplo simple
- [ ] He adaptado un ejemplo a mi caso
- [ ] Combinaré múltiples agents

---

## 🚀 Tu Primer Proyecto

**Elige uno de estos para empezar:**

1. **Fácil (30 mins)** - Crear un componente React simple
2. **Medio (1-2 horas)** - Refactorizar tu código actual
3. **Avanzado (3-4 horas)** - Plan completo de un proyecto
4. **Experto (full day)** - Combinar 5+ agents en un proyecto

---

**¡Ahora sí, a programar!** 🎉

Recuerda: Los mejores resultados vienen de ser específico, proporcionar contexto y iterar.

