# Publicación de Volleyball Manager Dev

## Paso 1: comprobar derechos
Confirma que existe permiso del autor original (Miguel Caldas) para redistribuir **públicamente** esta versión modificada del juego y los recursos.

## Paso 2: publicar el archivo (manual)

Abre https://github.com/Benru98/volleyball-manager-downloads/releases/new

1. En «Choose a tag», escribe y crea exactamente **v0.5.11** (target: main).
2. Título: `Volleyball Manager Dev 0.5.11 — Windows x64`.
3. Pega el texto de `RELEASE_NOTES_0.5.11.md` como descripción.
4. Adjunta el archivo **Volleyball-Manager-Dev-0.5.11-Windows.zip** (el ZIP original del juego, NO el ZIP de la web).
5. Marca «Set as a pre-release» porque aún está en desarrollo.
6. Pulsa «Publish release».

El HTML ya enlaza a esa versión exacta y descargará el ZIP sin más cambios:
https://github.com/Benru98/volleyball-manager-downloads/releases/download/v0.5.11/Volleyball-Manager-Dev-0.5.11-Windows.zip

## Paso 3: activar web pública (manual)

Abre https://github.com/Benru98/volleyball-manager-downloads/settings/pages

En «Build and deployment»: «Source» = **Deploy from a branch**; «Branch» = **main**, carpeta **/(root)**; pulsa **Save**.

La web quedará en https://benru98.github.io/volleyball-manager-downloads/

## Paso 4: comprobar

- Abre la web sin iniciar sesión (por ejemplo en ventana de incógnito).
- Comprueba que los botones descargan el ZIP completo.
- Descomprime el ZIP y ejecuta `Volleyball Manager Dev.exe` en Windows x64.

**Nunca** subas el ZIP de 159 MB a la rama main: GitHub Pages no es el lugar para distribuir el instalador; GitHub Releases sí lo es.
