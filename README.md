# Lista de perros

## Descripcion

Aplicacion web que muestra imagenes aleatorias de perros y permite interactuar con ellas mediante opciones como "me gusta","no me gusta" y saltear.

## Instalacion

No requiere instalacion de dependencias.
Para ejecutar el proyecto, se debe abrir el archivo `index.html` en un navegador web.

## Uso

Abrir el archivo `index.html` para visualizar la aplicacion y mostrar imagenes aleatorias de perros.

## Estrategia de ramificacion

Para este proyecto se utiliza GitFlow.

GitFlow permite separar el desarrollo de nuevas funcionalidades, correcciones y codigo estable mediante distintas ramas.

Las principales ramas utilizadas son:

- `main`: contiene la version estable del proyecto.
- `develop`: contiene los cambios en desarrollo antes de integrarlos a la version estable.
- `feature/*`: se utiliza para desarrollar nuevas funcionalidades.
- `hotfix/*`: se utiliza para realizar correcciones rapidas.

### Otros modelos de ramificacion

- GitHub Flow: utiliza una rama principal y ramas de trabajo de corta duracion, integradas mediante Pull Requests.
- Trunk-Based Development: los desarrolladores integran cambios frecuentemente sobre una rama principal, utilizando ramas de muy corta duracion.

Se eligio GitFlow porque permite organizar claramente las funcionalidades, correcciones y versiones estables del proyecto.

## Convencion de ramas

Las ramas deben utilizar los siguientes nombres:

- `feature/nombre-funcionalidad`
- `hotfix/nombre-correccion`

Ejemplos:

- `feature/mejora-interfaz`
- `feature/documentacion`
- `hotfix/correccion-texto`

## Convencion de commits

Los mensajes de commit deben ser claros y describir el cambio realizado.

Ejemplos:

- `mejora interfaz principal`
- `corrige texto principal`
- `corrige flujo de contribucion`
- `agrega guia de contribucion`

## Flujo de trabajo

1. Actualizar la rama `develop`.
2. Crear una rama `feature/*` o `hotfix/*`.
3. Realizar los cambios necesarios.
4. Crear un commit.
5. Subir la rama a GitHub.
6. Crear un Pull Request hacia `develop`.
7. Revisar los cambios.
8. Realizar el merge cuando los cambios sean correctos.

## Revision de Pull Requests

Antes de realizar un merge se deben revisar:

- Los archivos modificados.
- Los commits realizados.
- Que no existan conflictos.
- Que los cambios correspondan al objetivo de la rama.

Las ramas `feature/*` y `hotfix/*` se integran mediante Pull Requests.

La rama `main` representa la version estable del proyecto.

## Integracion continua con GitHub Actions

El proyecto utiliza GitHub Actions para automatizar la validacion de los cambios realizados en el repositorio.

El workflow se ejecuta automaticamente cuando se realiza un push a la rama `develop` y cuando se crea un Pull Request hacia `main`.

La accion verifica que los archivos principales del proyecto, como `index.html`, `style.css` e `index.js`, se encuentren presentes.

Esta automatizacion permite verificar los cambios antes de integrarlos a la rama estable y representa una etapa basica de Integracion Continua.

## Estructura del proyecto

- `index.html`: estructura principal de la pagina.
- `style.css`: estilos de la interfaz.
- `index.js`: logica de la aplicacion.
- `README.md`: documentacion principal.
- `CONTRIBUTING.md`: guia de contribucion.
- `.github/workflows/ci.yml`: configuracion del workflow de GitHub Actions.

## Control de versiones

El proyecto utiliza Git y GitHub para mantener la trazabilidad de los cambios.
Cada funcionalidad o correccion se desarrolla en una rama independiente y posteriormente se integra mediante Pull Requests.

## Autores

- Francisco Osorio

## Uso de IA

Se utilizo ChatGPT como herramienta de apoyo para orientar la configuracion del repositorio y resolver dudas durante el desarrollo del trabajo.

## Reflexion individual

- Francisco Osorio

Fue motivante volver a trabajar con la terminal de VS Code, ya que por no utilizarla de forma frecuente se me habia olvidado varios de los comandos y sus funciones, ademas este trabajo me permitio obtener una base que podre utilizar en trabajos futuros, especialmente en el uso de Git y GitHub, la creacion de ramas y la organizacion de los cambios del proyecto y pude comprender mejor el uso de distintas ramas lo que permite organizar mejor el trabajo cuando participan varias personas en un mismo proyecto, aunque en esta ocasion no contaba con un grupo con el cual poder trabajar en conjunto en el desarrollo de este trabajo, por lo que no pude experimentar completamente el trabajo colaborativo, espero poder aplicar estos conocimientos en el proximo trabajo grupal.