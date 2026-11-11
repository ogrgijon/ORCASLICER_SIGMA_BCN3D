# Perfiles BCN3D Sigma para OrcaSlicer

Perfiles de impresora y laminado para utilizar la familia **BCN3D Sigma** con **OrcaSlicer**.

![Impresora BCN3D Sigma](BCN3D_SIGMA_ORCA_PROFILE/V.2.05/BCN3D/BCN3D%20Sigma%20R18_cover.png)

> **Solo configuraciones:** este repositorio no incluye ni modifica el firmware de la impresora.

## Qué encontrarás

- Perfiles para BCN3D Sigma, Sigma R17, Sigma R18 y Sigma R19.
- Configuraciones para boquilla de 0,4 mm.
- Perfiles de impresión desde Extra Fine hasta Draft.
- Perfiles genéricos de filamento PLA, ABS y PETG.

OrcaSlicer convierte modelos 3D en instrucciones G-code usando la impresora, el proceso y el material seleccionados. Estos perfiles ayudan a configurar esos parámetros para la familia Sigma.

## Instalación rápida

1. En GitHub, pulsa **Code → Download ZIP** y descomprime el repositorio.
2. En `BCN3D_SIGMA_ORCA_PROFILE`, abre la carpeta de la versión que quieras instalar (consulta el [historial de versiones](#versiones-e-historial)).
3. Copia **todo el contenido** de esa carpeta de versión.
4. Pégalo dentro de `resources\profiles` en la carpeta de instalación de OrcaSlicer. En Windows, la ruta habitual es:

   `C:\Program Files\OrcaSlicer\resources\profiles`

   Si instalaste OrcaSlicer en otra ubicación, busca allí la carpeta `resources\profiles`.

5. Reinicia OrcaSlicer y selecciona el perfil de tu Sigma, la boquilla y los perfiles de proceso y filamento adecuados.

## Versiones e historial

Las versiones se guardan en carpetas separadas dentro de `BCN3D_SIGMA_ORCA_PROFILE`. Así puedes elegir la que necesitas y mantener las anteriores cuando se publiquen nuevas ediciones.

| Edición | Versión indicada en el perfil | Estado | Contenido |
|---|---|---|---|
| [V.2.05](BCN3D_SIGMA_ORCA_PROFILE/V.2.05/) | `02.05.00.58` | Actual | Perfiles de máquina, procesos y filamentos; recursos gráficos |

### Detalle de la edición actual

El archivo `BCN3D.json` identifica la configuración como `02.05.00.58`. Incluye boquilla de 0,4 mm, perfiles de proceso Extra Fine (0,06 mm), Fine (0,10 mm), Normal (0,15 mm) y Draft (0,20 mm), y materiales genéricos PLA, ABS y PETG.

## Compatibilidad

Los perfiles están destinados a BCN3D Sigma, Sigma R17, Sigma R18 y Sigma R19. Comprueba que el perfil seleccionado corresponda a tu modelo, boquilla y configuración.

## Proyecto y referencias

La BCN3D Sigma es una impresora 3D de doble extrusión independiente (IDEX). BCN3D ha publicado recursos de hardware abierto; este repositorio comunitario se centra únicamente en perfiles para OrcaSlicer y no está afiliado ni respaldado oficialmente por BCN3D.

- [Diseño mecánico BCN3D Sigma](https://github.com/BCN3D/BCN3DSigma-Mechanics)
- [Electrónica BCN3D Sigma](https://github.com/BCN3D/BCN3DSigma-Electronics)
- [Firmware BCN3D Sigma](https://github.com/BCN3D/BCN3DSigma-Firmware)
- [Proceso de fabricación BCN3D Sigma](https://github.com/BCN3D/BCN3DSigma-Process)
- [Código fuente de OrcaSlicer](https://github.com/OrcaSlicer/OrcaSlicer)

## Aviso de uso

Este es un proyecto comunitario de investigación. Las configuraciones se ofrecen **tal cual**, sin garantía de que sean adecuadas para cada impresora, revisión, material o modificación. Revisa y valida los parámetros frente a la documentación de tu impresora antes de usarlos: una configuración inadecuada puede causar fallos de impresión o daños en la impresora, sus componentes o el material.

Utiliza los perfiles bajo tu responsabilidad y supervisa las impresiones, especialmente las primeras pruebas.
