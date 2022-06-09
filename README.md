# Data_Liquid_Water_Conditions
This data is part of the publication 'Potential long-term habitable conditions on 
planets with primordial H-He atmospheres', M. Mol Lous, R. Helled, C. Mordasini (2022).

## Paper abstract:
  Cold super-Earths that retain their primordial, H–He-dominated atmosphere
  could have surfaces that are warm enough to host liquid water. This would be
  due to the collision-induced absorption of infrared light by hydrogen, which
  increases with pressure. However, the long-term potential for habitability of
  such planets has not been explored yet. Here we investigate the duration of
  this potential exotic habitability by simulating planets of different core
  masses, envelope masses and semi-major axes. We find that terrestrial and
  super-Earth planets with masses of ~1–10 M⊕ can maintain temperate surface
  conditions up to 5–8 Gyr at radial distances larger than ~2 au. The required
  envelope masses are ~10−4 M⊕ (which is 2 orders of magnitude more massive than
  Earth’s) but can be an order of magnitude smaller (when close-in) or larger
  (when far out). This result suggests that the concept of planetary
  habitability should be revisited and made more inclusive with respect to the
  classical definition.

## Description:
  The tables contain the results of simulations of the evolution of planets
  which have a rocky core and a solar composition (primordial) atmoshere. These
  results are presented in Mol Lous et al. 2022, where the aim of the work was
  to investigate the occurence of conditions that allow liquid water on the
  core-envelope interface. The simulations assume a sun-like host-star.
  
  **NoEvap**: These contain data for evolution models that do not take into consideration 
  atmospheric escape. These results are presented in Figure 1. of Mol Lous et al. 2022. 
  The 'unbound' cases are those where the distance is set to 1e6 AU so that solar 
  irradiation becomes negligible. Every file contains data on the whole population of 
  planets at a given time, which is indicated in the title in years. For example 1e8.dat 
  is a file that contains data on all the modeled planets at 100 Myr.

  **Evap**: These contain data for evolution models that include an atmospheric escape model. 
  These results are presented in Figure 3. of Mol Lous et al. 2022. The 'unbound' cases 
  are those where the distance is set to 1e6 AU so that solar irradiation becomes 
  negligible.

  **Menv_Loss/JeansEsc/*** and Menv_Loss/HydroEsc/* : These are several cases of planets with 
  different envelope masses, core masses and distances to their host star. The two folders 
  JeansEsc and HydroEsc contain data for a Jeans escape model and a hydrodynamical escape 
  model respectively. The data is presented in Mol Lous et al. 2022, Figure 2.

  **Cold_Cases:** These contain data of only the planets that receive negligible radiation 
  (distance is set to 1e6 AU). Every file contains the evolution of one planet. The data 
  is presented in Mol Lous et al. 2022, Figure 4.
  
  All data sets contain the same variables in the same order, which are:
  1. Time (year)
  2. Core mass (Earth mass)
  3. Core Luminosity (Ljup=3.35e25 cgs)
  4. Total Luminosity (Ljup=3.35e25 cgs)
  5. Pressure at envelope core boundary (bar)
  6. Temperature at envelope core boundary (Kelvin)
  7. Radiogenic core luminosity (Ljup=3.35e25 cgs)
  8. Mdotevap (Earth mass/yr) envelope evaporation rate
  9. Semi-major axis (AU)
  10. Menve(Mearth)
  11. Current envelope mass / initial envelope mass
  12. Water state on core-enve boundary 0=solid, 1=liquid, 2 = vapour, 3=supercritical, 4 = other (high press. ices, temp > 800 K)
  13. Duration of liquid water presence [year]
  14. Texo (Kelvin)
  15. Radius where optical depth = 0.01 (Rearth).
