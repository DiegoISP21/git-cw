# Práctica de commits — Git · ENP6 UNAM

Cada nivel te pide un cambio concreto en este archivo.  
Edita → `git add practica-commits.md` → `git commit -m "..."`

---

## Nivel 1 · Preséntate

**Qué hacer:** Llena los campos con tus datos.  
**Commit:** `feat(perfil): agrega presentación de [tu nombre]`

```
Nombre     : Diego Salcedo Perez
GitHub     : https://github.com/DiegoISP21
Algo sobre mí : Me gusta leer libros de no ficción sobre ciencia o algún tema que puede ayudarme en mi vida
```

---

## Nivel 2 · Lo que ya sabes hacer

**Qué hacer:** Agrega al menos tres cosas que sabes hacer (no tienen que ser de programación).  
**Commit:** `feat(habilidades): agrega lista de habilidades`

- Sé resolver problemas matemáticos complejos
- Aprendo rápido
- Tengo conocimientos en inglés

---

## Nivel 3 · Corrige los errores

**Qué hacer:** El párrafo de abajo tiene **cuatro errores**. Corrígelos todos en un solo commit.  
**Commit:** `fix(convenciones): corrige errores en descripción de Git`

> Git es un sistema de control de versiones creado en 2005 por Linus Torvalds
> para reemplazar a Bitkeeper, que era de licencia y dejó de darse gratis al proyecto Linux.
> Cada commit guarda una fotografía de todos los archivos del repositorio en ese momento,
> identificada con un hash SHA-1 único. Para subir cambios al servidor usamos `git push`.

---

## Nivel 4 · Qué aprendí hoy

**Qué hacer:** Escribe tres cosas concretas que aprendiste en esta sesión.  
**Commit:** `docs(aprendizaje): agrega notas de la sesión`

1. ¿Cómo utilizar github? Se utiliza como un control de versiones para guardar un archivo.
2. ¿Qué es un commit? Es como la captura de un código o un proyecto, ya que es un registro permanente del mismo.
3. ¿Qué es y cómo crear un repositorio? Es una carpeta en el que se registra cada cambio en el proyecto y se utilizan como un historial completo, además de guardar carpetas ocultas que en windows se puede visualizar con el comando dir/a.
4. Las diferencias entre git y github, las cuales tornan en que la primera es una herramienta local, tiene una línea de comandos, es open sourse, etc. y este último es un hospedaje de repositorios remotos, se puede compartir, además de ser una plataforma nube.

---

## Nivel 5 · Tabla de comandos

**Qué hacer:** Completa las celdas vacías de la tabla.  
**Commit:** `docs(comandos): completa tabla de referencia`

| Comando | ¿Qué hace? |
|---------|------------|
| `git init` | |
| `git status` | |
| `git add .` | |
| `git commit -m "..."` | |
| `git log --oneline` | |
| `git push` | |

---

## Nivel 6 · Marca tu avance

**Qué hacer:** Cambia `[ ]` por `[x]` en cada punto que ya dominas.  
**Commit:** `chore(practica): actualiza checklist de avance`

- [ ] Hice `git init` sin ayuda
- [ ] Entiendo para qué sirve el Staging Area
- [ ] Escribí un mensaje de commit con formato Conventional Commits
- [ ] Puedo ver el historial con `git log`
- [ ] Completé todos los niveles de esta práctica

---

## Referencia rápida

| Tipo | Cuándo |
|------|--------|
| `feat` | Agrego algo nuevo |
| `fix` | Corrijo un error |
| `docs` | Solo toco documentación o notas |
| `style` | Formato, sin cambiar contenido |
| `refactor` | Reorganizo sin cambiar el resultado |
| `chore` | Tareas de mantenimiento |
