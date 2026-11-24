# Before you start

## What you need

You don't need to install anything special. You only need:

- [x] A computer running **Windows** or **macOS**, or a phone.
- [x] An internet connection.
- [x] About **30 minutes** to go step by step.
- [x] Pen and paper (to write important things down in a safe place).
- [x] Your phone at hand (we will use it for two-step verification).

!!! warning "Important"
    **Never** write your passwords in a computer file called "passwords.txt". If someone gets in, they will find it right away.

## Find out which system you use

=== "Windows"

    1. Press the key with the Windows logo :fontawesome-brands-windows: on your keyboard.
    2. Type **Settings** and open it.
    3. Go to **System** and scroll down to **About**.
    4. You will see whether you have **Windows 10** or **Windows 11**.

=== "macOS"

    1. Click the apple logo :fontawesome-brands-apple: at the top left.
    2. Choose **About This Mac**.
    3. You will see the name and number of your macOS version.

## Quick check of your current state

Before starting, note how you are doing now. That way you will see your progress at the end.

- [ ] I use **different** passwords for my important accounts.
- [ ] My device is **up to date**.
- [ ] My protection (antivirus) is **switched on**.
- [ ] I have a **backup** of my photos and documents.
- [ ] I can recognise a **fake message**.
- [ ] I avoid connecting to **unknown** Wi-Fi networks without care.

??? note "What if I can't tick any?"
    That's normal at the start. Don't worry: that's what this guide is for. Go step by step.

## Optional commands (for the curious)

If you feel like it, you can ask your device for information with a command. **It is not required** and it changes nothing: it only shows information.

=== "Windows"

    Open **PowerShell** (search for it in the Start menu) and type:

    ```powershell
    Get-MpComputerStatus | Select-Object AntivirusEnabled, RealTimeProtectionEnabled
    ```

    If you see `True` in both fields, your antivirus is active.

=== "macOS"

    Open the **Terminal** app (search with `Cmd + Space`) and type:

    ```bash
    fdesetup status
    ```

    If it answers `FileVault is On.`, your Mac's disk is encrypted.
