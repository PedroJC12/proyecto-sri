# Antes de empezar

## Qué necesitas

No hace falta instalar nada especial. Solo necesitas:

- [x] Un ordenador con **Windows** o **macOS**, o un móvil.
- [x] Conexión a internet.
- [x] Unos **30 minutos** para ir paso a paso.
- [x] Papel y lápiz (para apuntar cosas importantes en un lugar seguro).
- [x] Tu móvil a mano (lo usaremos para la verificación en dos pasos).

!!! warning "Importante"
    **Nunca** escribas tus contraseñas en un archivo del ordenador llamado "contraseñas.txt". Si alguien entra, lo encontrará enseguida.

## Averigua qué sistema usas

=== "Windows"

    1. Pulsa la tecla con el logo de Windows :fontawesome-brands-windows: en el teclado.
    2. Escribe **Configuración** y ábrela.
    3. Entra en **Sistema** y baja hasta **Acerca de**.
    4. Verás si tienes **Windows 10** o **Windows 11**.

=== "macOS"

    1. Pulsa el logo de la manzana :fontawesome-brands-apple: arriba a la izquierda.
    2. Elige **Acerca de este Mac**.
    3. Verás el nombre y el número de tu versión de macOS.

## Comprobación rápida de tu estado actual

Antes de empezar, apunta cómo estás ahora. Así verás tu progreso al final.

- [ ] Uso contraseñas **distintas** en mis cuentas importantes.
- [ ] Mi dispositivo está **actualizado**.
- [ ] Mi protección (antivirus) está **activada**.
- [ ] Tengo una **copia de seguridad** de mis fotos y documentos.
- [ ] Sé reconocer un **mensaje falso**.
- [ ] Evito conectarme a Wi-Fi **desconocidos** sin cuidado.

??? note "¿Y si no puedo marcar ninguna?"
    Es lo normal al principio. No pasa nada: para eso es esta guía. Ve paso a paso.

## Comandos opcionales (para curiosos)

Si te animas, puedes preguntarle datos a tu dispositivo con un comando. **No es obligatorio** y no cambia nada: solo muestra información.

=== "Windows"

    Abre **PowerShell** (búscalo en el menú Inicio) y escribe:

    ```powershell
    Get-MpComputerStatus | Select-Object AntivirusEnabled, RealTimeProtectionEnabled
    ```

    Si ves `True` en las dos casillas, tu antivirus está activo.

=== "macOS"

    Abre la aplicación **Terminal** (búscala con `Cmd + Espacio`) y escribe:

    ```bash
    fdesetup status
    ```

    Si responde `FileVault is On.`, el disco de tu Mac está cifrado.
