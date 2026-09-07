# Mywsh

VB6 Windows Script Host runner (`mywsh.vbp`) that takes a `.vbs` or `.js` path on the command line and executes it through the `MSScript` ScriptControl, loading helpers from `global.wsh`. Open `mywsh.vbp` in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Project1` (`mywsh.vbp`) | VB6 | WinForms exe | Project1 |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `mywsh.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `msscript.ocx`

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/Mywsh`.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
