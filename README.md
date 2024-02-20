--> https://resources.eumetrain.org/data/4/460/navmenu.php?tab=2&page=3.0.0

"When retrieving land surface temperature by remote sensing technologies, namely using sensors onboard aircraft or satellite platforms, we are dealing with radiometric temperature, a subtle concept that presupposes the understanding of the nature of radiation 
and how it interacts with matter.

Sunshine is one of the most familiar forms of radiation which, broadly speaking, may be viewed either as electromagnetic waves or as a collection of radiation energy quanta called photons that propagate through space or matter.

According to Prevost's definitions, all objects at a temperature greater than absolute zero radiate energy and the quantity of energy emitted depends on the properties of the object and not on the properties or presence of neighbouring objects.

When radiation energy strikes an object, generally a part of the energy, Er, is reflected, a part Ea is absorbed and a part Et is transmitted through the object.

Since energy is conserved we have:

E = Er + Ea +Et (eq.2)

Defining reflectivity ρ, absorptivity α and transmissivity τ respectively as the ratios of Er, Ea and Et to the total incident energy, E, we obtain:

1 = ρ + α + τ (eq.3)

Kirchhoff created a thought experiment involving a radiative equilibrium between two totally opaque (i.e. τ ≡ 0 and therefore ρ = 1 - α) infinite parallel plates of different materials facing each other. The two plates, call them A and B , 
will be emitting and absorbing radiation. Let αA(λ,T) and αB(λ,T) denote the absortivities of plates A and B at wavelength λ and let the two plates to reach thermodynamic equilibrium at a common thermodynamic temperature T. Let MA(λ,T) and MB(λ,T) 
denote the emitted energy per unit time at wavelength λ by plates A and B at equilibrium temperature T. Kirchhoff demonstrated that the ratios of emitted energy to absorptivity have to be the same for all materials, i.e.

MA(λ,T) / αA(λ,T) = MB(λ,T) / αB(λ,T) = Bλ(T) (eq.4)

where Bλ(T) is a universal function. This function gives the emitted energy per unit time per unit wavelength of a totally opaque body in units of absorptivity (assuming zero reflectivity) for all wavelengths. Kirchhoff envisioned a material with zero 
reflectivity and coined the term blackbody to label it.

Radiation emitted by a blackbody in thermal equilibrium per unit time at a specific wavelength λ (μm) and temperature T (K) is given by Planck's law (eq. 5): B(T) = (C1*λ^-5)/(e^(C2/λT)-1).

The spectral blackbody radiance is given in units of Wm-2sr-1μm-1, λ is the wavelength in μm, c1 and c2 are the Planck constants (c1=1.19104x108 Wm-2sr-1μm4; c2=1.43877 x104 μm K).

However, real surfaces do not behave as blackbodies. The fraction of radiance emitted from a real surface compared to a blackbody at the same temperature is referred as emissivity. For instance, a surface with a known spectral emissivity of 0.96 would emit 4% less 
radiation than a blackbody at the same temperature. Surface emissivity at a given wavelength depends on vegetation type and density, soil moisture and soil chemical components. Emissivity is a property of the material but not independent of the angle of incidence: 
it is a directional variable. On the other hand, according to Kirchhoff's Law, for a given object emitting and absorbing thermal radiation in thermodynamic equilibrium, the emissivity is equal to the absorptivity.

Emissivity is very difficult to measure, and it represents the major source of uncertainty in land surface temperature measurements. For a Lambertian surface (isotropic emissivity and reflectivity), where the spectral emissivity is assumed to be known and assuming 
there is no atmosphere between the ground and the measuring sensor, the surface temperature may be obtained by simply inverting Planck's function (assuming that the emissivity is known):

T = C2/(λ*ln(ε(C1/λ^5*B)+1)

For homogeneous isothermal surfaces, radiometric temperature is equivalent to thermodynamic temperature. However, land surfaces are not homogeneous, and so LST depends on within-pixel temperature and emissivity distribution, and is a directional quantity 
(Becker and Li, 1995).

As we have seen, the definition of radiometric temperature corresponds to the inversion of Planck's function, i.e, to a given radiance measured at a certain wavelength. Radiation is not monochromatic, however, but comprises a range of wavelengths. For the 
estimation of the surface energy budget in climate or numerical weather prediction models, we must consider the surface emitted radiation over the full infrared range, F, given by the integration of Planck's function for a gray body, i.e. a body where emissivity
is the same for all wavelengths and directions,

F↑ = εσT4skin  (eq.7)

This equation represents the so called Stefan-Boltzmann law, where σ= 5.67 x 10-8 W m2 K-4, and Tskin is called skin temperature.

The surface skin temperature can be derived from the energy balance equation:

(1 - α)S↓ + F↓ - (1 - ε)F↓ - F↑ - SH - LE - G = 0  (eq.8)

where α is the surface albedo, S↓ represents the downwelling shortwave radiation flux at the surface, F↓ is the longwave flux emitted by the atmosphere in downward direction towards the ground. ε is spectral averaged emissivity and (1 - ε)F↓ represents the portion 
of F↓ that is reflected backwards from the surface. LE and SH represent the surface latent and sensible heat fluxes, respectively, given by:

LE = coefE W (qskin-qair)  (eq.9)

SH = coefH W (Taero-Tair)  (eq.10)

coefE and coefH are bulk transfer coefficients for moisture and heat, W is wind speed, qskin is the saturated specific humidity at the aerodynamic temperature Taero (temperature at the height of roughness length for heat) and qair is the specific humidity at a 
reference level. Tair is the near surface air temperature (e.g. 2m shelter temperature). The radiometric (or skin) temperature is commonly used as a substitute for aerodynamic temperature in computing the sensible heat flux term SH in the energy balance.

So far we have clarified the physical meaning of radiometric temperature, the variable we are focusing on this product tutorial. We must also realize that due to its nature, radiometric temperature is not measured with thermometers (as thermodynamic temperature is), 
but with radiometers. Moreover, there is no direct method of measurement since what is being measured is emitted radiance and not radiometric temperature itself. Are the retrieving retrieval methods independent of the emitting surface?"

