# SpecGroups

VB6 Group Monitor (`SpecGroups.exe`): loads monitored group names from ADO and enumerates WinNT://POLICE group members via ADSI into list boxes and temp text dumps. Open `SpecGroups.vbp` in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `SpecGroups` (`SpecGroups.vbp`) | VB6 | WinForms exe | ADO-driven ADSI group membership monitor |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `SpecGroups.vbp`

## Requirements

- Visual Basic 6.0 IDE
- ADO / OLE DB for the monitored-group list
- ADSI access to the target WinNT domain

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Old/SpecGroups`.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
