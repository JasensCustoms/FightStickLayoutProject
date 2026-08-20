# Notice and attribution

Layouts in this repository come from more than one place. Credit is tracked per
layout rather than claimed in bulk. This file is the register of sources.

Every layout's catalogue entry in `README.md` names its origin. If you add a
layout, add its source here.

---

## Sources

### slagcoin.com

Covers: the 21 joystick button arrangements, meaning every file that is not
named `_all_button`.

  https://www.slagcoin.com/joystick/layout.html

Slagcoin published those layout diagrams, drawn to scale with full dimensions, as
a free resource for people building arcade controllers. They have been the
reference for that hobby since 2008. The layout designs, the measurements and the
descriptive text quoted in `README.md` are his.

If the live site is unreachable, the original pages are preserved on the Wayback
Machine:

  https://web.archive.org/web/*/slagcoin.com/joystick/layout.html

### JasensCustoms.com and the Panzer user community

Covers: the 7 all button (leverless) layouts, every file ending `_all_button`.

  https://www.jasenscustoms.com

These layouts were created by JasensCustoms.com and by members of the Panzer user
community. They may draw inspiration from other all button layouts out in the
world, but they are not exact replicas of any of them.

Shared here with the button patterns preserved as designed. Panel outlines,
mounting holes and other cutouts from the original working drawings were left out.

### ASI

Covers: the S24, S30 and B30 layouts: `asi_s24`, `asi_s30`, `asi_b30` and
their `inner_support_` twins, plus the lever mounting hole pattern on the
`GL_PLATE_HOLES` layer in every joystick layout.

  https://asindo.pro/
  https://www.arcadeshock.com

The S24, S30 and B30 layouts are ASI's designs, taken from their commercial
arcade sticks. The B30 is leverless.

IMPORTANT: these layouts were not supplied as files. They were measured by circle
fitting ASI's published product renders, calibrated on the button holes and cross
checked against the lever plate bore and, on the S30, against a second button
size. They are accurate to roughly a third of a millimetre, not exact, and they
are not official ASI files. Anyone cutting from them should verify against a real
stick first.

Credit for the layouts belongs to ASI.

ASI is also the source of the lever mounting hole pattern: the `GL_PLATE_HOLES`
layer in every joystick layout is based on the mounting plate of their GL lever,
symmetrised about the joystick centre. Thank you to ASI for the GL lever layout.

### Twistedsymphony / classicarcadecabinets.com

Covers: the Mortal Kombat 3 / Ultimate Mortal Kombat 3 dedicated cabinet panel:
`mk3_umk3_dedicated`, `mk3_umk3_dedicated_jp` and both `inner_support_` twins.

  https://www.classicarcadecabinets.com/mortal-kombat-3.html

The control panel layout drawing is by Twistedsymphony, published on
classicarcadecabinets.com as a fully dimensioned reference for people restoring
or reproducing the dedicated MK3 cabinet. The hole positions and sizes in these
files are read directly off that drawing.

Unlike the ASI layouts, nothing here was estimated. Every coordinate is a printed
dimension converted by an exact factor of 25.4. Circle fitting on the drawing was
used only to confirm the reading of the dimension chains, not to derive it.

The file is one player's half of that panel. The drawing is a two player cabinet
panel; the mirrored second half and the Start button are cabinet only features and
are not part of this layout. The six buttons and the lever that are here match the
drawing exactly.

The layout is imperial throughout. Holes are 1.125 in and every spacing is a whole
sixteenth of an inch. The files are millimetres because every file here is, so the
conversion is an exact factor of 25.4 with no rounding at any point.

`mk3_umk3_dedicated_jp` keeps Twistedsymphony's button centres unchanged and only
swaps the hardware, to 30 mm Sanwa holes and the universal GL lever plate. The
spacing credit is his; the hardware choices are not from his drawing.

### Industrias Lorenzo

Covers: the lever bore and mounting pattern on `mk3_umk3_dedicated` only.

The 35 mm bore and the four 5.9 mm screw holes on a 65.6 by 75.9 mm rectangle are
taken from Industrias Lorenzo's own Eurojoystick 2 panel mounting drawing. The
dimensions are IL's. They replace the 1.1875 in Happ style lever hole shown on the
Twistedsymphony drawing, because that panel was originally built for an American
lever and an IL boss will not pass through it.

<!--
### Next source

Copy this block when a layout arrives from somewhere new.

Covers: which layouts
Source: link or description
Credit: who designed it, who measured it, who should be named
Terms:  is it published freely, or given with permission
-->

---

## What this repository adds

On top of the source layouts:

- conversion into true scale vector geometry usable directly in CAD and CAM
- joystick mounting hardware, taken from the GL lever mounting plate by ASI
- the 82 mm and 95 mm lever spacing variants
- the 24 mm button variants, scaled 0.8 in both axes
- for the all button layouts, extraction of the button pattern from the original
  working drawings and normalisation of hole sizes to 24.00 and 30.00 mm
- the inner support variants, adding Sanwa OBSF snap in button ear relief slots
  to every button hole
- for the ASI layouts, recovery of the hole pattern from a product render by sub
  pixel circle fitting
- consistent units, origin, layer structure and file naming across the whole set

That work is shared freely. Use it, modify it, cut panels from it, sell those
panels.

## When you publish something made from these files

Credit whoever the layout came from. Check the layout's catalogue entry in
README.md, or the Sources list above, if you are not sure which that is.

## Adding a layout

New layouts are welcome, whether they come from a manufacturer drawing, a
measured cabinet, the community, or your own design. Please make sure the source
is yours to share or is published freely, name whoever should be credited, and
add a block to the Sources section above.
