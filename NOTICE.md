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
their `inner_support_` twins.

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
- joystick mounting hardware, taken from a universal lever mounting plate
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
