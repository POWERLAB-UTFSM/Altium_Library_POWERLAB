# Librería de componentes para Altium Designer

## Resumen
Este repositorio corresponde a las librerías de elementos (componentes, esquemáticos, footprints, plantillas, etc.) diseñados para Altium Designer por el equipo de POWERLAB.

## Usar Git con este proyecto
Para descargar este proyecto al computador local:
1. Instalar Git: https://git-scm.com/downloads
1. Instalar Git LFS: https://git-lfs.github.com/
1. Inicializar Git LFS:<br />
`git lfs install`
1. (*Opcional*) Instalar Git Extensions http://gitextensions.github.io/ o algún otro GUI para Git.
1. Ir al directorio principal donde se quiere dejar el repositorio local, y clonar desde el repositorio remoto `https://remote.git`:<br />
`git clone https://remote.git` <br />
En este caso: <br />
`git clone https://github.com/POWERLAB-UTFSM/Altium_Library_POWERLAB.git`

### Usar Git en Altium
1. **Save:** Una vez que los cambios se hayan efectuado, guarda el archivo o proyecto.
1. **Commit:** Click derecho en el archivo o proyecto, luego `Version Control` -> `Commit`. Añade una nota con los cambios hechos. Los cambios permanecerán en el repositorio local hasta que no se suban los cambios con el siguiente comando.
1. **Push:** Cuando se quiere subir al repositorio remoto todos los cambios efectuados, click derecho en el archivo o proyecto, luego `Version Control` -> `Push`.
1. **Check:** Verifica que todo se ha subido correctamente al repositorio remoto.

Para más información: https://www.altium.com/documentation/altium-designer/using-version-control-ad

### Usar Git desde la línea de comandos (manual)
1. **Abrir Bash:** <br /> Una vez que se hayan hecho las actualizaciones, ve al directorio del proyecto, abre la ventana de comandos de Git (Git Bash, u otro) y ejecuta:
1. `git status` <br /> Muestra los cambios hechos.
1. `git add [path/file]` <br /> Prepara los archivos/carpetas efectivos para consolidar (**Commit**). Para añadir todos los archivos a la vez, ejecutar `git add .`.
1. `git commit -m "description"` <br /> Consolida los cambios hechos con su respectiva descripción, y agrega el comentario `description`.
1. `git push origin master` <br /> Sube los cambios desde el repositorio local `origin` y la rama `master`, al repositorio remoto. Cambiar el nombre del repositorio local y rama, de ser necesario.
1. `git pull origin master` <br /> Descarga los últimos cambios desde el repositorio remoto hacia el repositorio local `origin` y la rama `master`.

Para más información: https://git-scm.com/doc

## Otros comentarios
