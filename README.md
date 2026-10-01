# CaseNoter for Windows

CaseNoter is a desktop app for Housing Hope staff using Apricot. One installer includes **Housing** and **Education & Employment (EE&T)**.

**[Download CaseNoter-Setup.exe](https://github.com/GearUnclear/casenoter-dist/releases/latest/download/CaseNoter-Setup.exe)** · [All releases](https://github.com/GearUnclear/casenoter-dist/releases)

## Install

1. Download **CaseNoter-Setup.exe** and run it using your ordinary Windows account. No administrator password is required.
2. Keep the default folder, `C:\Casenoter`, or choose a folder you can write to if your computer blocks that location.
3. Choose **Housing** or **Education & Employment (EE&T)**. Both departments are installed; this selects which one opens.
4. Select the desktop shortcut option if you want one, finish Setup, and open **CaseNoter**.

The app requires 64-bit Windows 10 (version 1809 or later) or Windows 11. Setup installs Microsoft WebView2 if needed; that step requires internet access. If it fails, check your connection and run Setup again. No separate .NET runtime, helper download, HTML file, or ZIP extraction is needed.

## Connect your account

Follow the setup steps inside CaseNoter. Choose a passphrase, open Bonterra's credential page, and create credentials under **your own staff account**. Paste the Client ID and Client Secret into CaseNoter. The app verifies your connection before syncing participants.

New credentials can take time to activate; follow the app's retry instructions. Your passphrase encrypts your credentials on this computer.

## Move your existing browser setup

Keep your original installation and helper running while you transfer. The browser and desktop apps can stay open together.

1. In the desktop app, choose **Move my existing setup** on first launch or in Settings. Choose the correct source if several are found.
2. In your original browser profile, check the source folder and pairing code, then choose **Allow this one-time transfer**. If the transfer link opens the wrong profile, copy it into the browser profile you used for CaseNoter.
3. Return to the desktop app and enter your **existing CaseNoter password**. If both departments are present, use the password for the department selected on the transfer page.
4. Choose **Import and open CaseNoter**. Confirm replacement if matching data already exists. CaseNoter restores and opens automatically.
5. Check both departments before removing the old installation. Each department keeps its original password.

**Older browser versions, including v2.6.9.5:** if the browser opens normal CaseNoter instead of a transfer page, cancel the connection. In the browser app's Settings, choose **Export my setup**. Select that encrypted file in the desktop import panel and enter your original password. Use this file export/import method when moving to another computer, too. A folder alone cannot recover your browser vault.

Imported pending requests remain available for review and are never automatically resubmitted. Check Apricot before entering uncertain work again. Keep your original installation and backup until the transfer succeeds.

## Open, pin, and change department

Open **CaseNoter** from the Start menu or desktop shortcut. To pin it, open the app, right-click its taskbar icon, and choose **Pin to taskbar**. Opening it again focuses the existing window. External links open in your normal browser.

To change department, close CaseNoter, run the installer again, and select the other department. Both departments' credentials and settings are preserved. Unlock the selected department with its own passphrase, or set it up if you have not used it yet.

Finish saves before closing. Closing the window or choosing **Quit** stops the app and its helper. Pending or unconfirmed work is not a successful save.

## Updates, reinstall, and removal

CaseNoter checks for updates when it opens. You can also use **Force check for updates** in Settings. Verified updates install the full app and reopen it automatically after your work is protected. Finish saves, sync, and setup transfers first; follow the prompt for unsaved entries. Updates never submit pending work. Offline or failed checks leave your current app available.

**Existing 3.0.1 RC users:** close CaseNoter and manually run the latest **CaseNoter-Setup.exe** into your existing folder once to enable the desktop updater. Your setup and passwords are preserved. Later supported desktop updates run automatically. Stable installs receive newer stable releases; RC installs can receive newer RC or stable releases. No GitHub account or token is required.

Reinstalling preserves your credentials, settings, and selected department. Local data lives under `%LOCALAPPDATA%\CaseNoter`, independently of the installation folder.

If an interrupted update prevents startup, run `%LOCALAPPDATA%\CaseNoter\Updates\Repair CaseNoter.cmd`. If recovery fails, reinstall the latest desktop package into the same folder and keep your local data.

Remove CaseNoter through **Windows Settings → Apps → Installed apps**. Keep local data when asked unless you intend to delete this computer's credentials, settings, and data. Removing local data may drop unsent work; Apricot records are unaffected.

For help, see the [staff guide](https://housinghopehelp.xyz/api_guide/) or use the app's diagnostics control when contacting support. Never send your passphrase, Client Secret, or participant data with a support request.
