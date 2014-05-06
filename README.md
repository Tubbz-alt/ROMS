This is my fork of the official Rutgers ROMS trunk code.

Changes
-------
    * ROMS now stores the latest git commit IDs for both my ROMS fork and the current project I'm compiling
    * Ability to control rotation of harmonic and biharmonic viscosity/diffusivities individually
    * netCDF saving of spatially varying bottom friction parameters - rdrg, rdrg2
    * netCDF saving of domain nudging coefficients
    * More reasonable (to me) float deployment based on floats.in file.
    * netCDF saving of time invariant viscosity and diffusivity coefficients - both harmonic and biharmonic

Incomplete changes
------------------
    * More reasonable VOLCONS behaviour - ignore periodic boundaries, control which boundaries to calculate flux and which ones to adjust the flux.
    * Bihamornic smagorinsky mixing prioritized over harmonic? Not sure.
