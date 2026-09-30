# Guía para subir archivos con GitHub Desktop

Paso a paso para clonar el proyecto, subir tus cambios y mantenerte actualizado.
No se necesita saber nada de programación ni comandos.

---

## PASO 1 — Descargar GitHub Desktop

1. Entrá a **https://desktop.github.com**
2. Hacé click en **Download for Windows**
3. Instalá el programa (siguiente, siguiente, finalizar)

---

## PASO 2 — Iniciar sesión

1. Abrí GitHub Desktop
2. Hacé click en **Sign in to GitHub.com**
3. Se abre el navegador — iniciá sesión con tu cuenta de GitHub
4. Volvé a GitHub Desktop, ya debería aparecer tu nombre

---

## PASO 3 — Clonar el repositorio (solo la primera vez)

> Clonar = bajarte una copia del proyecto a tu PC

1. En GitHub Desktop, hacé click en **File → Clone repository**
2. Hacé click en la pestaña **URL**
3. Pegá esta dirección:
   ```
   https://github.com/Julian-Kellmer/segundo-parcial-unreal
   ```
4. En **Local path** elegí dónde querés guardar la carpeta en tu PC
5. Hacé click en **Clone**
6. Listo — ya tenés el proyecto en tu computadora

---

## PASO 4 — Agregar tus archivos

1. Abrí la carpeta del proyecto en tu PC (la que elegiste en el paso anterior)
2. Copiá o mové tus archivos de Unreal Engine ahí adentro
   - Archivos `.uasset`, `.umap`, carpetas de Content, etc.

---

## PASO 5 — Hacer Commit (guardar tus cambios)

> Commit = registrar los cambios que hiciste con una descripción

1. Volvé a GitHub Desktop
2. Vas a ver en el panel izquierdo la lista de archivos que cambiaron o agregaste
3. Abajo a la izquierda, en el campo **Summary**, escribí una descripción corta de lo que subís
   - Ejemplo: `Agrego escena del nivel 1`
   - Ejemplo: `Actualizo materiales del personaje`
4. Hacé click en el botón azul **Commit to main**

---

## PASO 6 — Hacer Push (subir al repositorio online)

> Push = enviar tus commits a GitHub para que todos los vean

1. Después del commit, arriba aparece el botón **Push origin**
2. Hacé click ahí
3. Listo — tus archivos ya están en GitHub

---

## PASO 7 — Hacer Pull (bajarte los cambios de otros)

> Pull = traer a tu PC los archivos que subieron tus compañeros

**Importante: hacé pull SIEMPRE antes de ponerte a trabajar**

1. Abrí GitHub Desktop
2. Arriba aparece el botón **Fetch origin** — hacé click ahí primero
3. Si hay cambios nuevos, el botón cambia a **Pull origin**
4. Hacé click en **Pull origin**
5. Ahora tu carpeta está actualizada con todo lo que subieron los demás

---

## Flujo de trabajo diario (resumen)

```
Antes de trabajar  →  Pull (traer cambios de otros)
Mientras trabajás  →  Agregás o modificás archivos normalmente
Cuando terminás    →  Commit (describís lo que hiciste)
                   →  Push (subís al repositorio)
```

---

## Errores comunes

**"There are uncommitted changes"**
→ Tenés archivos modificados que no commiteaste. Hacé commit primero y después pull.

**"Merge conflict"**
→ Dos personas modificaron el mismo archivo. Avisale a Julian para resolverlo juntos.

**El botón Push está desactivado**
→ Primero tenés que hacer un commit.

---

## Link del repositorio

https://github.com/Julian-Kellmer/segundo-parcial-unreal

Cualquier duda consultale a Julian.
