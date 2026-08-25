# Lista de perros 🐶

La idea de este proyecto es dar un pequeño repaso sobre conexiones a una API y sobre eventos. Es una pequeña aplicación web que muestra imágenes de perros aleatorias (obtenidas desde [dog.ceo](https://dog.ceo/dog-api/)) y permite marcarlas como "me gusta" o "no me gusta".

Este repositorio es la **base de trabajo** para la Evaluación Parcial N°1 de Ingeniería DevOps (DOY0101). A partir de este punto, cada pareja debe construir su propio flujo de trabajo colaborativo aplicando Git, GitHub y GitHub Actions.

---

## 🚀 Cómo levantar el proyecto localmente

No requiere instalación de dependencias. Basta con abrir `index.html` en el navegador, o servirlo con cualquier servidor estático simple, por ejemplo:

```bash
npx serve .
```

---

## 🌳 Estrategia de ramificación

> ✏️ **A completar por la pareja.**
> Indiquen aquí si optaron por **GitFlow** o **Trunk-Based Development**, y justifiquen la elección considerando el tamaño del proyecto, la frecuencia de cambios esperada, y el tipo de equipo (2 personas).

---

## 📝 Convenciones de commits

> ✏️ **A completar por la pareja.**
> Documenten aquí el formato que van a usar para sus mensajes de commit (ej. `feat: agrega contador de likes`, `fix: corrige error en carga de imagen`), y por qué eligieron ese formato.

---

## 🔀 Convenciones de naming de ramas

> ✏️ **A completar por la pareja.**
> Ejemplo de formato a definir: `feature/<nombre-descriptivo>`, `hotfix/<nombre-descriptivo>`. Expliquen brevemente el criterio que usaron para nombrar sus ramas durante el desarrollo.

---

## 🔍 Estrategia de revisión (Pull Requests)

> ✏️ **A completar por la pareja.**
> ¿Cómo revisaron los cambios antes de fusionarlos a `develop` o `main`? ¿Qué debía cumplir un Pull Request para ser aprobado?

---

## ⚙️ Automatización (CI/CD)

> ✏️ **A completar por la pareja.**
> Este proyecto no incluye ningún workflow de GitHub Actions todavía — es parte de su trabajo diseñarlo e implementarlo.
>
> **Objetivo sugerido:** usar este repositorio como si tuviera un entorno de *staging* (rama `develop`) y uno de *producción* (rama `main`), automatizando la integración de cambios entre ambos. Por ejemplo:
> - Al hacer `push` a `develop`: validar que el código no tenga errores evidentes (HTML/CSS/JS)
> - Al abrir un Pull Request hacia `main`: ejecutar una verificación o despliegue automático
>
> Documenten aquí qué automatizaron, por qué, y qué rol cumple dentro de un proceso CI/CD real.

---

## 📁 Estructura de carpetas

```
Lista-de-perros/
├── index.html
├── index.js
├── style.css
└── README.md
```

> ✏️ **A completar por la pareja.**
> Si agregan nuevas carpetas o archivos durante el desarrollo (ej. `.github/workflows/`), actualicen este diagrama.

---

## 👥 Autores

- Integrante 1 — nombre
- Integrante 2 — nombre

*Proyecto original: repaso de conexión a API y manejo de eventos en JavaScript. Adaptado como base para la Evaluación Parcial N°1, DOY0101 — Ingeniería DevOps.*


Cambio realizado para practicar 