# MNRD | Macro Shield 4.0

Protect what you built.

Keep your VBA code under your control.

## Windows app

Download **MacroShield.exe** from Releases. It is a single-file application;
no separate DLL or engine executable is required. Windows and .NET Framework
4.5 or later are required. Module renaming and dummy-module creation also need
Microsoft Excel and permitted VBA project access.

The app supports Viewable/Unviewable and Hide/Unhide options, binary-style
standard-module names, optional harmless padding modules, and a UTC property
stamp. The original is preserved. Output is saved beside it with the `_mnrd`
suffix; existing copies are not overwritten.

This is editor visibility protection, not payroll-data encryption or a guarantee
against copying/recovery. Test generated copies before distributing workbooks.

## Activation

A valid offline app license is required. Obtain a PC-bound license from the
owner using the PC code displayed by the activation dialog. Version-3 licenses
remain compatible with this release. Activation stays on the same PC/user when
the client EXE is replaced or moved.

## Updates

Use **Check for updates**. The app reads the latest stable GitHub release and
verifies its signed `update.json` before enabling a download. Downloaded EXEs
are checked against the signed size, SHA-256 hash and version. Updates are
never run or installed automatically. Close the old app, then replace its EXE
with the verified download. An offline update check does not disable your app.

### Release assets

- `MacroShield.exe` — client app
- `update.json` — owner-signed update information

Keep these asset names unchanged. The release tag must match the EXE version,
for example `v4.0.0`. Owners sign each future release with their existing private
update key; neither private key nor owner tools belong in this repository.

## Third-party component

The client embeds the unmodified OpenMcdf 2.2.1.2 compound-file library.
OpenMcdf source and licensing: https://github.com/openmcdf/openmcdf
Its Mozilla Public License 2.0 notice is included as `OpenMcdf-LICENSE.txt`.
