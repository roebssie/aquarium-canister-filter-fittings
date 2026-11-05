Canister filter inlet and outlet fittings — Blender 5.2.3

Files
- canister_filter_inlet_outlet.blend — editable Blender scene
- aquarium_inlet_12mm.stl — over-rim inlet with integrated intake guard
- aquarium_outlet_12mm.stl — over-rim return with open-ended horizontal T tunnel
- canister_fittings_preview.png — rendered design view

Layout
Both fittings pass over the aquarium rim with a downward-facing hose barb outside and a vertical leg inside. Two snap pegs on each inside leg are intended to push into existing suction-cup clips. The inlet guard is fused into the inlet as one mesh, with a continuous annular support ring joining the stem to the guard's top hoop while leaving the stem bore open.

The outlet is a T: its horizontal crossbar is a thin-wall hollow tube, and the vertical return tube feeds it from the side at the center. The crossbar is 34 mm OD and 27 mm ID, 32 mm long, with each open mouth 16 mm from the swivel center. It has no end caps or side ports; the swivel passage and two tube mouths are the only openings. A single print-in-place swivel is modeled at the central joint; no other bends rotate.

Fit assumptions
- Hose ID is assumed to be 12 mm from your estimate. The barbed tails are sized around common 12/16 mm canister hose; confirm the hose inside and outside diameters before printing.
- Glass was interpreted as 4 mm. The inlet U has about 30 mm between leg centerlines and the outlet U about 34 mm; both clear the rim. Suction cups retain the inside legs, and the fittings do not clamp the glass. The inlet hose barb ends about 32 mm below the rim reference; the outlet barb ends about 42 mm below it so its bend reads as a U. Check for lids or cross-braces that might obstruct the bends.
- The suction-clip opening is not measured. Peg heads are 5.2 mm, and the longer shanks are 3 mm diameter by 6 mm long. Their tips remain about 2 mm from the assumed glass plane. Check that the peg profile fits your cups before printing the full pair.
- The inlet guard bottom is about 174 mm below the rim reference; confirm it suits your tank depth and intake position.
- The swivel uses nominal 0.4 mm radial clearance. Printer calibration, material shrinkage, and layer orientation can make it fuse or wobble; gently free the joint after printing and confirm it turns without cracking.

Flow rationale
Canister-filter layouts commonly route hoses over the aquarium edge and retain rigid inlet/outlet pipes inside the tank with suction cups. EHEIM’s Classic 2213 manual shows this arrangement and lists different hose sizes, including 12/16 mm and 16/22 mm, so this fitting is not universal across all filters.

The 27 mm open-ended horizontal passage carries water from the center out of both ends. Its combined end area is about 1,145 mm², compared with about 113 mm² for the 12 mm hose bore, so return flow divides between two broad mouths. This may reduce jet speed, but actual current depends on the filter’s flow rate and aquarium layout. ADA's Lily Pipe uses a specially shaped outlet to moderate flow; this straight T tunnel is a different, untested design.

Research references
- EHEIM Classic 150 manual (strainer, suction-cup clips, outlet elbow and pipe): https://eheim.com/media/pdf/99/72/55/EHEIM_classic_150_manual.pdf
- EHEIM Classic 2213 manual: https://eheim.com/media/a3/4a/c9/1770122536/2213_classic.pdf
- ADA Lily Pipe manual: https://www.adana.co.jp/jp/contents/support/filtration/manuals/LILYPIPE_S_WEB.pdf
- ADA Lily Pipe Spin product page (gentle return flow): https://www.adana.co.jp/en/contents/products/na_filter/detail04.html/1000
- Betta care/current guidance: https://vetmed.illinois.edu/pet-health-columns/betta-fish/ and https://www.petmd.com/fish/betta-fish-care-sheet
- Prusa watertight-printing notes: https://blog.prusa3d.com/watertight-3d-printing-part-2_53638/

Print and use notes
- Prototype only: no pressure, flow, fit, or long-term immersion tests have been performed.
- The print-in-place swivel has running clearance and is not a sealed bearing. Water may leak or bypass around the joint; it is not guaranteed watertight or pressure-rated. Test it under supervision in a tub before aquarium use and do not leave it unattended unless it proves reliable in sustained testing.
- FDM layer lines can leak under canister-filter flow/pressure. Use aquarium-appropriate filament from a known source, sufficient wall count, inspect passages for blockage, and use a suitable hose clamp if needed.
