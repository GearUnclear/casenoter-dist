# CaseNoter for Windows

CaseNoter 3.0 is a Windows desktop app for Housing Hope staff using Apricot. One installer includes **Housing** and **Education & Employment (EE&T)**.

**[Download CaseNoter-Setup.exe](https://github.com/GearUnclear/casenoter-dist/releases/latest/download/CaseNoter-Setup.exe)** · [All releases](https://github.com/GearUnclear/casenoter-dist/releases)

## Install or upgrade to 3.0

**A one-time manual upgrade from CaseNoter 2.x to 3.0 is required.** Download and run the installer below; the browser version's updater cannot perform this upgrade. After installing 3.0, future desktop updates run automatically.

1. Download **CaseNoter-Setup.exe** and run it using your normal Windows account.
2. Keep the default folder, `C:\Casenoter`, or choose a folder you can write to.
3. Choose **Housing** or **Education & Employment (EE&T)**. Both are installed; this selects which department opens.
4. Select the desktop shortcut option if you want one, finish Setup, and open **CaseNoter**.

Requires 64-bit Windows 10 (version 1809 or later) or Windows 11. No administrator password is required. Setup installs Microsoft WebView2 if needed, which requires internet access. If that step fails, check your connection and run Setup again.

## Bring your existing setup from 2.x

Keep your old installation until you have checked that your setup works in the desktop app. Installing 3.0 alone does not copy your browser's saved setup.

1. Open CaseNoter in the browser and unlock it. In **Settings**, choose **Export my setup** and save the encrypted file.
2. Open the desktop app and choose **Move my existing setup**.
3. Select the encrypted export in the import panel and enter your **existing CaseNoter password**.
4. Choose **Import and open CaseNoter**. Confirm replacement if matching data already exists.
5. Check your setup before removing the old installation. If you use both departments, check both; each keeps its original password.

If your browser build supports direct transfer, you can instead keep the old helper running and follow the paired transfer prompts under **Move my existing setup**. If it opens normal CaseNoter rather than a transfer page, use the encrypted export steps above.

Imported pending requests remain available for review and are never automatically resubmitted. Check Apricot before entering uncertain work again.

## Set up a new account

If you do not have an existing setup, follow the steps inside CaseNoter. Choose a passphrase, create Bonterra credentials under **your own staff account**, and paste the Client ID and Client Secret into the app. CaseNoter verifies the connection before syncing participants. New credentials can take time to activate; follow the retry instructions.

## Open and use CaseNoter

Open **CaseNoter** from the Start menu or desktop shortcut. To pin it, open the app, right-click its taskbar icon, and choose **Pin to taskbar**. Opening it again focuses the existing window.

To change department, close CaseNoter and run Setup again. Select the other department and finish installation. Both departments' credentials and settings are preserved.

Finish saves before closing the window or choosing **Quit**. Pending or unconfirmed work is not a successful save.

## Updates and reinstall

The desktop app checks for updates when it opens. You can also choose **Force check for updates** in Settings. Updates install the full app and reopen it automatically after your work is protected. Follow any prompts for unsaved work. Updates never submit pending requests.

Reinstalling preserves your setup, passwords, and selected department. To reinstall, close CaseNoter and run the latest installer into the same folder.

To remove the app, use **Windows Settings → Apps → Installed apps**. Keep local data when asked unless you intend to delete this computer's credentials, settings, and saved data. Apricot records are unaffected.

For help, see the [staff guide](https://housinghopehelp.xyz/api_guide/) or use the app's diagnostics control when contacting support.
