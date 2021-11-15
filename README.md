# Tr_He_in_Catchment
This juypter notebook simulates the entry, transport and radioactive decay of tritium in groundwater, and the corresponding so-called Tritium-Helium groundwater age. 

The atomic-bomb tests in the 1960ties released tritium into the atmoshere leading to a peak of ~ 10000 Tritium Units in rainwater. 
Some rainwater infiltrates into the ground and feeds the aquifers as groundwater recharge. The residence time of a water parcel in an aquifer 
after infiltration can be calulated from the ratio of the remaining Tritium and enriched Helium in a groundwater sample. The calulated age is an approximation only, as the  hydrodynamic dispersion leads to bias, especially around the bomb-peak time.

The here presented 2D-vertical cross-section model of an aquifer simulates the process in a very simplified manner. The model assumes a homogeneous aquifer with a 
constant groundwater recharge over space and time. It compares the Tritium - Helium age and the so called piston-flow age (which assumes no dispersion) in the aquifer, as well as the resulting mixing age in a groundwater sample, taken from a monitoring well of specific position and screen length.

The model is purely based on analytical solutions that describe the travel times and flow paths in an unconfined aquifer 
(Chesnaux and Allen, 2008; Greskowiak et al., 2013), as well as advective-dispersive-reactive transport (Kinzelbach, 1987) 
considering a time varying boundary condition based on the superposition principle (Wexler, 1992).

Chesnaux, R. and Allen, D.M. (2008). Groundwater travel times for unconfined island aquifers bounded by freshwater or seawater. Hydrogeology Journal, 16: 437-445. https://doi.org/10.1007/s10040-007-0241-6.

Greskowiak, J., Röper, T., Post, V.E.A. (2013): Closed-Form Approximations for Two-Dimensional Groundwater Age Patterns in a Fresh Water Lens. Ground Water, 51(4), 629-634. https://doi.org/10.1111/j.1745-6584.2012.00996.x

Kinzelbach, W. (1987). Numerische Methoden zur Modellierung des Transports von Schadstoffen im Grundwasser, Habilitationsschrift, Universität Stuttgart.

Wexler (1992). Analytical solutions for one-, two-, and three-dimensional solute transport in ground-water systems with uniform flow Techniques of Water-Resources Investigations 03-B7,  https://doi.org/10.3133/twri03B7.
