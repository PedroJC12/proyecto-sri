# Backups

## Why make them?

Devices break, get lost, stolen or infected. If everything you have is in one place, **you can lose it forever**. A backup is your **plan B**.

## The 3-2-1 rule (explained simply)

| Number | Means | Example |
|---|---|---|
| **3** | Have **3 copies** of what matters | The original + 2 copies |
| **2** | In **2 different kinds of place** | External drive and cloud |
| **1** | **1 copy away from home** | The cloud (internet) |

!!! tip "If that's too much"
    Start with the basics: **one copy on an external drive** and another **in the cloud**. You'll already be better off than most people.

## Step 1: decide what to copy

- [ ] Photos and videos
- [ ] Documents (assignments, invoices, paperwork)
- [ ] Contacts
- [ ] Work or study files

## Step 2: choose where to save

=== "External drive"

    A hard drive or USB stick you plug into the computer. Advantage: it doesn't depend on the internet. Drawback: it can be lost or break, and you have to remember to connect it.

=== "Cloud"

    Services like **iCloud**, **OneDrive** or **Google Drive** store your files on the internet. Advantage: automatic and reachable from anywhere. Drawback: free space is limited.

## Step 3: turn on automatic backup

=== "Windows"

    1. Open **Settings → Accounts → Windows Backup**.
    2. Turn on folder sync with **OneDrive** (Desktop, Documents, Pictures).
    3. You can also use **File History** with an external drive.

=== "macOS"

    **With an external drive (Time Machine):**

    1. Plug in the external drive.
    2. Open **System Settings → General → Time Machine**.
    3. Click **Add Backup Disk** and choose it.

    **With the cloud (iCloud):** in **System Settings**, click your name, go to **iCloud** and turn on **Photos** and **iCloud Drive**.

    To see the backups you already have, from the Terminal:

    ```bash
    tmutil listbackups
    ```

## Step 4: check that it works

A backup that has never been tested **is not a reliable backup**.

1. Pick any file.
2. Find it in the backup (drive or cloud).
3. Open it and check that it looks right.

??? question "How often should I back up?"
    Ideally **automatically and daily**. If manual, at least once a week or before updating the system.

??? question "Is the cloud safe?"
    It is fairly safe if you protect your account with a strong password and [two-step verification](contrasenas.md). For very sensitive documents, add a copy on an external drive.

??? question "What happens to backups if I get a virus?"
    Some viruses also encrypt connected backups. That's why you should **unplug the external drive** when you're not using it.

!!! warning "Don't confuse syncing with copying"
    If you delete a file in a synced folder, **it is also deleted in the cloud**. A backup keeps earlier versions.
