# Jet625 CAD Android

Native Android starter port for Jet625 CAD / Donatoni DXF workflow.

## What is included

- Open DXF files from Android file picker
- Export DXF files with AC1009/R12-style DXF output
- Supports LINE, CIRCLE, ARC, LWPOLYLINE, and old POLYLINE/VERTEX/SEQEND basics
- Keeps Donatoni layer names and operation colors: 0, CUTOUT, WALL, EASE, SEAM, OtherEDGE, Mill, STOVEorFRIDGE
- Touch pan/zoom, draw line/rectangle/circle, select/delete, apply layer
- Chain Check that marks open endpoints with green circles
- Helper/checker graphics are not exported

## Open in Android Studio

1. Open Android Studio.
2. Choose **File > Open**.
3. Select this repository folder.
4. Let Gradle sync.
5. Press **Run**.

## Notes

This is a starter Android version. The original Windows Tkinter app has more tools that still need to be ported, including full sink placement, full dimensions, offset/extend refinements, and the complete desktop UI behavior.
