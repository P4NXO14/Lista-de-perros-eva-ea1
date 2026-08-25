# Guia de Contribución

## Flujo de trabajo

1. Actualizar la rama principal:

```bash
git pull origin main
```

2. Crear una rama de corta duración:

```bash
git checkout -b feature/nombre-funcionalidad
```

3. Realizar los cambios y confirmarlos:

```bash
git add .
git commit -m "feat: descripción del cambio"
```

4. Subir la rama al repositorio remoto:

```bash
git push origin feature/nombre-funcionalidad
```

5. Abrir un Pull Request hacia `main` y solicitar revisión.

## Convención de commits

* `feat:` nueva funcionalidad.
* `fix:` corrección de errores.
* `docs:` cambios en documentación.

## Revisión de Pull Requests

Todo cambio debe ser revisado por al menos otro integrante del equipo antes de fusionarse a `main`.

La rama `main` corresponde a la versión estable del proyecto.
