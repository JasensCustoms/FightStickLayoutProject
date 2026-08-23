# Plexi and 3D printed case

> ## Not yet validated
>
> **As of August 22, 2026, none of these files has been cut, printed or test
> assembled.** The geometry is published as designed, and the numbers in this
> document are measured from the files themselves, but no physical build has
> confirmed that the parts fit together.
>
> Treat everything here as a first release. Cut one of anything before you cut
> six, and expect the tolerances to be the first thing that needs adjusting.
>
> Once a build has been completed this page will be updated to say so, with
> photographs of the assembled case and a list of recommended vendors for the raw
> plexi.

A laser cut acrylic case with 3D printed corner and center supports, sized to take
any of the control panel layouts in the [main repository](../README.md).

Everything here is millimeters. DXF files are the flat cut profiles; STL and STEP
are the printed parts; SLDPRT are the SolidWorks sources.

<img src="preview/top_outline_1_inner_plexi_case_parts.png" alt="Top outline 1, inner layer" width="420"> <img src="preview/cornersupport_3d.png" alt="Corner support" width="260">

## The case at a glance

| | |
|---|---|
| **Footprint** | **451.0 x 303.0 mm** (17.76 x 11.93 in), 30 mm corner radius |
| **Internal height** | **45.0 mm**, set by the supports and the wall shoulders |
| **Overall height** | **62.2 mm**, being 45 plus an inner and outer layer top and bottom |
| **Inner acrylic** | **5.6 mm** extruded, tolerance +/- 10 to 15 percent (5.2 to 6.0) |
| **Outer acrylic** | **3.0 mm** extruded, tolerance +/- 10 percent (2.7 to 3.30) |
| **Fasteners** | M4, into heat set inserts in the printed supports |

The 451 x 303 mm footprint has room for every layout in this repository several
times over. The largest cut envelope in the library is 278.2 x 151.7 mm.

## Bill of materials

**Acrylic, 16 pieces:**

| Qty | Part | Thickness | File |
|---:|---|---|---|
| 1 | Top, inner layer | 5.6 mm | `Top - Outline N - Inner` |
| 1 | Top, outer layer | 3.0 mm | `Top - Outline N - Outer`, same N |
| 1 | Bottom, inner layer | 5.6 mm | `Bottom - Outline N - Inner` |
| 1 | Bottom, outer layer | 3.0 mm | `Bottom - Outline N - Outer`, same N |
| 4 | Short side, inner | 5.6 mm | `Short Side - JCC`, plain or a button variant |
| 4 | Short side, outer | 3.0 mm | `Short Side - JCC`, plain or a button variant |
| 2 | Long side, inner | 5.6 mm | `Long Side - JCC`, plain or a button variant |
| 2 | Long side, outer | 3.0 mm | `Long Side - JCC`, plain or a button variant |

**Inner and outer are different files for the top and bottom**, and the difference
is the fourteen wall slots. Only the inner layer carries them. See below.

**Printed, 6 pieces:**

| Qty | Part | Files |
|---:|---|---|
| 4 | Corner support | `CornerSupport.STL` / `.STEP` / `.SLDPRT` / `.DXF` |
| 1 | Blank center support | `Blank_CenterSupport.STL` / `.STEP` / `.SLDPRT` / `.DXF` |
| 1 | Neutrik center support | `Neutrik_CenterSupport.STL` / `.STEP` / `.SLDPRT` |

**Hardware:**

| Qty | Item |
|---:|---|
| 12 | M4 brass heat set inserts, [ruthex RX-M4x8.1](https://www.amazon.com/dp/B07YSV66Y5) or equivalent |
| 12 | M4 screws, length to suit your stack |

Two inserts per support, one in each end of its 5.6 mm through bore, which is why
the panels carry six 4.1 mm clearance holes each: four corners and two centers,
top and bottom.

You will also want flat head screws for whatever you mount to the top inner panel,
a fight board and up to two OLED screens. **Countersink those holes after cutting**
so the heads sit below the surface and the outer layer can lie flat on top.

## Print settings

PETG, **5 wall loops**. The supports carry the whole case and take the insert
heat, so wall count matters more than infill here.

## The parts

### Top and bottom panels

<img src="preview/top_outline_1_inner_plexi_case_parts.png" alt="Top outline 1, inner layer" width="380"> <img src="preview/top_outline_2_inner_plexi_case_parts.png" alt="Top outline 2, inner layer" width="380">

*Left: Outline 1. Right: Outline 2.*

<img src="preview/bottom_outline_1_inner_plexi_case_parts.png" alt="Bottom outline 1, inner layer" width="380"> <img src="preview/bottom_outline_2_inner_plexi_case_parts.png" alt="Bottom outline 2, inner layer" width="380">

*The matching bottoms. Left: Outline 1. Right: Outline 2.*

**Outline 1 and Outline 2 are the same panel with a different silhouette.** Both
are exactly 451.0 x 303.0 mm with a 30 mm corner radius, and every hole and slot
in them is in the same place to the last decimal. The only difference is the front
and back edge: Outline 1 runs straight across, Outline 2 bows gently outward, so
at 210 mm from center Outline 1 measures 298.285 mm front to back and Outline 2
measures 302.902. Pick the look you want and cut it in both thicknesses.

The bottom inner panel carries the six 4.1 mm mounting holes and the wall slots.
The top inner panel carries those plus:

| Feature | Count | What it is |
|---|---:|---|
| 4.1 mm clearance holes | 6 | the four corner and two center supports |
| 3.3 mm holes | 12 | two fight board mounting clusters of six |
| 2.0 mm holes | 8 | two OLED screen mounts of four |
| 23.9 x 11.9 mm cutouts | 2 | the OLED windows those four fixings surround |

**The cutouts and the 2.0 mm holes take a 0.96 in OLED screen.** There are two
sets, left and right. Cut the side you want and leave the other out, or cut both
if you want a screen at each end.

**The 3.3 mm clusters mount a fight board.** There are two of them for the same
reason: cut both if you like, but only one side is needed. The inner two mounts of
a cluster are worth having if you plan to 3D print a bracket for the board rather
than bolting it straight to the panel.

All four features are **inner layer only**; see the outer layer note below.

> **Countersink every 2.0 and 3.3 mm hole on the inner panels after cutting**, so
> a flat head screw sits below the surface of the plexi. The outer layer lies
> straight on top of the inner one, and a screw head standing proud will hold the
> two apart.

**Wall slots, and why the outer layer has none.** Three 10.3 x 26 mm slots on each
303 mm edge and four 26 x 10.3 mm slots on each 451 mm edge, fourteen in all. The
10.3 mm width takes the laminated wall, nominally 5.6 plus 3.0 equals 8.6 mm, and
still fits at the worst end of both material tolerances, 6.0 plus 3.3 equals 9.3.

The wall tab is 5.0 mm long and the inner layer is 5.6 mm, so the tab stops 0.6 mm
short of the inner layer's outer face and the outer layer caps it. **The outer
layer therefore must not be cut with those fourteen slots**, which is what the
`- Outer` files are for:

<img src="preview/top_outline_1_outer_plexi_case_parts.png" alt="Top outline 1, outer layer" width="380"> <img src="preview/bottom_outline_1_outer_plexi_case_parts.png" alt="Bottom outline 1, outer layer" width="380">

*The outer layers. Left: top. Right: bottom. Same silhouette, the six mounting
holes, and on the top the two connector apertures. Nothing else.*

**The top outer layer also drops the small holes.** The twelve 3.3 mm fight board
mounts and eight 2.0 mm OLED mounts fix hardware to the underside of the top
panel, and their countersunk screw heads sit below the inner layer's surface, so
the 3.0 mm cosmetic layer above them stays solid. Twenty holes plus fourteen slots
come out and the top outer panel goes from 170 entities to 38. The **two
23.9 x 11.9 mm OLED windows stay**, because you have to see the screen.

| Feature | Top inner | Top outer | Bottom inner | Bottom outer |
|---|---:|---:|---:|---:|
| Silhouette | yes | yes | yes | yes |
| Wall slots | 14 | none | 14 | none |
| 4.1 mm mounting holes | 6 | 6 | 6 | 6 |
| 3.3 mm holes | 12 | none | none | none |
| 2.0 mm holes | 8 | none | none | none |
| 23.9 x 11.9 mm OLED windows | 2 | 2 | none | none |

Every outer file is its matching inner with those features deleted and nothing
else touched. Both outlines have an outer version of each panel.

| Layer | Outline 1 | Outline 2 |
|---|---|---|
| Top, inner 5.6 mm | `Top - Outline 1 - Inner - Plexi Case Parts.DXF` | `Top - Outline 2 - Inner - Plexi Case Parts.DXF` |
| Top, outer 3.0 mm | `Top - Outline 1 - Outer - Plexi Case Parts.DXF` | `Top - Outline 2 - Outer - Plexi Case Parts.DXF` |
| Bottom, inner 5.6 mm | `Bottom - Outline 1 - Inner - Plexi Case Parts.DXF` | `Bottom - Outline 2 - Inner - Plexi Case Parts.DXF` |
| Bottom, outer 3.0 mm | `Bottom - Outline 1 - Outer - Plexi Case Parts.DXF` | `Bottom - Outline 2 - Outer - Plexi Case Parts.DXF` |

### Side walls

<img src="preview/long_side_jcc_plexi_case_parts.png" alt="Long side" width="220"> <img src="preview/short_side_jcc_plexi_case_parts.png" alt="Short side" width="500">

| Part | Size | Tabs |
|---|---|---|
| Long side | 55.0 x 235.402 mm | 3 per edge, into the 303 mm panel edges |
| Short side | 170.5 x 55.0 mm | 2 per edge, two pieces per 451 mm panel edge |

The plain walls are the same file for both layers: they carry no slots, so the
inner and outer cut identically. The **button variants below** are the exception.

Both walls are **55.0 mm** across, made of a **45.0 mm** body between the tab
shoulders and a **5.0 mm** tab at each end. The 45 mm body is what sets the
internal height, and it matches the printed supports exactly. The 5 mm tab enters
the 5.6 mm inner layer and stops 0.6 mm short of its outer face, where the 3.0 mm
outer layer caps it.

### Side walls with buttons

<img src="preview/_button_sides.png" alt="Side walls with buttons" width="900">

Both walls come in variants carrying **24 mm buttons at 30 mm centers**, in twos,
threes and fours, centered on the wall in both directions. Twelve files in all.

| | 2 button | 3 button | 4 button |
|---|---|---|---|
| **Long side, inner** | [dxf](Long%20Side%20-%20JCC%20-%202%20Button%20Inner%20-%20Plexi%20Case%20Parts.DXF) | [dxf](Long%20Side%20-%20JCC%20-%203%20Button%20Inner%20-%20Plexi%20Case%20Parts.DXF) | [dxf](Long%20Side%20-%20JCC%20-%204%20Button%20Inner%20-%20Plexi%20Case%20Parts.DXF) |
| **Long side, outer** | [dxf](Long%20Side%20-%20JCC%20-%202%20Button%20Outer%20-%20Plexi%20Case%20Parts.DXF) | [dxf](Long%20Side%20-%20JCC%20-%203%20Button%20Outer%20-%20Plexi%20Case%20Parts.DXF) | [dxf](Long%20Side%20-%20JCC%20-%204%20Button%20Outer%20-%20Plexi%20Case%20Parts.DXF) |
| **Short side, inner** | [dxf](Short%20Side%20-%20JCC%20-%202%20Button%20Inner%20-%20Plexi%20Case%20Parts.DXF) | [dxf](Short%20Side%20-%20JCC%20-%203%20Button%20Inner%20-%20Plexi%20Case%20Parts.DXF) | [dxf](Short%20Side%20-%20JCC%20-%204%20Button%20Inner%20-%20Plexi%20Case%20Parts.DXF) |
| **Short side, outer** | [dxf](Short%20Side%20-%20JCC%20-%202%20Button%20Outer%20-%20Plexi%20Case%20Parts.DXF) | [dxf](Short%20Side%20-%20JCC%20-%203%20Button%20Outer%20-%20Plexi%20Case%20Parts.DXF) | [dxf](Short%20Side%20-%20JCC%20-%204%20Button%20Outer%20-%20Plexi%20Case%20Parts.DXF) |

**Inner and outer follow the same rule as the layouts in the main repository.**
The button passes through both sheets, so the outer layer gets a plain 24 mm hole
and the inner layer gets that hole merged with a Sanwa OBSF ear relief slot,
5 x 29 mm, as a single closed profile. Cut it as one contour.

**The ear slots sit at 45 degrees**, not the 60 the rest of the library uses, and
that was solved rather than picked. At 45 the slot corners tuck almost inside the
hole's own bounding box in both axes at once, which makes it the only angle in the
15 degree family that holds the full web between neighbors **and** the most
material to the top and bottom edges of the wall:

| Slot angle | Web between buttons | To the wall edge |
|---|---:|---:|
| 0 or 90 degrees | 1.000 mm | 10.500 mm |
| 60 or 120 degrees | 6.000 mm | 8.693 mm |
| **45 or 135 degrees** | **5.958 mm** | **10.479 mm** |

Every variant measures **5.958 mm** between adjacent profiles and **10.479 mm**
from a profile to the long edges of the wall. End clearance is generous
throughout: the tightest is the four button short side at **28.229 mm** from the
outermost profile to the end of the wall, and each end of a short side is buried
about 4.8 mm inside a support, so there is plenty left over.

> **Check your buttons against the stack.** Inner plus outer is 8.6 mm of acrylic.
> The ear relief lets the retention ears pass through and spring out underneath,
> which is the whole point of it, but 8.6 mm is at the deep end for a snap in.
> Cut one wall in scrap and try a button before committing to four.

### Printed supports

<img src="preview/cornersupport_3d.png" alt="Corner support" width="250"> <img src="preview/blank_centersupport_3d.png" alt="Blank center support" width="250"> <img src="preview/neutrik_centersupport_3d.png" alt="Neutrik center support" width="250">

*Left to right: corner, blank center, Neutrik center.*

| Part | Size | Notes |
|---|---|---|
| Corner support | 34.599 x 45.0 x 34.599 mm | L shaped, outer corner radiused to match the panel |
| Blank center support | 60.0 x 45.0 x 31.0 mm | mid span on each 451 mm edge |
| Neutrik center support | 60.0 x 45.0 x 31.0 mm | same outside, with a 24 x 24 mm aperture through it |

All three are a straight 45 mm extrusion of a single profile, with one 5.6 mm bore
running the full length for the heat set inserts. The Neutrik version adds a
24 x 24 mm opening for a Neutrik D series panel connector; it is otherwise
identical to the blank.

<img src="preview/cornersupport.png" alt="Corner support profile" width="330"> <img src="preview/blank_centersupport.png" alt="Blank center support profile" width="430">

*The two profiles that ship as DXF. Left: corner. Right: blank center.*

**The corner and blank center supports also ship as DXF**, because that profile is
all they are. If you would rather laminate them from acrylic offcuts than print
them, cut the profile and stack it to 45 mm. The Neutrik support has no DXF,
because its aperture is an internal feature that a single profile cannot describe.

## What is not here

Stated plainly so nobody hunts for a file that was never in the folder:

- **`Neutrik_CenterSupport.DXF`** does not exist. See above.
- **`Top Panel.SLDPRT`** is here without a STEP, STL or DXF companion, so it is
  only usable in SolidWorks.
- **`All Plexi Case Parts.SLDPRT`** is the multibody source for the set.
- **Assembly order and screw lengths** depend on your final stack thickness, which
  moves with the material tolerance, so measure before you buy screws.
- **Countersink depth** is not in the files. It depends on the flat head screws you
  use, and the DXFs carry the through holes only.

## About these files

Eight of the DXFs came straight out of SolidWorks and keep their original
filenames exactly as they came. The other sixteen, the four outer panels and the
twelve button walls, are generated from those eight: features are deleted or added
and the rest of the geometry is carried across untouched, so a wall in a button
variant is the same wall, not a redrawn one.

## License

Same as the rest of this repository: **Creative Commons Attribution-ShareAlike 4.0
International**. See [LICENSE](../LICENSE) and [NOTICE.md](../NOTICE.md).

These case files were created by [JasensCustoms.com](https://www.jasenscustoms.com).
