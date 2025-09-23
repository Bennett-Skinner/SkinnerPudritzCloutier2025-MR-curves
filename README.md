# SkinnerPudritzCloutier2025-MR-curves
Mass-Radius curves created using the planetary interior structure model presented in Skinner et al. (2025)

FORMATTING:

Each isocomposition curve is a separate file.
There are two slightly different file formats for planets with condensed surfaces and planets without condensed surfaces.
Planets without condensed surfaces have tables with two values of radii, one, "radius", is the 100 Pa pressure radius, the other,
"transit_radius", is calculated following the procedure in subsection 2.8
The other columns are as follows:
mass = Mass of planet in Earth masses
envelope_frac = Envelope fraction by mass of the planet
water_frac = Water fraction by mass of the planet
mantle_frac = Mantle fraction by mass of the planet
core_frac = Core fraction by mass of the planet
T_eq = Equilibrium temperature of the planet (assuming 0 bond albdeo) in Kelvin
period = Rotation period of the planet in Earth days; Note that the code accounting for this is disabled so this is a dummy value (Earth's)
age = Age of the planet in Gyr
radius = Radius of planet at 100 Pa in Earth radii
transit_radius = Radius of planet calculated using the procedure in subsection 2.8 in Earth radii
inner_pressure = Pressure of planet at the deepest depth simulated
inner_temperature = Temperature of planet at the deepest depth simulated

Direct all correspondance to skinnb1@mcmaster.ca.