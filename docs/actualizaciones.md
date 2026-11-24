# Actualizaciones

## ¿Por qué actualizar?

Cuando el fabricante descubre un fallo de seguridad, publica una **actualización** que lo arregla. Si no la instalas, **la puerta sigue abierta** y los delincuentes conocen ese fallo.

!!! tip "Resumen"
    Actualizar no es molestar: es **cerrar con llave** una puerta que sabemos que está abierta.

## Paso 1: actualiza el sistema

=== "Windows"

    1. Abre **Configuración** (tecla Windows + `I`).
    2. Entra en **Windows Update**.
    3. Pulsa **Buscar actualizaciones**.
    4. Si hay alguna, pulsa **Descargar e instalar**.
    5. Reinicia cuando te lo pida.

=== "macOS"

    1. Pulsa el logo de la manzana :fontawesome-brands-apple: y abre **Ajustes del Sistema**.
    2. Entra en **General** y después en **Actualización de software**.
    3. Si hay alguna, pulsa **Actualizar ahora**.
    4. El Mac se reiniciará solo.

    Opcionalmente, desde la Terminal puedes ver qué hay disponible:

    ```bash
    softwareupdate --list
    ```

## Paso 2: activa las actualizaciones automáticas

Así no tienes que acordarte.

=== "Windows"

    En **Windows Update**, deja activada la opción de recibir actualizaciones en cuanto estén disponibles. En general Windows ya las instala solo.

=== "macOS"

    En **Actualización de software**, pulsa el icono **(i)** junto a "Actualizaciones automáticas" y activa las casillas de descargar e instalar actualizaciones.

## Paso 3: actualiza también tus programas y tu móvil

- Navegador (Chrome, Edge, Safari, Firefox): se actualiza solo, pero reinícialo de vez en cuando.
- Aplicaciones del móvil: activa las **actualizaciones automáticas** en App Store o Google Play.
- Sistema del móvil: **Ajustes → Actualización de software**.

- [ ] Mi sistema está actualizado
- [ ] Tengo activadas las actualizaciones automáticas
- [ ] Mi móvil está actualizado

??? question "¿Pierdo mis archivos al actualizar?"
    No. Las actualizaciones no borran tus archivos. Aun así, por eso es buena idea tener una [copia de seguridad](copias-seguridad.md).

??? question "Mi ordenador es muy viejo y ya no recibe actualizaciones, ¿qué hago?"
    Si el fabricante ya no da soporte a tu versión, es un riesgo. Lo ideal es cambiar de equipo o de sistema. Mientras tanto, extrema el cuidado y no hagas operaciones con el banco desde él.

!!! warning "Cuidado con los avisos falsos"
    Una ventana del navegador que dice "¡Tu equipo está infectado, actualiza ya!" suele ser una **estafa**. Las actualizaciones reales llegan desde los **ajustes del sistema**, no desde páginas web.
