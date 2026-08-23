# Notice and attribution

Layouts in this repository come from more than one place. Credit is tracked per
layout rather than claimed in bulk. This file is the register of sources.

Every layout's catalog entry in `README.md` names its origin. If you add a
layout, add its source here.

---

## Sources

### slagcoin.com

Covers: the 21 joystick button arrangements, meaning every file that is not
named `_all_button`. That includes `american_s_american_parts`, which is the same
Capcom USA arrangement cut for American hardware.

  https://www.slagcoin.com/joystick/layout.html

Slagcoin published those layout diagrams, drawn to scale with full dimensions, as
a free resource for people building arcade controllers. They have been the
reference for that hobby since 2008. The layout designs, the measurements and the
descriptive text quoted in `README.md` are his.

If the live site is unreachable, the original pages are preserved on the Wayback
Machine:

  https://web.archive.org/web/*/slagcoin.com/joystick/layout.html

### JasensCustoms.com and the Panzer user community

Covers: the 7 all button (leverless) layouts, every file ending `_all_button`,
and the Sega 2P IMPACT layouts `jasenscustoms_sega2p_impact` and
`jasenscustoms_sega2p_impact_24mm_buttons`, with their `inner_support_` twins.

  https://www.jasenscustoms.com

These layouts were created by JasensCustoms.com and by members of the Panzer user
community. They may draw inspiration from other all button layouts out in the
world, but they are not exact replicas of any of them.

Shared here with the button patterns preserved as designed. Panel outlines,
mounting holes and other cutouts from the original working drawings were left out.

`case/` holds a laser cut acrylic case with 3D printed corner and center supports,
also created by JasensCustoms.com: twenty four DXF cut profiles, four printed parts
as STL and STEP, and the SolidWorks sources. Eight of the DXFs came straight from
SolidWorks with their original filenames kept exactly; the other sixteen are
derived from those, with features deleted or added rather than anything being
redrawn. The fight board bracket is not from SolidWorks at all: it is modeled
directly from the panel's own hole pattern. Same license as everything else
here.

The Sega 2P IMPACT layouts come from `jasenscustoms-pfs4-mczte-sega2p-IMPACT-withbezel.svg`,
a JasensCustoms cut file for the IMPACT plate that fits the Panzer Fight Stick 4
and the Mad Catz TE. The same rule was applied: the plate outline, its six 3/16 in
mounting screw holes and the control strip window were all left out, and only the
button and lever pattern was kept. The eight main button centers already existed
in this library as the Slagcoin Sega 2P cluster and are credited to slagcoin.com
above; the 24 mm button below the lever is JasensCustoms' addition.

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
size. They are accurate to roughly a third of a millimeter, not exact, and they
are not official ASI files. Anyone cutting from them should verify against a real
stick first.

Credit for the layouts belongs to ASI.

ASI is also the source of the lever mounting hole pattern: the `GL_PLATE_HOLES`
layer in every joystick layout is based on the mounting plate of their GL lever,
symmetrised about the joystick center. Thank you to ASI for the GL lever layout.

### Twistedsymphony / classicarcadecabinets.com

Covers: the Mortal Kombat 3 / Ultimate Mortal Kombat 3 dedicated cabinet panel:
`mk3_umk3_dedicated_american_parts`, `mk3_umk3_dedicated_japanese_parts` and both `inner_support_` twins.

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
sixteenth of an inch. The files are millimeters because every file here is, so the
conversion is an exact factor of 25.4 with no rounding at any point.

`mk3_umk3_dedicated_japanese_parts` keeps Twistedsymphony's button centers unchanged and only
swaps the hardware, to 30 mm Sanwa holes and the universal GL lever plate. The
spacing credit is his; the hardware choices are not from his drawing.

### @Nikogel360, and the Vewlix twelve button variant

Covers: `vewlix_12button_modern` and its `inner_support_` twin.

  https://x.com/Nikogel360

The layout was seen on Twitter, posted by @Nikogel360, as a photograph of a built
panel. Credit for surfacing it belongs there. Whether @Nikogel360 originated the
arrangement or was showing someone else's is not known, and no claim either way is
made here; if you know the designer, please open an issue so this can name them.

The eight original holes are Slagcoin's Vewlix 4+4 cluster at 24 mm, unchanged,
and are credited above. The four additions were constructed from that geometry to
match what the photograph shows, not measured from it, because a photograph taken
at an angle cannot support the accuracy a cut file needs. The construction is set
out in README.md so anyone can check it against a real panel.

### @GAMING_okayama, and the Vewlix ten button variant

Covers: `vewlix_okayama_10button` and its `inner_support_` twin.

  https://x.com/GAMING_okayama

The layout was seen on Twitter, posted by @GAMING_okayama, as a photograph of a
built panel. Credit for surfacing it belongs there. Whether @GAMING_okayama
originated the arrangement or was showing someone else's is not known, and no
claim either way is made here; if you know the designer, please open an issue so
this can name them.

The six inherited holes are Slagcoin's Vewlix 4+4 cluster at 24 mm, unchanged,
and are credited above. The fourth column is deleted and four holes are added,
two of them 30 mm. None of the four was measured from the photograph, because a
photograph taken at an angle cannot support the accuracy a cut file needs. Two
are equilateral triangle apexes on the existing column pairs; the other two are
placed by exact edge alignments supplied by the person who spotted the layout.
The construction is set out in README.md so anyone can check it against a real
panel.

### Crowquilll

Covers: the Neo Geo MVS Type 1 layouts: `neogeo_mvs_type1_japanese_parts`,
`neogeo_mvs_type1_american_parts` and both `inner_support_` twins. The other four
Neo Geo panels came from elsewhere and are credited below.

Source files: "MVS CPO 1P CURVED template.pdf" and "MVS CPO 2P CURVED template.pdf",
signed Crowquilll and dated 7/07. The artwork states that it was traced from a scan
of the control panel overlay of a dedicated 2-25 cabinet, and that the original CPO
is 23.75 x 8.75 inches.

The drilling template, and the work of tracing the original overlay, are
Crowquilll's. These templates were circulated freely in the arcade restoration
community. No canonical publication URL was confirmed, so none is claimed here; if
you know where they were originally posted, please open an issue and it will be
added.

The hole positions in both files come from that template, unchanged between them.
The hardware differs: `neogeo_mvs_type1_japanese_parts` carries 30 mm holes and the
GL lever pattern, `neogeo_mvs_type1_american_parts` carries 1.125 in holes with an
IL Eurojoystick 2 lever
cut. The template's own 1.1875 in buttons and 1.875 in American lever hole are
recorded here as what the original called for, but American Parts means 1.125 in
and IL's 35 mm bore consistently across this library.

The three lone buttons along the top of the CPO, labeled 1P Start, 2P Start and
Select Game on the template, are not included in either file.

### KidGamer77, and four more Neo Geo panels

Covers: `neogeo_mvs_type2_japanese_parts`, `neogeo_mvs_type2_american_parts`,
`neogeo_mini_japanese_parts`, `neogeo_mini_american_parts`,
`neogeo_mvs_u4_japanese_parts`, `neogeo_sc19_4_japanese_parts` and their
`inner_support_` twins.

  https://github.com/JasensCustoms/FightStickLayoutProject/issues/3

KidGamer77 opened the issue asking for the Neo Geo arrangements beyond the Type 1
panel this repository already had, named them, and then went and found flat,
square on reference art for each one. Credit for identifying these layouts and for
sourcing the art belongs there.

The art itself belongs to the people who made it, and none of it is redistributed
here. What each file names is which piece of art it was measured from:

  Type 2   a Phoenix Arcade screen printed reproduction CPO, photographed flat.
           Their listing states the panel is 9.25 x 23.625 inches, which is what
           gives this one an independent scale.
           https://www.phoenixarcade.com/products/neo-geo/neo-geo-cpo
  Mini     a flat photograph of a reproduction overlay of the aggressively curved
           panel, the one whose arc resembles the AES pad.
  MVS-U4   a flat photograph of an SNK MVS-U4 25 reproduction overlay.
  SC19-4   artwork for the SNK Neo SC19-4 candy cabinet panel, watermarked
           ArcadeArtShop.com, who appear to sell the clean version.

The original panel designs are SNK's. The reproduction artwork, and the tracing
and printing work behind each reproduction, belong to whoever made it. No claim is
made on any of it. Only the hole pattern, which is functional geometry, is here.

Unlike the Type 1 templates, none of these came as a vector drawing, so the hole
positions were measured. Two of the four images turned out to have real
perspective in them, which the measurement catches and corrects using nothing but
the panel itself: every button hole is the same size, every lever hole is the same
size, and each panel carries the same cluster twice as a translation rather than a
mirror. README.md sets out the method, the checks it passed and the accuracy it
reached, so anyone can judge it. Anyone cutting from these should verify against a
real panel first.

### lasagnasf, and the IST MakeStick

Covers: `ist_type1_japanese_parts`, `ist_type3_japanese_parts` and their
`inner_support_` twins.

  https://github.com/JasensCustoms/FightStickLayoutProject/issues/4

lasagnasf asked for the IST MakeStick layouts and supplied the product
photographs they were recreated from.

The layout is IST Mall's, from their MakeStick sticks.

  https://www.us.istmall.co.kr

RECREATED FROM PRODUCT PHOTOGRAPHY, not from a drawing. Two small photographs of
built sticks are all that was available, and they are not an official source.
Scale comes from the buttons themselves: the visible flange of a 30 mm Sanwa OBSF
is 33.2 mm and of a 24 mm one is 27.0 mm, and those two independent rulers agree
with each other to 0.21 percent on the better photograph. Both pictures turn out
to show the same arrangement, mapping onto each other at about a millimeter, and
the Type 1 file is the Type 3 file with three of the four extra buttons left out.
About a millimeter on the arrangement and about a percent on scale is the honest
accuracy; README.md says so in the catalog entry. If IST's own panel template
turns up, these will be redrawn from it.

### Industrias Lorenzo

Covers: the lever bore and mounting pattern on every American Parts file:
`mk3_umk3_dedicated_american_parts`, `american_s_american_parts`,
`neogeo_mvs_type1_american_parts`, `neogeo_mvs_type2_american_parts` and
`neogeo_mini_american_parts`.

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

Credit whoever the layout came from. Check the layout's catalog entry in
README.md, or the Sources list above, if you are not sure which that is.

## Adding a layout

New layouts are welcome, whether they come from a manufacturer drawing, a
measured cabinet, the community, or your own design. Please make sure the source
is yours to share or is published freely, name whoever should be credited, and
add a block to the Sources section above.
