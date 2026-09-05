# Guia de Contribucion

## Flujo de trabajo

1. Actualizar la rama principal:

```bash
git checkout develop
git pull origin develop
```

2. Crear una rama de corta duracion:

```bash
git checkout -b feature/nombre-funcionalidad
```

3. Realizar los cambios y confirmarlos:

```bash
git add .
git commit -m "descripcion del cambio"
```

4. Subir la rama al repositorio remoto:

```bash
git push origin feature/nombre-funcionalidad
```

5. Abrir un pull request hacia `develop` y solicitar revision.

## Convencion de commits

Los mensajes de commit deben ser claros y describir el cambio realizado.

Ejemplos:

- `mejora interfaz principal`
- `corrige texto principal`
- `corrige flujo de contribucion`
- `agrega guia de contribucion`

## Revision de Pull Requests

Antes de realizar un merge se deben revisar los archivos modificados, los commits realizados y que no existan conflictos.

La rama `main` corresponde a la version estable del proyecto.