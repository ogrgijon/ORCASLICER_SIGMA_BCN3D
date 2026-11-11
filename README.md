# Perfiles de BCN3D Sigma R18 para OrcaSlicer

![Impresora BCN3D Sigma R18](BCN3D_SIGMA_ORCA_PROFILE/V.2.05/BCN3D/BCN3D%20Sigma%20R18_cover.png)

Este proyecto reúne perfiles de configuración para usar la **BCN3D Sigma R18** con **OrcaSlicer**. La Sigma es una impresora 3D de doble extrusión independiente (IDEX); estos archivos permiten seleccionarla y laminar modelos con parámetros de máquina, calidad y material apropiados. No es firmware ni lo modifica.

La BCN3D Sigma forma parte de la iniciativa de hardware abierto de BCN3D. La empresa ha publicado en GitHub recursos oficiales de diseño mecánico, electrónica y firmware. Este repositorio comunitario se centra únicamente en los perfiles para OrcaSlicer y no es un proyecto oficial de BCN3D.

### Proyectos oficiales relacionados

- [BCN3D Sigma: diseño mecánico](https://github.com/BCN3D/BCN3DSigma-Mechanics)
- [BCN3D Sigma: electrónica](https://github.com/BCN3D/BCN3DSigma-Electronics)
- [BCN3D Sigma: firmware](https://github.com/BCN3D/BCN3DSigma-Firmware)
- [BCN3D Sigma: proceso de fabricación](https://github.com/BCN3D/BCN3DSigma-Process)
- [OrcaSlicer](https://github.com/OrcaSlicer/OrcaSlicer)

## Versiones y contenido

Las configuraciones se organizan por versión dentro de `BCN3D_SIGMA_ORCA_PROFILE`, para mantener disponibles distintas ediciones y poder añadir futuras versiones sin sobrescribir las anteriores. Cada carpeta de versión contiene el paquete completo para OrcaSlicer.

### Versión actual: V.2.05

El archivo `BCN3D_SIGMA_ORCA_PROFILE/V.2.05/BCN3D.json` identifica esta configuración como la versión **02.05.00.58** para la **BCN3D Sigma R18**. Incluye:

- Configuración de la BCN3D Sigma R18 con boquilla de 0,4 mm.
- Perfiles de proceso Extra Fine (0,06 mm), Fine (0,10 mm), Normal (0,15 mm) y Draft (0,20 mm).
- Perfiles de filamento genéricos PLA, ABS y PETG.
- Recursos gráficos de la impresora y la superficie de impresión.

## ¿Qué es OrcaSlicer?

OrcaSlicer es un programa de laminado (*slicer*) para impresión 3D. Convierte un modelo 3D en instrucciones de impresión (G-code), aplicando los parámetros de la impresora, el material y la calidad seleccionados. Estos perfiles permiten preparar trabajos para la Sigma R18; no actualizan el firmware de la impresora.

## Instalar los perfiles

1. Descarga el repositorio como ZIP y descomprímelo.
2. Abre la carpeta de la versión que quieras usar, por ejemplo `BCN3D_SIGMA_ORCA_PROFILE/V.2.05`, y copia **todo su contenido**.
3. Pégalo en la carpeta `resources\profiles` de OrcaSlicer. En Windows, normalmente está en `C:\Program Files\OrcaSlicer\resources\profiles`. Si instalaste OrcaSlicer en otra ubicación, busca `resources\profiles` dentro de su carpeta de instalación.
4. Reinicia OrcaSlicer. Selecciona la **BCN3D Sigma R18** y el perfil de boquilla de 0,4 mm; después elige el proceso y filamento que quieras usar.

## Compatibilidad

El paquete identifica la impresora como **BCN3D Sigma R18** y está preparado para una boquilla de **0,4 mm**. Verifica los perfiles y los parámetros antes de imprimir, especialmente si tu impresora tiene otra revisión, boquilla o configuración.
