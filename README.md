# StudentHub

StudentHub es una plataforma para gestionar servicios académicos universitarios.
El proyecto será desarrollado colaborativamente utilizando Git y GitHub.

## Funcionalidades

- Gestión de estudiantes
- Gestión de cursos

## Equipo

- Developer A
- Developer B


## Preguntas de reflexión

### 1. ¿Cuál es la diferencia entre `git add` y `git commit`?

`git add` mueve los cambios de un archivo al staging area, marcando qué se va a incluir en el próximo commit, pero todavía no los guarda en el historial. `git commit` toma lo que está en staging y lo guarda permanentemente en el historial del repositorio, con un mensaje que describe el cambio.

### 2. ¿Cuál es la diferencia entre `git push` y `git pull`?

`git push` envía los commits que tienes en tu repositorio local hacia el repositorio remoto (GitHub). `git pull` hace lo contrario: trae los commits que existen en el remoto y los integra a tu copia local.

### 3. ¿Cuál es la diferencia entre un repositorio local y uno remoto?

El repositorio local vive en tu computadora, dentro de la carpeta `.git`, y es donde trabajas directamente. El repositorio remoto (en GitHub) es una copia centralizada en la nube que permite que varias personas colaboren y mantengan una versión común del proyecto.

### 4. ¿Qué problema resuelve una rama?

Una rama permite trabajar en una funcionalidad o cambio de forma aislada, sin afectar el código de `main`. Esto evita que el trabajo en progreso interrumpa el desarrollo de otras personas y permite trabajar en paralelo.

### 5. ¿Qué diferencia existe entre `git merge` y `git rebase`?

`git merge` une dos ramas creando un nuevo commit de fusión, conservando el historial completo con sus bifurcaciones. `git rebase` reescribe el historial, aplicando los commits de una rama como si hubieran comenzado desde el punto más reciente de otra, dejando una línea de historial más limpia.

### 6. ¿Por qué ocurre un conflicto?

Ocurre cuando dos ramas modifican la misma parte de un mismo archivo de forma distinta, y Git no puede decidir automáticamente cuál versión es la correcta.

### 7. ¿Quién debe decidir cómo resolver un conflicto?

La decisión debe tomarla una persona del equipo, no Git. Alguien debe revisar ambas versiones y decidir o combinar el contenido final.

### 8. ¿Qué problema resuelve un Pull Request?

Permite proponer cambios de una rama para integrarlos a otra (normalmente `main`) de forma controlada, dando espacio para que otra persona revise el código antes de integrarlo.

### 9. ¿Por qué es recomendable revisar un Pull Request antes de integrarlo?

Porque permite detectar errores, mejorar la claridad del contenido y asegurar que el cambio cumple con lo esperado antes de afectar a todo el equipo a través de `main`.

### 10. ¿Qué ventaja tiene trabajar en una rama en lugar de modificar directamente `main`?

Protege la estabilidad de `main`, ya que los cambios en progreso no afectan el código principal hasta que están listos, revisados y aprobados.