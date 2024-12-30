
Jupyter ToolKit for : 
Laser Power density(PowerDensity or IMax or Imax, GW/cm2) calculation from Beam parameters Energy (E - J), pulse duration (Tpul or Tau - ns) and spot diameter (d - mm), possible neutral density (D0)
Related Plasma pressure profile (GPa)

See reference for limits and validation 
# Bibtex - Citation - reference. 
@article{Scius-Bertrand_2021, doi = {10.1088/1361-6463/abc040}, url = {https://dx.doi.org/10.1088/1361-6463/abc040}, year = {2020}, month = {nov}, publisher = {IOP Publishing}, volume = {54}, number = {5}, pages = {055204}, author = {Marine Scius-Bertrand and Laurent Videau and Alexandre Rondepierre and Emilien Lescoute and Yann Rouchausse and Jan Kaufman and Danijela Rostohar and Jan Brajer and Laurent Berthe}, title = {Laser induced plasma characterization in direct and water confined regimes: new advances in experimental studies and numerical modelling}, journal = {Journal of Physics D: Applied Physics}, abstract = {Optimization of the laser shock peening (LSP) and LASer Adhesion Test (LASAT) processes requires control of the laser-induced target’s loading. Improvements to optical and laser technologies allow plasma characterization to be performed with greater precision than 20 years ago. Consequently, the processes involved during laser–matter interactions can be better understood. For the purposes of this paper, a self-consistent model of plasma pressure versus time is required. The current approach is called the inverse method, since it is adjusted until the simulated free surface velocity (FSV) corresponds to the experimental velocity. Thus, it is not possible to predict the behavior of the target under shock without having done the experiments. For the first time, experimental data collected in different labs with the most up-to-date laser parameters are used to validate a self-consistent model for temporal pressure-profile calculation. In addition, the parameters characterizing the plasma (temperature, thickness and duration) are obtained from the ESTHER numerical code, together with the amount of ablated matter. Finally, analytic fits are presented that can reproduce any pressure–temporal profiles in the following domains of validity: intensities, I, ranging from 10 to 500 GW cm−2 and pulse durations, T pul, between 5 and 40 ns for the direct-illumination regime at 1053 nm, I ranging from 1 to 6 GW cm−2 and T pul between 10 to 40 ns in the water-confined regime at 1053 nm, and I from 1 to 10 GW cm−2 and T pul between 7 and 20 ns in the water-confined regime at 532 nm. These temporal pressure profiles can then be used to predict the aluminum target’s behavior under laser shock using mechanical simulation software.} }


def LaserPowerDensity(Tau,E,d,D0) gives Power Density calculation
def MaxPressureAtMaxPowerDensity(PowerDensity) gives maximum pressure in GPA
def PowerDensityPressure(IMax,Np) gives maximum pressure curve in GPA up to IMax with Np increments
def PressureFunction(Time,Imax,Tpul,T0,Ti) gives Pressure at time (Time - ns) - T0 is rise time 
def PressureProfile(I0,Tpul,T0,Np,FileName) give Pressure (Time) profile saved in FileName with Np increment time. 

@author: Marine Scius_Bertrand, Laurent Berthe 
