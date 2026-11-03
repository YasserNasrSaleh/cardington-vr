# Cardington Steel Frame (3D + VR)

A read-only 3D and WebXR walkthrough of the eight-storey composite steel frame built at the BRE Large Building Test Facility, Cardington, UK.

**Live page:** https://yassernasrsaleh.github.io/cardington-vr/

## Features
- 3D model of the full frame: 33 columns per storey, primary/secondary beams, core framing, vertical and plan bracing.
- Plan views for Level 1, Level 2, Levels 3–7 (typical) and Level 8 (roof).
- Hover or tap a member for its ID, grid position, level and length.
- Optional exterior finishes: curtain wall or ribbon glazing, rainscreen cladding over the stair cores, roof plant screen, entrance canopy.
- Optional interior fit-out: core partitions, open-plan desking, glazed meeting rooms, tea points and a reception lobby.
- **VR:** open the page in the Meta Quest Browser and press *Enter VR*.

## VR controls (Meta Quest)
| Control | Action |
|---|---|
| Left stick | Move (hold grip to go faster) |
| Right stick | Snap turn 30° |
| Right trigger | Teleport to the floor you point at |
| Point at a member | Identify it on the wrist panel |
| A / B | Up / down one level |
| X | Finishes on / off |
| Y | Back to the start point |
| Left stick click | Interiors on / off |

## Notes
- Grid 45.0 × 21.0 m; storey heights 4.34 m (ground) and 4.14 m above.
- The exterior envelope and interior fit-out are illustrative only. It is not part of the Cardington test frame.
- Single self-contained `index.html`; three.js r128 is loaded from cdnjs/jsDelivr. WebXR requires HTTPS, which GitHub Pages provides.
