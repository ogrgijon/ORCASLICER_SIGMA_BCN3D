# BCN3D Sigma en OrcaSlicer

Perfiles de impresora para laminar modelos 3D con las **BCN3D Sigma, Sigma R17, Sigma R18 y Sigma R19** usando **OrcaSlicer**.

![Impresora BCN3D Sigma R18](BCN3D_SIGMA_ORCA_PROFILE/V.2.05/BCN3D/BCN3D%20Sigma%20R18_cover.png)

> **No es firmware.** Este proyecto contiene perfiles para OrcaSlicer; no instala ni actualiza el firmware de la impresora.

## Empieza aquí

1. Descarga el repositorio: pulsa **Code → Download ZIP** en GitHub y descomprime el archivo.
2. Abre `BCN3D_SIGMA_ORCA_PROFILE/V.2.05`.
3. Copia **todo el contenido** de esa carpeta.
4. Pégalo dentro de la carpeta `resources\profiles` de OrcaSlicer.
   - En una instalación habitual de Windows: `C:\Program Files\OrcaSlicer\resources\profiles`
   - Si OrcaSlicer está instalado en otra ubicación, busca `resources\profiles` dentro de su carpeta de instalación.
5. Reinicia OrcaSlicer y selecciona el perfil adecuado para tu modelo Sigma, la boquilla de **0,4 mm** y los perfiles de proceso y filamento que quieras usar.

## Perfiles incluidos

La versión actual incluye:

| Tipo | Perfiles |
|---|---|
| Impresora | BCN3D Sigma, Sigma R17, Sigma R18 y Sigma R19; boquilla de 0,4 mm |
| Calidad de impresión | Extra Fine (0,06 mm), Fine (0,10 mm), Normal (0,15 mm), Draft (0,20 mm) |
| Filamento | PLA, ABS y PETG genéricos |

## Versiones

Cada edición se guarda en su propia carpeta dentro de `BCN3D_SIGMA_ORCA_PROFILE`, para poder conservar las versiones anteriores y añadir nuevas sin reemplazarlas.

### V.2.05 — versión de configuración 02.05.00.58

Esta versión está identificada en `BCN3D_SIGMA_ORCA_PROFILE/V.2.05/BCN3D.json` y contiene los perfiles indicados arriba, además de los recursos gráficos de la impresora y la superficie de impresión.

## El proyecto y OrcaSlicer

La BCN3D Sigma es una impresora 3D de doble extrusión independiente (IDEX). OrcaSlicer es un laminador: convierte modelos 3D en instrucciones G-code usando la impresora, el proceso y el material seleccionados.

BCN3D ha publicado recursos de hardware abierto de la Sigma. Este repositorio comunitario aporta únicamente perfiles para OrcaSlicer y no está afiliado oficialmente a BCN3D.

### Enlaces oficiales

- [Diseño mecánico BCN3D Sigma](https://github.com/BCN3D/BCN3DSigma-Mechanics)
- [Electrónica BCN3D Sigma](https://github.com/BCN3D/BCN3DSigma-Electronics)
- [Firmware BCN3D Sigma](https://github.com/BCN3D/BCN3DSigma-Firmware)
- [Proceso de fabricación BCN3D Sigma](https://github.com/BCN3D/BCN3DSigma-Process)
- [Código fuente de OrcaSlicer](https://github.com/OrcaSlicer/OrcaSlicer)

## Compatibilidad

Los perfiles están destinados a las **BCN3D Sigma, Sigma R17, Sigma R18 y Sigma R19**, con boquilla de **0,4 mm**. Comprueba que el perfil seleccionado corresponda exactamente a tu modelo y configuración.

## Aviso importante

Este es un proyecto comunitario de investigación y sus perfiles se proporcionan **tal cual**, sin garantía de que sean adecuados para cada impresora, revisión, material o modificación. Revisa y valida todos los parámetros frente a la documentación de tu impresora antes de usarlos. Una configuración incorrecta puede causar fallos de impresión o daños en la impresora, sus componentes o el material.

Utiliza los perfiles bajo tu propia responsabilidad y supervisa las impresiones, especialmente las primeras pruebas. Este proyecto no está afiliado ni respaldado oficialmente por BCN3D.
