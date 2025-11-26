# 🚀 DevPlaybook — Guía Oficial de Participación  
### Simulación de Sprint Ágil con GitHub, GitHub Projects y Markdown

Bienvenido/a a la sesión práctica **DevPlaybook**. En esta actividad vivirás un **flujo real de trabajo usado en la industria del software**, utilizando Git, GitHub, GitHub Projects, ramas por tarea, Pull Requests y documentación en Markdown. El objetivo es simular un **sprint ágil real** para que experimentes cómo trabajan los equipos profesionales.

---

## 🎯 Objetivo General

Simular un sprint real de desarrollo de software donde cada estudiante trabaja sobre un Issue individual, crea su rama, documenta su respuesta, genera un Pull Request, pasa por revisión y finalmente se integra al repositorio principal. Al mismo tiempo se refuerzan los conceptos de Ingeniería de Software, procesos, Scrum, Git, GitHub, requerimientos y calidad.

---

## ✅ Requisitos Previos

- Cuenta activa de GitHub  
- Git instalado  
- Visual Studio Code instalado  
- Acceso como colaborador al repositorio `dev-playbook`  
- Conexión a Internet  

---

## 📩 Aceptación de Invitación

Para poder participar entra a:

https://github.com/notifications

yaml
Copiar código

Busca la invitación al repositorio **dev-playbook** y da clic en **Accept invitation**.  
Si no aceptas la invitación, **no podrás subir tu trabajo**.

---

## 💻 Clonado del Repositorio

Desde la terminal de VS Code:

```bash
git clone https://github.com/<USUARIO-DEL-REPO>/dev-playbook.git
cd dev-playbook
Desde la interfaz de VS Code:

Abrir VS Code

Ctrl + Shift + P

Escribir Git: Clone

Pegar la URL del repositorio

Elegir la carpeta donde se guardará

📋 Ubicación de tu Issue
Entra al repositorio en GitHub

Dirígete a la pestaña Projects

Localiza el Issue con tu nombre completo

Da clic en él y lee tu pregunta asignada

🌿 Creación de la Rama
Dentro de tu Issue:

Da clic en Create branch

Copia el nombre de la rama creada

En VS Code ejecuta:

bash
Copiar código
git checkout nombre-de-tu-rama
Ejemplo:

bash
Copiar código
git checkout issue-12-andrea-acosta
Verificación:

bash
Copiar código
git branch
📁 Ubicación del Archivo
En el proyecto entra a:

Copiar código
equipos/
Después a tu carpeta de equipo:

Copiar código
team-1 / team-2 / team-3 / team-4 / team-5 / team-6
Ubica tu archivo:

Copiar código
TU-NOMBRE.md
Ejemplo:

Copiar código
ACOSTA-ANDREA.md
✍️ Redacción de la Respuesta
Abre tu archivo .md y redacta tu respuesta con tus propias palabras usando formato Markdown.

Ejemplo:

markdown
Copiar código
# ¿Qué es Git?

Git es un sistema de control de versiones que permite registrar los cambios de un proyecto y facilitar el trabajo colaborativo.

## ¿Para qué sirve?
- Controlar versiones
- Trabajar en equipo
- Mantener historial de cambios
Guarda los cambios.

💾 Registro de Cambios
bash
Copiar código
git add .
bash
Copiar código
git commit -m "Respuesta a mi Issue"
Ejemplo:

bash
Copiar código
git commit -m "Agrega respuesta sobre Git"
⬆️ Envío de Cambios
bash
Copiar código
git push origin nombre-de-tu-rama
Ejemplo:

bash
Copiar código
git push origin issue-12-andrea-acosta
🔁 Creación del Pull Request
Regresa a GitHub

Da clic en:

powershell
Copiar código
Compare & pull request
Título:

less
Copiar código
Respuesta a Issue #12
Descripción obligatoria:

nginx
Copiar código
Closes #12
Da clic en:

sql
Copiar código
Create pull request
⏳ Revisión del Pull Request
El PR pasará a In Review. Los Codeowners lo revisarán.
Si es aprobado, se integrará al repositorio y tu Issue pasará a Done.
Si hay observaciones, deberás corregirlas en la misma rama y volver a hacer commit y push.

⚠️ Reglas Importantes
No trabajar en la rama main

Trabajar solo en tu rama

Editar únicamente tu archivo

Usar siempre Closes #NUMERO-DEL-ISSUE

No borrar carpetas ni archivos de otros compañeros

Respetar el trabajo del equipo

Consultar dudas con el equipo organizador

🧠 Buenas Prácticas
Usar títulos en Markdown

Mantener claridad en las respuestas

Hacer commits con mensajes claros

Revisar ortografía

No subir archivos innecesarios

🏁 Mensaje Final
Esta actividad simula el trabajo real dentro de una empresa de software. No solo importa entregar, sino seguir correctamente el proceso profesional.

DevPlaybook no es solo una práctica, es una experiencia real de ingeniería de software.

🚀
