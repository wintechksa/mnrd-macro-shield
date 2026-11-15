# MNRD | Macro Shield

**Protect what you built.**

Keep your VBA code under your control.

## Download

Download **MacroShield.exe** from the [latest release](https://github.com/wintechksa/mnrd-macro-shield/releases/latest). The Windows client is a standalone EXE with its dependencies embedded. Microsoft Excel is needed for Excel-dependent processing features. Windows and .NET Framework 4.5 or later are required.

## Excel protection

- Drag and drop one or multiple Excel files, or browse to select them.
- Configure VBA project visibility and hide/unhide standard modules in the editor.
- Use binary-style or randomized standard-module names and optional reserved dummy modules.
- Follow processing progress in the activity log and file queue.
- Switch between light and dark themes.

Original files are preserved. Output copies are saved automatically in the same folder using the `_mnrd` suffix. Existing copies are not overwritten, and the output folder opens after processing.

Editor visibility protection is not workbook-data encryption or a guarantee against copying or recovery. Test generated copies before distributing workbooks.

## Activation and privacy

Open **Settings → Activate Macro Shield** and send your PC Code privately to the app owner. Paste the individual license code supplied by the owner, or import your `.lic` file. Licenses can be Lifetime or have an expiry date.

The current licensing system requires explicit online registration. Missing registrations are blocked. Deleted licenses are permanently revoked; restoring access requires a new license rather than reactivating the deleted one. Use the latest client to receive the current licensing protections.

First verification requires internet. A previously verified active license has up to 24 hours of offline grace. Known revoked licenses remain blocked offline. Check intervals and GitHub caching can delay remote changes; an offline PC cannot receive a new status immediately.

Names, PC Codes, license codes and private owner history are not published here. Public status files contain anonymous signed license hashes and states only. The private License Manager, login credentials, signing keys and GitHub token are never included in client downloads.

## Updates

Open **Settings → Check for updates** and choose **Update now**. The client verifies the signed update manifest, EXE checksum, size and version before replacing the existing executable and restarting. Activation is preserved, and temporary update files are cleaned up.

Release downloads contain:

- `MacroShield.exe` — client application
- `update.json` — signed update information

The automatically generated GitHub source archives contain this public repository's documentation and public status files, not the private application source or owner tools.

## Third-party component

The client embeds OpenMcdf. Its license notice is included in the application and in [OpenMcdf-LICENSE.txt](OpenMcdf-LICENSE.txt). See the [OpenMcdf project](https://github.com/openmcdf/openmcdf) for its source and licensing.
