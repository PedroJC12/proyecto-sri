# Updates

## Why update?

When the manufacturer discovers a security flaw, it releases an **update** that fixes it. If you don't install it, **the door stays open** and criminals know about that flaw.

!!! tip "In short"
    Updating is not a nuisance: it is **locking** a door that we know is open.

## Step 1: update the system

=== "Windows"

    1. Open **Settings** (Windows key + `I`).
    2. Go to **Windows Update**.
    3. Click **Check for updates**.
    4. If there are any, click **Download and install**.
    5. Restart when asked.

=== "macOS"

    1. Click the apple logo :fontawesome-brands-apple: and open **System Settings**.
    2. Go to **General** and then **Software Update**.
    3. If there are any, click **Update Now**.
    4. The Mac will restart by itself.

    Optionally, from the Terminal you can see what is available:

    ```bash
    softwareupdate --list
    ```

## Step 2: turn on automatic updates

That way you don't have to remember.

=== "Windows"

    In **Windows Update**, keep the option to get updates as soon as they are available switched on. Windows usually installs them by itself.

=== "macOS"

    In **Software Update**, click the **(i)** icon next to "Automatic updates" and turn on the options to download and install updates.

## Step 3: also update your programs and your phone

- Browser (Chrome, Edge, Safari, Firefox): updates itself, but restart it from time to time.
- Phone apps: turn on **automatic updates** in the App Store or Google Play.
- Phone system: **Settings → Software update**.

- [ ] My system is up to date
- [ ] I have automatic updates on
- [ ] My phone is up to date

??? question "Do I lose my files when updating?"
    No. Updates don't delete your files. Even so, that is why having a [backup](copias-seguridad.md) is a good idea.

??? question "My computer is very old and no longer gets updates, what do I do?"
    If the manufacturer no longer supports your version, it is a risk. Ideally, change your device or system. Meanwhile, be extra careful and don't do banking from it.

!!! warning "Beware of fake alerts"
    A browser window saying "Your device is infected, update now!" is usually a **scam**. Real updates come from the **system settings**, not from web pages.
