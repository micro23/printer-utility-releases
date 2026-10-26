# Printer Utility for macOS

Find and add network printers with a few clicks.

**[Download the latest app](https://github.com/micro23/printer-utility-releases/releases/latest/download/Printer-Utility.zip)** · [Release notes](https://github.com/micro23/printer-utility-releases/releases/latest)

1. Download and expand the ZIP file.
2. Move the app to Applications.
3. Open the app while connected to your organization's network or VPN.
4. The app matches your local IP address to the building ranges in the printer directory and opens the matching building. Otherwise, choose your building when prompted, or browse all buildings. Search by printer, building, or address whenever needed.
5. Click a printer row or its checkbox to select it, then click **Add printer** and keep or change its name. Select several printers to add them together; clicking one again removes only that printer from your selection.

Building matching uses the local IP address range even on a wider shared network. Unmapped or conflicting ranges require a building choice; remote VPN addresses are excluded. A building choice checks only that building’s printers; browsing all buildings does not scan the whole directory.

Check nearby shows printers discovered on your network, including printers listed under other buildings. Its heading identifies the nearby view, and Check status checks only those displayed printers. Turn it off to return to your building.

Search results automatically check their current connection status. Checks follow list order and progress stays visible while you select printers. A clear confirmation appears after a printer is added; printing a test page is always your choice. Modern is the default appearance. Choose Classic or Modern in Settings; saved choices are preserved across updates. Classic follows your Mac’s light/dark appearance; Modern adds a photographic workspace with a quieter printer list, clear selection accents, and distinct primary and disabled actions. Keyboard controls, Reduce Motion, Reduce Transparency and Increase Contrast are supported.

Setup keeps your selection intact. If you close the app while setup is running, you can keep it open or stop safely after the current step; completed additions are kept.

The current build requires an Apple Silicon Mac and macOS 12 or later. Version 4.3.60 is signed with the organization's Apple Developer ID certificate, notarized by Apple, and includes a stapled notarization ticket. Gatekeeper acceptance is verified before publication. If managed-device policy blocks opening it, contact your IT support team for installation assistance.

The app checks for updates at launch and prompts when one is available. You can also choose **Check for Updates…** from the app menu. Updates are verified using the app's existing Sparkle signing key. No GitHub account or token is needed for downloads or update checks.

This repository distributes compiled app releases, checksums, and the update feed. The application's source code is maintained separately and is not published here. GitHub's automatic “Source code” archives contain only this repository's download documentation.

[Update feed](https://github.com/micro23/printer-utility-releases/releases/latest/download/appcast.xml)
