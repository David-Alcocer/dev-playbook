# 🚀 DevPlaybook: Simulación Profesional de Flujo de Trabajo con GitHub Projects

![GitHub](https://img.shields.io/badge/GitHub-Projects-blue)
![Markdown](https://img.shields.io/badge/Documentación-Markdown-brightgreen)
![Scrum](https://img.shields.io/badge/Metodología-Scrum-orange)
![Estado](https://img.shields.io/badge/Estado-En%20Progreso-yellow)

## 📋 Descripción del Proyecto

**DevPlaybook** es una simulación completa de un entorno real de trabajo en ingeniería de software, donde los participantes aplican procesos profesionales de control de versiones, organización por equipos, revisión de calidad y automatización utilizando **GitHub Projects**.

> ⚡ **Experiencia Realista**: Replicamos fielmente las condiciones y desafíos que encontrarás en una empresa de software moderna.

## 🎯 Objetivos del Proyecto

| Objetivo | 🎯 Descripción | 💡 Valor |
|----------|----------------|-----------|
| **Simulación Real** | Replicar el flujo de trabajo empresarial completo | Experiencia auténtica |
| **Automatización** | Uso práctico de GitHub Projects y Actions | Eficiencia industrial |
| **Trabajo Colaborativo** | Desarrollo coordinado por equipos | Habilidades de equipo |
| **Evaluación por Proceso** | El flujo es más importante que solo la respuesta | Mentalidad profesional |
| **Caos Controlado** | Avances desfasados en el tiempo | Gestión de complejidad |

## 🧠 Conceptos de Ingeniería de Software Aplicados

| Área | Tecnología/Concepto | Aplicación |
|------|---------------------|------------|
| **Proceso de Software** | SDLC Completo | Flujo end-to-end |
| **Metodología Ágil** | Scrum | Organización por equipos |
| **Control de Versiones** | Git | Gestión de código |
| **Plataforma Colaborativa** | GitHub | Entorno unificado |
| **Calidad** | CODEOWNERS | Revisión por pares |
| **Documentación** | Markdown | Comunicación técnica |

## 🗂️ Estructura del Repositorio
dev-playbook/
├── 📁 equipos/
│ ├── 📁 team-1/
│ ├── 📁 team-2/
│ ├── 📁 team-3/
│ ├── 📁 team-4/
│ ├── 📁 team-5/
│ └── 📁 team-6/
├── 📄 README.md
└── 📄 CONTRIBUTING.md


## 🌿 Estrategia de Ramas

### 📊 Diagrama de Ramas
main (rama principal estable)
│
├── team-1-integration
│ ├── issue-15-juan-perez
│ └── issue-16-maria-lopez
│
├── team-2-integration
│ ├── issue-22-carlos-ruiz
│ └── issue-25-ana-garcia
│
└── team-3-integration
├── issue-18-axel-meza
└── issue-21-lucia-mendez


### 📋 Tipos de Ramas

| Tipo | Convención | Propósito |
|------|------------|-----------|
| **Principal** | `main` | Código estable y listo para producción |
| **Integración** | `team-X-integration` | Unificación del trabajo por equipo |
| **Feature** | `issue-#-nombre` | Trabajo individual de cada estudiante |

## 🔄 Flujo Global del Proceso

### 📈 Diagrama de Flujo
🎫 Issue → 🔄 In Progress → 🌿 Rama → 📤 PR a equipo
↓
👀 In Review → 🧹 Squash → 📤 PR a main → ✅ Merge → 🏁 Done


### 📝 Descripción Detallada del Flujo

1. **🎫 Issue Creation** - Se crea un ticket para cada tarea
2. **🔄 In Progress** - El estudiante comienza a trabajar
3. **🌿 Feature Branch** - Desarrollo en rama individual
4. **📤 PR to Team** - Pull Request a la rama de integración del equipo
5. **👀 Code Review** - Revisión por CODEOWNERS
6. **🧹 Squash Merge** - Integración limpia al equipo
7. **📤 PR to Main** - Pull Request final a main
8. **✅ Final Merge** - Integración completa
9. **🏁 Done** - Tarea completada

## 👥 Organización por Equipos en el Tiempo

### 🕒 Cronograma de Inicio

| Equipo | Rama de Integración | ⏰ Inicio | 👥 Miembros |
|--------|---------------------|-----------|-------------|
| **Team 1** | `team-1-integration` | T + 0 min | 4-5 estudiantes |
| **Team 2** | `team-2-integration` | T + 5 min | 4-5 estudiantes |
| **Team 3** | `team-3-integration` | T + 10 min | 4-5 estudiantes |
| **Team 4** | `team-4-integration` | T + 15 min | 4-5 estudiantes |
| **Team 5** | `team-5-integration` | T + 20 min | 4-5 estudiantes |
| **Team 6** | `team-6-integration` | T + 25 min | 4-5 estudiantes |

> ⚡ **Simulación Realista**: Los inicios escalonados crean un flujo de trabajo desordenado en tiempo, replicando condiciones reales de la industria.

## 🧪 Flujo de Trabajo del Estudiante

### 📋 Checklist Paso a Paso

| Paso | Actividad | 🛠️ Comando/Acción |
|------|-----------|-------------------|
| 1 | **Aceptar invitación** | ✅ Click en enlace de invitación |
| 2 | **Clonar repositorio** | `git clone <repo-url>` |
| 3 | **Localizar Issue** | 📊 Ir a Projects → Mi Issue |
| 4 | **Mover a In Progress** | 🖱️ Drag & Drop en el board |
| 5 | **Crear rama desde Issue** | 🎫 Usar botón "Create branch" |
| 6 | **Cambiar a rama local** | `git checkout issue-#-nombre` |
| 7 | **Navegar a carpeta de equipo** | `cd equipos/team-X/` |
| 8 | **Editar archivo personal** | ✏️ `NOMBRE.md` |
| 9 | **Contestar pregunta** | 📝 Formato Markdown |
| 10 | **Guardar cambios** | 💾 Ctrl+S / Cmd+S |
| 11 | **Stage changes** | `git add .` |
| 12 | **Commit changes** | `git commit -m "feat: respuesta #issue"` |
| 13 | **Push changes** | `git push origin issue-#-nombre` |
| 14 | **Crear PR a equipo** | 📤 New Pull Request |
| 15 | **Vincular Issue** | 🔗 "Closes #N" en descripción |

## 🔁 Flujo de Pull Requests

### 📊 Estrategia de Integración

| Etapa | Origen | Destino | Acción | Responsable |
|-------|--------|---------|--------|-------------|
| **PR Individual** | `issue-#-nombre` | `team-X-integration` | 👀 Revisión + 🧹 Squash | CODEOWNERS |
| **PR de Equipo** | `team-X-integration` | `main` | ✅ Merge Final | Organizadores |

### 🎯 Reglas de PR
Título del PR: feat: Respuesta para Issue #XX
Descripción:
Completada tarea del Issue #XX

Archivo creado en carpeta de equipo

Formato Markdown correcto

Changes:
Agregado archivo equipos/team-X/NOMBRE.md

Closes #XX


## 🛡️ Sistema CODEOWNERS

### 👥 Responsabilidades

| Fase | Responsable | Acción | Permisos |
|------|-------------|--------|----------|
| **Revisión** | CODEOWNERS | ✅ Validar contenido | Approve/Request changes |
| **Integración** | CODEOWNERS | 🧹 Squash a rama de equipo | Merge permissions |
| **Integración Final** | Organizadores | ✅ Merge a main | Admin permissions |

## ⚠️ Reglas Obligatorias

### 🚫 No Hacer

| Regla | ❌ Prohibido | ✅ Correcto | Justificación |
|-------|--------------|-------------|---------------|
| **Rama Main** | Trabajar en `main` | Usar ramas feature | Protección del repositorio |
| **Títulos de Issues** | Modificar títulos | Mantener original | Trazabilidad |
| **Archivos** | Modificar archivos ajenos | Trabajar solo en el propio | Evitar conflictos |
| **Entorno** | Usar otras herramientas | Solo VS Code | Uniformidad |
| **Vínculos** | PR sin referencia | Usar `Closes #N` | Automatización |

### ✅ Debe Hacer

| Regla | Descripción | Beneficio |
|-------|-------------|-----------|
| **Un archivo por alumno** | Cada estudiante trabaja en su propio archivo | Minimiza conflictos |
| **Commits descriptivos** | Mensajes claros y concisos | Mejor trazabilidad |
| **Sincronización frecuente** | `git pull` regularmente | Evita divergencias |
| **Revisión por pares** | Ayudar a compañeros | Aprendizaje colaborativo |

## ✅ Automatización en GitHub Projects

### 🤖 Automatización del Board

| Evento | Trigger | Acción Automática |
|--------|---------|-------------------|
| **Inicio de trabajo** | Issue vinculado a PR | `To Do` → `In Progress` |
| **Revisión** | PR creado | `In Progress` → `In Review` |
| **Completado** | Merge a main | `In Review` → `Done` |

### 📊 Estados del Project Board

| Estado | 🎯 Significado | 👥 Responsable |
|--------|----------------|----------------|
| **To Do** | 📥 Issues asignados sin iniciar | Estudiantes |
| **In Progress** | 🚀 Alumnos trabajando activamente | Estudiantes |
| **In Review** | 👀 En revisión por CODEOWNERS | Revisores |
| **Done** | ✅ Integrados satisfactoriamente a main | Sistema |

## 🏁 Cierre Conceptual

### 💡 Filosofía DevPlaybook

> **"En la industria, el proceso es tan importante como el resultado."**

DevPlaybook no evalúa solo respuestas correctas, sino la **capacidad de seguir un proceso profesional completo**, tal como sucede en una empresa real de software.

### 🎓 Competencias Desarrolladas

| Competencia Técnica | Competencia Profesional |
|---------------------|-------------------------|
| ✅ Control de versiones Git | ✅ Trabajo en equipo |
| ✅ Flujos de PR profesionales | ✅ Comunicación técnica |
| ✅ Revisión de código | ✅ Gestión del tiempo |
| ✅ Automatización GitHub | ✅ Seguimiento de procesos |

---

**¿Listo para comenzar tu journey profesional?** 🚀

*Únete al proyecto y experimenta el desarrollo de software como realmente es, no como te lo cuentan.*