# Antivirus

## What is an antivirus?

It is the **security guard** of your device: it watches files and programs and warns you (or blocks) if something looks dangerous.

!!! success "Good news"
    You don't need to buy anything. **Windows** and **macOS** already include their own protection. All you have to do is **check that it is switched on**.

## Step 1: check your protection

=== "Windows"

    1. Open the Start menu and type **Windows Security**. Open it.
    2. Go to **Virus & threat protection**.
    3. You should see a message like **"No actions needed"**.
    4. If there is a red or yellow warning, click the button it suggests.

    For the curious, from **PowerShell**:

    ```powershell
    Get-MpComputerStatus | Select-Object AntivirusEnabled, RealTimeProtectionEnabled
    ```

    If both answers are `True`, everything is fine.

=== "macOS"

    macOS protects automatically with **Gatekeeper** and **XProtect**. To strengthen it:

    1. Open **System Settings → Privacy & Security**.
    2. Scroll down to **Security**.
    3. Under "Allow applications from", keep **App Store and identified developers**.
    4. Turn on **FileVault** (encrypts the disk) and the **Firewall** (under Network).

## Step 2: run a scan

=== "Windows"

    In **Virus & threat protection**, click **Quick scan**. It takes a few minutes.

=== "macOS"

    macOS has no manual scan button. If you want one, you can install a free antivirus from a well-known brand **downloaded only from its official website**.

## Step 3: good habits

An antivirus is useless if you open the door yourself. Remember:

1. **Download programs only from official sources** (App Store, Microsoft Store or the maker's website).
2. **Don't install "cracked"** or "free" programs from strange pages: they often carry viruses.
3. **Don't open attachments** from people you don't know.
4. **Don't plug in USB sticks** found on the street.

- [ ] My antivirus is on
- [ ] I have run a quick scan
- [ ] I only download programs from official sources

??? question "Do I need to pay for an antivirus?"
    For normal use, no. The protection that comes with your system is enough if you have good habits and everything is up to date.

??? question "What if I have two antiviruses at once?"
    It's not a good idea: they can interfere with each other and slow the computer down. Use only one.

??? question "Don't Macs get viruses?"
    That's a myth. There are fewer, but they exist. That's why you should also keep the Mac updated and be careful what you download.

!!! danger "Signs that something is wrong"
    - The device suddenly becomes **very slow**.
    - **Pop-up windows** keep appearing.
    - Programs you **didn't install**.
    - Your browser changes its search engine or home page by itself.

    If this happens, run a scan and change your passwords **from another device**.
