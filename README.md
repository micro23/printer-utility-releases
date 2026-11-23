# Printer Utility

Find and add network printers with a few clicks.

**[Download for macOS](https://github.com/micro23/printer-utility-releases/releases/latest/download/Printer-Utility.zip)** · [Mac release notes](https://github.com/micro23/printer-utility-releases/releases/latest)

**[Download the Windows 11 x64 preview](https://github.com/micro23/printer-utility-releases/releases/download/windows-preview-v4.4.0-3/Printer-Utility-Windows-x64.zip)** · [Windows preview notes and checksum](https://github.com/micro23/printer-utility-releases/releases/tag/windows-preview-v4.4.0-3)

## Windows 4.4.0 preview 3

In File Explorer, select **Extract All**, then open **Printer Utility.exe** inside the extracted folder. Keep the files together. Python is included. The app uses the Microsoft Edge WebView2 Runtime and .NET Framework 4.8 or later.

For a first test, open the application menu and choose **Check Windows setup…**. Confirm that it shows **4.4.0 preview 3**. It checks adapter and queue access, direct driverless setup and eligible installed drivers for older printers. It also shows when Windows protected print mode blocks those older drivers. Use **Copy results** to save the summary. Add one designated test printer, compare its driver and address in its Windows queue, and send one test page. Check for that page at the printer.

Connect to your organization's network or VPN, choose your building, select a printer, and click **Add printer…**. You can also enter a printer address or a Windows print share. Installed printers have shortcuts to the Windows queue and printing preferences.

Start with **Automatic** for a driverless network printer. If an older printer needs a specific Windows driver, choose **Connection options…** and use the connection type, queue name and driver supplied by your IT team. For a USB printer, **Find printers in Windows…** opens the Windows device setup. Refresh the app after Windows adds the printer.

This portable preview is unsigned. Its interface, directory and simulated printer workflows were verified on macOS. Native Windows startup, changes to real queues and physical printing still await PC testing. If your organization's policy requires signed software, contact your IT team.

## macOS

1. Download and expand the ZIP file.
2. Move the app to Applications.
3. Open the app while connected to your organization's network or VPN.
4. The app matches your local IP address to the building ranges in the printer directory and opens the matching building. Otherwise, choose your building when prompted, or browse all buildings. Search by printer, building, or address whenever needed.
5. Click a printer row or its checkbox to select it, then click **Add printer** and keep or change its name. Select several printers to add them together; clicking one again removes only that printer from your selection.

Click **Refresh** to load current printer names and inventory changes from the maintained directory. Routine directory edits do not require an app update.

Use **Add by address** for a printer with a known hostname, IP address, or printer URL. For older printers, enter the exact make and model from the printer label to help match a driver.

Building matching uses the local IP address range even on a wider shared network. Unmapped or conflicting ranges require a building choice; remote VPN addresses are excluded. A building choice checks only that building’s printers; browsing all buildings does not scan the whole directory.

Check nearby shows printers discovered on your network, including printers listed under other buildings. Its heading identifies the nearby view, and Check status checks only those displayed printers. Turn it off to return to your building.

Search results automatically check their current connection status. Checks follow list order and progress stays visible while you select printers. A clear confirmation appears after a printer is added; printing a test page is always your choice. Modern is the default appearance. Choose Classic or Modern in Settings; saved choices are preserved across updates. Classic follows your Mac’s light/dark appearance; Modern adds a photographic workspace with a quieter printer list, clear selection accents, and distinct primary and disabled actions. Keyboard controls, Reduce Motion, Reduce Transparency and Increase Contrast are supported.

Setup keeps your selection intact. If you close the app while setup is running, you can keep it open or stop safely after the current step; completed additions are kept.

The current build requires an Apple Silicon Mac and macOS 12 or later. The latest release is signed with the organization's Apple Developer ID certificate, notarized by Apple, and includes a stapled notarization ticket. Gatekeeper acceptance is verified before publication. If managed-device policy blocks opening it, contact your IT support team for installation assistance.

The app checks for updates at launch and prompts when one is available. You can also choose **Check for Updates…** from the app menu. Updates are verified using the app's existing Sparkle signing key. No GitHub account or token is needed for downloads or update checks.

This repository distributes compiled app releases, checksums, and the update feed. The application's source code is maintained separately and is not published here. GitHub's automatic “Source code” archives contain only this repository's download documentation.

[Update feed](https://github.com/micro23/printer-utility-releases/releases/latest/download/appcast.xml)
