title: "Thermodynamic Context in Geophysical Interpretation at the Rainbow Hydrothermal Field, MAR"
excerpt:
collection: portfolio

## Thermodynamic Context in Geophysical Interpretation at the Rainbow Hydrothermal Field, MAR

Around a month ago, I read a journal paper in Nature ([*Hydrothermal flow and serpentinization in oceanic core complexes controlled by mafic intrusions*](https://www.nature.com/articles/s41561-024-01444-y?fromPaywallRec=false)*)* on a seismic investigation of fluid flow and alteration at the ultramafic hosted Rainbow Hydrothermal Field on the Mid-Atlantic Ridge. The study developed seismic velocity models of the oceanic core complex and utilized effective medium theory to calculate estimates for degree of serpentinization and porosity of the study area. The authors identified low Vp channels that serve as high permeability upflow zones towards the seafloor hydrothermal field, as well as large mafic intrusive bodies that, through rheological contrast with the surrounding serpentinized peridotite that promotes fracture nucleation, control the path of upflowing hydrothermal fluid. The authors also concluded that based on the low degree of serpentinization beneath the largest mafic intrusion, the intrusion served as a barrier to fluid downflow, thereby limiting serpentinization.

<p align="center">
  <img src =https://github.com/user-attachments/assets/2bfdf7d6-9a41-4237-a37d-ecc5c1e2a118>
</p>

<p align="center">
 <i>Fig. 2e from Jian et al. (2024) showing best estimates of degree of serpentinization calculated from seismic velocity and effective medium theory at the Rainbow Hydrothermal Field.</i>
</p>

Overall the paper was very well written and explained, however I took some issue to the last point regarding the interpretation of low serpentinization as a sign of limited fluid downflow. Serpentinization is a relatively low temperature metamorphic process, and thus the equilibrium between serpentine and its precursor minerals of olivine and orthopyroxene begins to result in incomplete conversion of the original minerals past 315℃ as olivine becomes increasingly stable. At these higher temperatures, a sample of partially serpentinized peridotite can exist at equilibrium with excess available water. The water emanating from the Rainbow hydrothermal field is in excess of 360℃, indicating that the oceanic core complex contains regions of high enough temperature that the stability of olivine in the equilibrium of serpentinization is relevant \[1\]. Therefore, it is important to take the thermal environment into account when interpreting fluid availability, comparing the level of serpentinization to *maximum potential alteration* *given the thermal conditions*, rather than defaulting to 100% serpentinization as the maximum.  
As a preface, the following process is more a proof of concept for a method rather than a numerically accurate and definitive answer for interpretation of this seismic data, as we will have to make many assumptions through the process. Firstly, the solutions for degree of serpentinization from seismic velocity are non-unique, as noted in the paper, due to contributions from both chemical alteration and porosity. However, the most uncertain assumption is the geotherm. The actual geotherm is likely complex and both laterally and vertically heterogeneous, due to hydrothermal convection and intrusions of magmatic bodies. However, since we don’t have any additional information on temperature conditions, we must assume a linear geotherm. The seafloor line delineated by bathymetry can be assumed to be at thermal equilibrium with deep seawater (\~0℃). The temperature at depth is more challenging to ascertain. The hydrothermal fluid exits the vents at \~360℃, and geochemical studies indicate the fluid loses \~24-30% of its heat content while traveling to the seafloor, estimating the source temperature to be 430-470℃ \[[1](https://www.sciencedirect.com/science/article/abs/pii/S0012821X24004953)\]. However, previous seismic studies have imaged numerous magmatic sills that have intruded into the oceanic core complex and are thought to be the primary drivers of hydrothermal circulation, but likely do not directly influence the overall geotherm of the ultramafic body \[[2](https://pubs.geoscienceworld.org/gsa/geology/article-abstract/45/5/451/207914/Seismic-imaging-of-magma-sills-beneath-an)\]. Thus, I decided to delineate the bottom geotherm temperature based on the beginning of the “high Vp” zone, somewhat arbitrarily at 7.0 km/s, using interpolation and smoothing to create the line. A high velocity zone would correspond to the temperature where olivine is fully stable (400℃), thus it is unable to be serpentinized and retains its higher density, and therefore higher seismic velocity. Between these two horizontal contours, we establish a linear geotherm between 0 and 400℃.

<p align="center">
 <img src =https://github.com/user-attachments/assets/7ac8e370-acdf-45e5-8535-39a61efc2b49>
</p>
<p align="center">
<i>Image of Vp of the Rainbow massif, data from Jian et al. (2024)</i>
</p>

<p align="center">
<img src=https://github.com/user-attachments/assets/e6e5a559-83f0-48a5-af17-a97cbd8f48e0>
</p>
<p align="center">
<i>Calculated linear temperature gradient, Dotted line delineates the high Vp zone. Original data from Jian et al. (2024) </i>
</p>

After establishing the temperature distribution, we can apply thermodynamic modeling to calculate the equilibrium degree of serpentinization at every temperature. McCollom & Bach (2009) calculated the predicted equilibrium mineralogy of 1000g of harzburgite at a water:rock ratio of 1\. I recreated a simplified piecewise equation to represent the relationship between temperature and equilibrium degree of serpentinization (equal to 1- (mass original mineral remaining)/(mass original mineral)), shown below.

<p align="center">
<img src = https://github.com/user-attachments/assets/bebb5313-c0e9-478a-9f28-0fc7a841ea41>
</p>
<p align="center">
<i>Left: Equilibrium calculation of 1000g harzburgite at water:rock ratio of 1 at different temperatures, from McCollom & Bach (2009). Right: Simplified piecewise equation used to calculated equilibrium degree of serpentinization </i>
</p>

Applying the piecewise equation to the calculated temperature distribution gives the estimated maximum alteration at each point, which can be compared to the original calculation of degree of serpentinization from seismic velocity to get the thermodynamic degree of alteration((seismic derived degree serpentinization)/(calculated maximum degree of alteration)).

<p align="center">
<img src =https://github.com/user-attachments/assets/84988336-d735-466f-9480-249cb9ab8f7a>
</p>
<p align="center">
<i>Calculated degree of alteration in agreement with thermodynamic equilibrium, based on the assumed thermal gradient. The two large white bodies in the centre are mafic intrusions identified by Vp/Vs from local earthquake tomography. The blue dotted line delineates the high Vp zone.</i>
</p>

Based on our assumed geotherm, the region directly below the large central mafic intrusion is closer to 50-80% altered given the thermodynamic constraints, indicating that supply of water to the region is not a significant limitation. Thus, it is unlikely that the mafic intrusion blocks fluid to the region, as if this were the case, we would expect to see little to no alteration at all. An alternative interpretation could be that the intrusive body acts as a lid to *fluid upflow*, preventing hydrothermal convection out of the region and thus conserving the high temperatures in the area, limiting serpentinization thermodynamically. However, the limitations of our assumed linear geotherm can be seen in the region of the diagram to the upper left of the intrusive body. Our calculations show that this region is less altered than its surroundings. However, the study identified this area as the upward flow path toward the hydrothermal field. Thus, we would expect this area to be hotter than described by the linear geotherm, due to contact with hydrothermal fluid, and therefore it is likely fully altered relative to its true temperature, due to its constant contact with hydrothermal fluid. Applying this same line of reasoning to the region below the mafic body, I would actually guess that the temperature may even be higher than predicted. The mafic body would have been very hot upon intrusion. If it truly served to limit fluid intrusion into the region, then the region would likely remain at a high temperature due to no fluid to convect heat away, and in that case we would expect even less alteration than shown in the seismic imaging. Thus, it is more likely that there is fluid intrusion in some fashion, but there is limited hydrothermal convection due to the mafic body, keeping the temperature relatively high, but altering the peridotite close to its thermodynamic potential in the given conditions. Due to the uncertainty from the non-uniqueness of solutions for degree of serpentinization and our assumptions with the geotherm, it is difficult to come to definite conclusions, however this process hopefully illustrates the importance of integrating geochemistry and thermodynamics into geophysical interpretations in ultramafic environments and possible methodology to do so.
