# xsafe — brand mark

The icon expresses the core thesis: **a single Ethereum multisig (the signing hub)
controls operations on any destination chain.**

- **Center — Ethereum diamond:** the one signing hub. Where authority lives.
- **Spokes:** control radiating outward from that hub to every chain.
- **Six nodes + hexagon ring:** the network of destination chains. Uniform
  and interchangeable — *any* chain.

## Files

| File | Use |
|------|-----|
| `xsafe-icon.svg` | Primary avatar mark on a dark rounded tile (source of truth) |
| `xsafe-mark.svg` | Transparent mark, mid-tones — for light or dark backgrounds |
| `xsafe-icon-{256,400,512}.png` | Rasterized avatar (upload one of these to GitHub) |
| `xsafe-mark-512.png` | Rasterized transparent mark |

## Palette

| Token | Hex | Role |
|-------|-----|------|
| Hub violet (light facet) | `#B7A6FF` | Diamond upper-left |
| Hub violet | `#9A85F7` | Diamond upper-right |
| Hub indigo | `#8B79F3` | Diamond lower-left |
| Hub indigo (deep) | `#6E5CEA` | Diamond lower-right |
| Node | `#C7D2FE` (dark bg) / `#6366F1` (light) | Destination chains |
| Spoke / ring | `#5B6493` (dark bg) / `#94A3B8` (light) | Connections |
| Tile background | `#141A33 → #0A0E1F` | Avatar gradient |

## Setting the GitHub org avatar

GitHub avatars are UI-only and must be raster (PNG/JPG):

1. Go to **https://github.com/organizations/xsafe/settings/profile**
2. Under **Profile picture**, click **Upload a picture…**
3. Choose `xsafe-icon-512.png`, position, and save.

## Regenerating PNGs

```bash
pip install cairosvg
python3 -c "import cairosvg; cairosvg.svg2png(url='xsafe-icon.svg', write_to='xsafe-icon-512.png', output_width=512, output_height=512)"
```
