# Fase 4: Metodología de Trabajo

## 📌 Resumen de la Fase

En esta fase se define el marco metodológico que regirá el desarrollo del proyecto. Dado el tamaño del equipo (2 personas) y la naturaleza académica del trabajo, se ha optado por un **modelo mixto** que combina la visualización y flexibilidad de **Kanban** con la planificación por iteraciones de **Scrum**.

!!! success "Estado"
    **En progreso** (entrega: 24/04/2026)

---

## 1. 🧩 Metodología Elegida: Kanban + Scrum (Modelo Mixto)

### Descripción

Se adopta un enfoque híbrido que aprovecha lo mejor de ambas metodologías:

| Metodología | Elementos que usamos | Propósito |
|-------------|----------------------|----------|
| **Kanban** | Tablero visual, flujo continuo, límites de trabajo en progreso (WIP) | Visualizar el estado de cada tarea y evitar cuellos de botella |
| **Scrum** | Sprints de 1 semana, reuniones diarias, revisiones y retrospectivas | Entregar valor de forma iterativa y mantener ritmo constante |

### ¿Por qué un modelo mixto?

!!! quote "Justificación"
    Como equipo de solo dos personas, aplicar Scrum al 100 % resultaría excesivamente burocrático (roles muy definidos, eventos largos). Por otro lado, usar solo Kanban sin iteraciones planificadas podría hacer perder el foco en las entregas parciales. El modelo mixto nos permite:

    - **Flexibilidad**: adaptar el ritmo semanal según la carga de otras asignaturas.
    - **Visibilidad**: el tablero Trello muestra el flujo real del trabajo.
    - **Compromiso**: los sprints semanales fijan objetivos concretos y evaluables.
    - **Mejora continua**: las retrospectivas nos ayudan a ajustar el proceso.

---

## 2. 📅 Organización de Reuniones

### Tipos de Reunión

| Reunión | Frecuencia | Duración | Participantes | Objetivo |
|---------|------------|----------|---------------|----------|
| **Daily Standup** | Diaria (de lunes a viernes) | 10–15 min | Ramón y Anna | Sincronizar el trabajo del día, detectar bloqueos |
| **Sprint Planning** | Lunes de cada semana | 30 min | Ramón y Anna | Seleccionar tareas del backlog para el sprint |
| **Sprint Review** | Viernes de cada semana | 20 min | Ramón y Anna | Demostrar lo hecho, validar con el criterio de aceptación |
| **Retrospectiva** | Viernes de cada semana | 15 min | Ramón y Anna | Analizar qué funcionó, qué no, y acciones de mejora |

### Formato de la Daily Standup

Cada integrante responde a tres preguntas:

1. **¿Qué hice ayer?**  
2. **¿Qué voy a hacer hoy?**  
3. **¿Tengo algún bloqueo o necesito ayuda?**

!!! info "Comunicación asíncrona"
    Si no es posible coincidir presencialmente o en videollamada, la daily se realiza por escrito en el canal **#Planificación** de Microsoft Teams antes de las 10:00 h.

### Calendario tipo de Sprint (1 semana)

```text
Lunes              Martes–Jueves          Viernes
├─ Planning        ├─ Desarrollo          ├─ Review
│  (30 min)        │  (trabajo autónomo)  │  (20 min)
│                  │                      │
│                  │                      ├─ Retrospective
│                  │                      │  (15 min)
│                  │                      |
└─ Daily           └─ Daily (cada día)    └─ Daily
```
  
---

## 3. 📈 Seguimiento del Trabajo

### 3.1 Tablero Trello (Kanban)

El flujo de trabajo en Trello sigue las siguientes reglas:

- **WIP Limit**: máximo 2 tarjetas por persona en la columna *En Progreso*.
- **Definición de "Hecho"**: una tarea solo se mueve a *Hecho* cuando:
  - El código está subido a GitHub y funciona en local.
  - La documentación asociada está actualizada en MkDocs.
  - El compañero ha revisado y validado el trabajo (*pair review*).
- **Priorización**: las tareas se ordenan en *Por Hacer* de arriba a abajo según prioridad.

### 3.2 Control de versiones (GitHub)

| Convención | Descripción |
|------------|-------------|
| **Ramas** | `main` (producción), `develop` (integración), `feature/nombre-tarea` (desarrollo) |
| **Commits** | Mensajes descriptivos en español: `feat: añade formulario de login`, `fix: corrige validación email` |
| **Pull Requests** | Cada funcionalidad nueva se integra mediante PR revisada por el compañero |
| **Issues** | Bugs y mejoras se registran como Issues vinculados al proyecto |

### 3.3 Documentación continua

- La documentación se escribe en **Markdown** y se publica con **MkDocs**.
- Cada vez que se completa una fase, se actualiza el archivo `.md` correspondiente.
- Se mantiene un registro de decisiones técnicas en `docs/decisiones.md` *(por crear)*.

---

## 4. 🔄 Flujo de Trabajo del Equipo

El siguiente diagrama describe el ciclo de vida de una tarea desde que se identifica hasta que se entrega:

```text
┌─────────────┐     ┌─────────────┐     ┌─────────────┐
│   BACKLOG   │────→│ POR HACER   │────→│ EN PROGRESO │
│  (ideas y   │     │ (sprint     │     │ (desarrollo │
│   tareas)   │     │  actual)    │     │   activo)   │
└─────────────┘     └─────────────┘     └──────┬──────┘
                                               │
                    ┌─────────────┐            │
                    │   HECHO ✓   │←───────────┘
                    │ (validado y │
                    │  mergeado)  │
                    └──────▲──────┘
                           │
                    ┌──────┴──────┐
                    │  REVISIÓN   │
                    │ (pair review│
                    │   y pruebas)│
                    └─────────────┘
```

---

!!! tip "Navegación"
    ← [Fase 3: Planificación ](fase3.md) | [Fase 5: Diseño Web ](fase5.md) →