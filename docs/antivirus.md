# Antivirus

## ¿Qué es un antivirus?

Es el **guardia de seguridad** de tu dispositivo: vigila los archivos y los programas y avisa (o bloquea) si algo parece peligroso.

!!! success "Buena noticia"
    No necesitas comprar nada. **Windows** y **macOS** ya incluyen protección propia. Lo único que tienes que hacer es **comprobar que está activada**.

## Paso 1: comprueba tu protección

=== "Windows"

    1. Abre el menú Inicio y escribe **Seguridad de Windows**. Ábrela.
    2. Entra en **Protección antivirus y contra amenazas**.
    3. Debes ver un mensaje como **"No se requieren acciones"**.
    4. Si hay un aviso en rojo o amarillo, pulsa el botón que te sugiere.

    Para curiosos, desde **PowerShell**:

    ```powershell
    Get-MpComputerStatus | Select-Object AntivirusEnabled, RealTimeProtectionEnabled
    ```

    Si las dos respuestas son `True`, todo está bien.

=== "macOS"

    macOS protege de forma automática con **Gatekeeper** y **XProtect**. Para reforzarlo:

    1. Abre **Ajustes del Sistema → Privacidad y seguridad**.
    2. Baja hasta **Seguridad**.
    3. En "Permitir aplicaciones de", deja **App Store y desarrolladores identificados**.
    4. Activa **FileVault** (cifra el disco) y el **Firewall** (en Red).

## Paso 2: haz un análisis

=== "Windows"

    En **Protección antivirus y contra amenazas** pulsa **Análisis rápido**. Tarda unos minutos.

=== "macOS"

    macOS no trae botón de análisis manual. Si quieres uno, puedes instalar un antivirus gratuito de una marca conocida **descargado solo desde su web oficial**.

## Paso 3: buenos hábitos

Un antivirus no sirve de nada si tú abres la puerta. Recuerda:

1. **Descarga programas solo de sitios oficiales** (App Store, Microsoft Store o la web del fabricante).
2. **No instales programas "crackeados"** o "gratis" de páginas raras: suelen traer virus.
3. **No abras archivos adjuntos** de personas que no conoces.
4. **No insertes memorias USB** encontradas por la calle.

- [ ] Mi antivirus está activado
- [ ] He hecho un análisis rápido
- [ ] Solo descargo programas de sitios oficiales

??? question "¿Necesito pagar un antivirus?"
    Para un uso normal, no. La protección que trae tu sistema es suficiente si tienes buenos hábitos y todo actualizado.

??? question "¿Y si tengo dos antivirus a la vez?"
    No es buena idea: pueden molestarse entre sí y ralentizar el equipo. Usa solo uno.

??? question "¿Los Mac no tienen virus?"
    Es un mito. Hay menos, pero existen. Por eso también conviene mantener el Mac actualizado y tener cuidado con lo que se descarga.

!!! danger "Señales de que algo va mal"
    - El equipo va **muy lento** de repente.
    - Aparecen **ventanas emergentes** constantes.
    - Programas que **no instalaste**.
    - Tu navegador cambia de buscador o de página de inicio solo.

    Si te pasa, haz un análisis y cambia tus contraseñas **desde otro dispositivo**.
