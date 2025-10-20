# Curso de Git / GitLLab

- CONTROL DE VERSIONES CON GITLAB AF 82897 - GR 85302
- Duración: 16 horas
- Modalidad: On-line
- Fechas: 20, 21, 22, 23 y 27, 28, 29, 30 de Octubre 2025
- Horario 15:30 – 17:30 hs

Formador: Alejandro Cerezo
<alce65@hotmail.es>

## Contenidos

- Introducción a Git y GitLab
  - Fundamentos del control de versiones.
  - Conceptos básicos de Git.
  - Características principales de GitLab.
- Configuración inicial y gestión de repositorios
  - Creación y clonación de repositorios
  - Configuración de SSH Y HTTPS
  - Organización y gestión de proyectos en GitLab
- Operaciones básicas con Git
  - Realización de commits y revert
  - Trabajo con ramos (branching)
  - Resolución de conflictos en merges
- Flujos de trabajo en equipo
  - Flujos de trabajo basados en GitLab Flow.
  - Uso de merge requests y revisión de código
  - Gestión de issues y etiquetado.
- Automatización y CI/CD Básico en GitLab
  - Introducción a pipelines en GitLab.
  - Configuración básica de GitLab CI/CD.
  - Integración de pruebas automáticas.
- Buenas prácticas y resolución de problemas
  - Estrategias para un historial limpio y ordenado.
  - Manejo de errores comunes en Git.

Desarrollo del curso en la carpeta Oficial -> [repo](https://github.com/IconoTC/CONTROL-DE-VERSIONES-CON-GITLAB-AF-82897---GR-85302)

## Desarrollo del curso

### Día 1 (Lunes 20 Octubre 2025)

- Presentación profesor / alumnos
- Introducción: Qué es un SCV y qué un SCV distribuido
- IDE / Editor de código: Visual Studio Code (VSC)
- Instalación de Git
- Terminales
- Configuración inicial

  - Configuración global y por repositorio
  - Configuración de usuario: name, email

- Primeros pasos con Git
  - Primer repo (init), primer commit: readme.md & .gitignore
  - Anatomía de un repositorio git: working directory, staging area (index o cache) y repositorio (.git)
  - Estados de un archivo: untracked (U), tracked (modified (M), staged (A), committed)
  - add/commit/reset y status/log/show

<!-- ### Día 2 (Martes 21 Octubre 2025)

- Primeros pasos con Git (2)
  - Modificación de ficheros
  - Mensajes de commit

- Anatomía de comandos típicos, referencias VS paths

  - HEAD, master, HEAD~1 y otras referencias útiles
  - Referencias por mensaje de commit (:/cadena)

- Integración con otras herramientas y entornos
  - Clientes gráficos
  - Entornos de desarrollo
  - Repositorios remotos: GitHub, GitLab, Bitbucket
    - remotes -> push / pull
    - Clonar un repositorio: clone
- Comprobar el repositorio.
  - git log
  - git show
  - git diff
- Aliases
  - Qué son
  - Cómo crearlos desde el CLI: `git config --global alias.co checkout`
  - Crearlos editando el fichero de configuración: `git config --global -e`
- Ficheros Markdown
  - Qué son
  - Sintaxis básica
  - Vista previa en VSC / GitHub / GitLab -->

<!-- ### Día 3 (Miércoles 22 Octubre 2025)

- Git internals
  - Estructura de un repositorio git: .git
  - Objetos git: blobs, trees, commits (y tags)
    - Creación y lectura de objetos
    - Creación del árbol de objetos en un primer commit
    - Modificación del árbol de objetos en commits sucesivos
  - Referencias: heads, ramas (tags y remotes)
  - Taller: creación de un repositorio git "a mano"
- Herramientas para preparar un buen commit en cualquier situación

  - Operaciones en la Staging Area (Index)
    - Añadir ficheros
    - Eliminar de la Staging Area (Index)
  - Eliminar ficheros: git rm
    - Problemas con .gitignore
  - Cambiar nombre de ficheros: git mv
  - git blame
  - Recapitulando: Git básico

### Día 4 (Jueves 23 Octubre 2025)

- Reescribiendo la historia
  - Advertencia
  - git command --amend
    - Ref logs
  - git checkout
  - git reset
  - Evolución de git checkout: Nuevos comandos git switch y git restore
  - git checkout a nivel de archivo (restore)
  - git reset a nivel de archivo -->

<!-- ### Día 5 (Lunes 27 Octubre 2025)

- Reescribiendo la historia (2)
  - rebase interactivo
    - edit: modificando un commit
    - squash y fixup: fusionando commits
    - drop: eliminando un commit
- Otros comandos

  - git clean
  - git revert
  - git bisect

- Trabajando en paralelo

  - Ramas
    - Crear y seleccionar
      - Crear desde referencia
    - Ver ramas
    - Borrar ramas
    - Mover y renombrar ramas
  - Combinación de ramas: Merge y Rebase
    - git merge
      - fast-forward
      - three-way merge
    - git rebase

### Día 6 (Martes 28 Octubre 2025)

- Trabajando en paralelo (2)

  - git stash
  - Resolución de conflictos
  - git cherry-pick

- Etiquetas (tags)
  - Tags anotadas y tags ligeros
  - Crear, listar, eliminar
- Worktrees
- Patches
  - Creación
  - Aplicación -->

<!-- ### Día 7 (Miércoles 29 Octubre 2025)

- Repositorios remotos

  - Repositorios "bare"
  - Clonar repositorios: git clone
  - git remote
  - git push
    - push tags
  - git pull

    - git fetch
    - git merge / git rebase
    - Conflictos

  - Ramas remotas
    - Seguimiento de ramas remotas (tracking branches)
    - Crear ramas locales a partir de ramas remotas: fetch + checkout / switch -c
    - Subir ramas locales a ramas remotas: -u
    - Eliminar ramas remotas
  - Pull requests (GitHub) / Merge requests (GitLab)
    - Flujo de trabajo típico
    - Revisión de código
    - Resolución de conflictos en remoto
    - Buenas prácticas:
      - Actualizar la rama con la rama main antes de hacer el merge
      - Resolución de conflictos en local
      - Eliminar la rama una vez hecho el merge

- ### Día 8 (Jueves 30 Octubre 2025)

- Flujos de trabajo (workflows)

  - Git Flow
  - GitLab Flow
  - GitHub Flow
    - Ship-Show-Ask

- Buenas prácticas

- GitLab
  - Hosting de Repositorios
    - repositorios públicos y privados; ramas y remotos: push y pull (v.s.)
    - forks
  - Colaboración
    - merge requests: revisión de código y comentarios (v.s.)
    - MR desde ramas y forks
    - Proyectos
      - Tableros (Boards)
      - issues y proyectos; milestones
    - Wikis

-->

<!-- Reubicar

- GitLab (continuación)
  - GitLab Pages
    - Configuración y uso
    - Práctica: publicar una web estática generada con Astro
  - Releases
- Integración continua / Entrega continua (CI/CD)
  - Introducción a CI/CD
  - Configuración de un pipeline: stages y jobs
  - Artefactos
  - Variables
  - Despliegues: environments

-->
