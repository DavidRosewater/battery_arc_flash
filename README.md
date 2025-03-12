**Battery Hazard Calculator**

This is a spreadsheet to help electrical safety professionals analyze the hazards in battery systems. 

Three methods for arc flash analysis are currently implemented in this tool: Max Power, Arc Resistance, and Self-Extinguishing.

**Max Power**

From: Doan, D. R., “Arc Flash Calculations for Exposures to DC Systems,” IEEE Transactions on Industry Applications, vol. 46, no. 6, pp. 2299–2302, November/December 2010.

**Arc Resistance**

From: R. F. Ammerman, T. Gammon, P. K. Sen, and J. P. Nelson, “DC-Arc Models and Incident-Energy Calculations,” in IEEE Transactions on Industry Applications, vol. 46, no. 5, pp. 1810-1819, Sept.-Oct. 2010, doi: 10.1109/TIA.2010.2057497. 

With the arc model from: A. D. Stokes and W. T. Oppenlander, ``Electric arcs in open air,'' J. Phys. D: Appl. Phys. Vol 24, pp. 26-35, 6 April 1990

**Self-Extinguishing**

From: D. M. Rosewater, L. Gordon, W. Cantor, "Practical Battery Arc Flash Models" in 2025 IEEE IAS Electrical Safety Workshop, Jacksonville, FL, March 2024

**Recent Bug Fixes** 

•	Arc Boundary calculation in max power method used wrong cell for the initial estimation. Fixed 2025-3-10

•	IE calculation for the <5% chance self-extinguishing method always used inline configuration: Fixed 2025-3-7

•	Input Error Checking field in self-extinguishing method did not warn user if the input voltage was above the training data set used for calculating Beta. Fixed 2025-3-7
