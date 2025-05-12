# 🚀 Manual de Uso de GitHub.

Este manual describe paso a paso las funciones esenciales de GitHub: **Issues**, **Pull Requests**, **Projects**, **Gists**, **Pages**, **Codespaces** y **Dev Editor**.

---

## 1. Issues

**¿Qué es?**  
Un Issue es un ticket para reportar bugs, proponer mejoras o asignar tareas.

**Cómo crear un Issue**  
1. En tu repositorio, ve a **Issues** → **New issue**.  
2. Rellena **Título** y **Descripción**.  
3. (Opcional) Asigna labels, assignees y milestones.  
4. Haz clic en **Submit new issue**.

---
## 2. Pull Requests

**¿Qué es?**  
Un Pull Request (PR) propone integrar cambios de una rama al repositorio principal.

**Flujo básico**  
```bash
# 1. Crear y moverte a una rama nueva
git checkout -b feature/nombre-de-la-rama

# 2. Hacer cambios y commitear
git add .
git commit -m "feat: descripción clara del cambio"

# 3. Subir la rama
git push origin feature/nombre-de-la-rama
