# FELD – Windows installers

**FELD** is a music studio with a sequencer, a mixer, a rack of instruments and effects, and AI helpers.
It runs in the browser and as a desktop app for Windows.

FELD is **freeware**. It is **not open source**: this repository holds only the finished installers, not the program's source code.

- Website and sign-in: <https://feld.loehrmann.de>
- Terms of use: <https://feld.loehrmann.de/terms>
- Third-party licenses: <https://feld.loehrmann.de/licenses>

## Download

Get the newest installer from the [Releases](../../releases) page: `FELD-<version>-x64.msi` (Windows, 64 bit).
You can also use the "Windows app" link in the project menu of the studio on the website.

Versions are numbered by date: `v26.289` is the 289th day of 2026 (the last two digits of the year, then the number of the day, 1 January is day 1).

## Install

1. **Unblock the file once.** FELD is not signed with a paid code-signing certificate, so Windows marks downloaded files and may warn you.
   Right-click the downloaded `.msi` -> **Properties** -> tick **Unblock** at the bottom -> **OK**.
   If Windows still shows "Windows protected your PC", click **More info** -> **Run anyway**.
2. **Double-click the `.msi`.** Windows asks for an administrator, because FELD is installed for all users into `C:\Program Files\FELD`.
   All files are ordinary files in that one folder, there is no self-extracting setup.
3. **Sign in.** You need an account (login ID and password) on <https://feld.loehrmann.de>. New accounts are unlocked by hand.
   The same account works in the browser and in the app, on a limited number of devices.

### Update

Install the newer `.msi` over the old one. If Windows says another version is installed, uninstall FELD first (Settings -> Apps).
Your projects are kept, they are not in the program folder.

If you used an older setup program (`FELD_..._x64-setup.exe`), uninstall it first: it is a different product.

## Your projects

Every project is a folder of its own, named like the project, in
`%LOCALAPPDATA%\app.feld.studio\projects\<project name>\`. The `.feld` file in it is the project; the same file opens in the web app.
Make your own copies of what matters to you.

## Support the work

FELD is free to use. If you like it, you can support its development with a voluntary donation. It unlocks nothing and is never required.
The link is on the sign-in page of <https://feld.loehrmann.de>.

## Contact

Hagen Löhrmann · hagen@loehrmann.de

© 2026 Hagen Löhrmann. All rights reserved. VST is a trademark of Steinberg Media Technologies GmbH. Windows is a trademark of Microsoft Corporation.
FELD is not affiliated with or endorsed by them.
