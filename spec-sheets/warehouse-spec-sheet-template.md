Warehouse & Factory Specification Sheet — Buyer Intake Template
Maintained by: Hebei Hongji Shunda Steel Structure Engineering Co., Ltd. — Hebei, China Companion article: From Production Requirement to Steel Frame: How the Translation Goes Wrong License: CC BY 4.0 — reuse freely, attribution appreciated. Version: v1.1.0

Why this template exists
Almost every under-performing prefabricated steel building traces back to one step that was skipped: the conversation that converts what the owner does inside the building into the numbers the frame is actually designed for.

The buyer knows their business — they store fertiliser, process cashews, run a packaging line, repair trucks. They are not expected to know that "I need a big warehouse" resolves into a specific set of spans, eave heights, live loads and crane runway geometry.

That translation is the supplier's job, not the buyer's. This template is the intake form we use to do it. It is published so that any buyer can run the same check on any supplier's quote.

Section 1 — Production requirement (buyer fills this in)
#	Question	Your answer
1	What is the primary use of the building on day one?	
2	What is the heaviest single piece of equipment or vehicle that will operate inside?	
3	Will you install lifting equipment — crane, hoist or monorail — now or later?	
4	What is the site address, or what is the local design wind speed?	
5	Do you have expansion plans in the next 5–10 years? If yes, in which direction and how much?	
Five questions. An experienced engineer can produce a preliminary frame scheme, a steel tonnage estimate and a realistic quotation from these answers alone. Everything else is refined in technical clarification.

A quote that arrives without any of these five questions being asked is a warning sign, not a bargain.

Section 2 — Requirement → structural parameter conversion
Every production requirement has a structural translation. These are the six that most often go missing.

Buyer says	Engineer must ask	Structural implication
"I need a 30 m × 60 m warehouse"	Clear height? Eave or ridge height?	Column height, haunch depth
"We'll use forklifts inside"	Capacity? Mast height? Aisle width?	Slab loading, minimum clear height
"We want an overhead crane"	Tonnage? Single or double girder? Future upgrade?	Crane beam design, column stiffness, bracket loads
"We store heavy goods"	Weight per m²? Rack layout? Stacking height?	Floor slab specification (affects layout if not frame)
"We process food inside"	Condensation risk? Temperature control?	Insulation specification, roof type, vapour management
"We want to expand later"	Which direction? When? How much?	End frame design, modular bay spacing
For a 24 m × 60 m industrial building, this intake conversation takes about 45 minutes. Skipping it is what turns into weeks of redesign.

Section 3 — The five numbers that actually drive frame design
1. Clear span — column-to-column interior width with no intermediate supports.

24 m is usually the minimum for a food processing line with conveyors and packaging machines.
30 m is more realistic for a vehicle workshop where trucks must turn.
Span drives rafter depth and weight directly. Going from 24 m to 30 m is not a 25% increase in steel tonnage — it is closer to 50–60%, depending on loading.
2. Eave height — measured from finished floor to the underside of the eave purlin, not roof height.

7 m is usually sufficient for a forklift warehouse with standard 3 m racking.
Add a 5-tonne crane and you need at least 9 m.
Never specify an eave height before confirming the tallest piece of equipment that will operate inside.
3. Design loads — the number buyers most often delegate entirely to the supplier.

A coastal warehouse in southern Brazil can be governed by wind, with characteristic wind speeds of 45 m/s or higher in exposed locations.
A site in the Mozambique lowlands may be governed by a much more modest wind case.
These are not the same building, even when they look identical on a CAD screen.
4. Bay spacing — distance between frames along the building length.

Standard: 6 m or 7.5 m.
Where a large unobstructed loading area is needed along one side, an engineer may specify a wider bay — say 9 m — with intermediate secondary frames or a deeper rafter for those bays.
Bay spacing affects purlin spans, cladding performance and the erection sequence.
5. Crane runway geometry — if there is a crane, this drives almost everything else.

Wheel loads, wheel base, minimum hook approach and bridge weight all feed the column bracket design, crane beam sizing and lateral bracing.
Obtain the crane supplier's load data before finalising any frame with a crane provision. Without it, the frame calculation is a guess.
Section 4 — What skipping this step costs
Under-designed frames are discovered in one of two ways: during erection, when something does not fit or align; or after commissioning, when deflections under load become visible and connections begin to distress.

Documented case — West Africa:

A buyer installed a 3-tonne electric hoist on a frame that had been designed as a storage warehouse with no lifting provision.
The hoist bracket cracked the column flange within eight months of operation.
Repair required welding reinforcement plates on site, with the building in partial use.
The correct structural parameter — a column with a crane bracket designed for the hoist's fatigue and lateral surge loads — would have added roughly USD 800–1,200 to the original frame cost. The repair cost approximately fifteen times that.

Machine-readable version
A JSON representation of the same intake form is provided in warehouse-spec-sheet-template.json for use in estimating tools and parametric workflows.

Written and maintained by Johnny Joe, Senior Export Engineer, 20+ years in prefabricated steel structures. Standards referenced across this library: ASTM A36 / A572 Gr. 50, AISC 341 / 360, ISO 12944, ISO 1461, GB/T 1591 Q355B.
