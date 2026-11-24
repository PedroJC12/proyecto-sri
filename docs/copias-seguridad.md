# Copias de seguridad

## ¿Por qué hacerlas?

Los dispositivos se rompen, se pierden, se roban o se infectan. Si lo único que tienes está en un solo sitio, **puedes perderlo para siempre**. Una copia de seguridad es tu **plan B**.

## La regla 3-2-1 (explicada fácil)

| Número | Significa | Ejemplo |
|---|---|---|
| **3** | Tener **3 copias** de lo importante | El original + 2 copias |
| **2** | En **2 tipos de lugar distintos** | Disco externo y nube |
| **1** | **1 copia fuera de casa** | La nube (internet) |

!!! tip "Si es mucho para ti"
    Empieza por lo básico: **una copia en un disco externo** y otra **en la nube**. Ya estarás mejor que la mayoría.

## Paso 1: decide qué copiar

- [ ] Fotos y vídeos
- [ ] Documentos (trabajos, facturas, papeles)
- [ ] Contactos
- [ ] Archivos de trabajo o estudios

## Paso 2: elige dónde guardar

=== "Disco externo"

    Un disco duro o memoria USB que conectas al ordenador. Ventaja: no depende de internet. Inconveniente: puede perderse o romperse, y hay que acordarse de conectarlo.

=== "Nube"

    Servicios como **iCloud**, **OneDrive** o **Google Drive** guardan tus archivos en internet. Ventaja: automático y accesible desde cualquier sitio. Inconveniente: el espacio gratuito es limitado.

## Paso 3: activa la copia automática

=== "Windows"

    1. Abre **Configuración → Cuentas → Copia de seguridad de Windows**.
    2. Activa la sincronización de carpetas con **OneDrive** (Escritorio, Documentos, Imágenes).
    3. También puedes usar **Historial de archivos** con un disco externo.

=== "macOS"

    **Con disco externo (Time Machine):**

    1. Conecta el disco externo.
    2. Abre **Ajustes del Sistema → General → Time Machine**.
    3. Pulsa **Añadir disco de copia** y elígelo.

    **Con la nube (iCloud):** en **Ajustes del Sistema**, pulsa tu nombre, entra en **iCloud** y activa **Fotos** y **iCloud Drive**.

    Para ver las copias que ya tienes, desde la Terminal:

    ```bash
    tmutil listbackups
    ```

## Paso 4: comprueba que funciona

Una copia que nunca se ha probado **no es una copia fiable**.

1. Elige un archivo cualquiera.
2. Búscalo en la copia (disco o nube).
3. Ábrelo y comprueba que se ve bien.

??? question "¿Cada cuánto debo hacer copias?"
    Lo ideal es que sean **automáticas y diarias**. Si son manuales, al menos una vez a la semana o antes de actualizar el sistema.

??? question "¿La nube es segura?"
    Es bastante segura si proteges tu cuenta con contraseña fuerte y [verificación en dos pasos](contrasenas.md). Para documentos muy delicados, añade una copia en un disco externo.

??? question "¿Qué pasa con las copias si me infecto con un virus?"
    Algunos virus también cifran las copias conectadas. Por eso conviene **desconectar el disco externo** cuando no lo uses.

!!! warning "No confundas sincronizar con copiar"
    Si borras un archivo en una carpeta sincronizada, **se borra también en la nube**. Una copia de seguridad conserva versiones anteriores.
