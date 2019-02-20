# CSPA
Climate System Phase Analysis is a framework which allow capturing the state of multiple climate signals and improve seasonal forecast. CSPA is composed of four steps:  
- The detection of relevant climate teleconnections is performed by means of the [Nino Index Phase Analysis](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1002/2015WR017644), which categorizes years by climate phase and, for each phase, identifies preseason SST anomalies statistically significantly correlated with local conditions.
- The seasonal precipitation forecasts are generated by a nonlinear, multivariate Extreme Learning Machine model conditioned on the preseason SST for the relevant teleconnections detected in the previous step.
- The hydrologic forecasts are produced through a temporal downscaling procedure of the seasonal precipitation forecast to feed a hydrologic model.
- The forecast operational value is assessed by using the [Information Selection and Assessment framework](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1002/2015WR017044).

Details about the framework and its application to the Lake Como basin are provided in Giuliani et al. "Improving seasonal forecasts through the state of multiple climate signals to inform water reservoir operations" submitted to Water Resources Research. The code has been adapted from the original version of NIPA developed by Brian Zimmerman.


----
### Copyright:

Copyright 2019 NRM group (Politecnico di Milano) and Water Systems & Society Research Group (University of Wisconsin Madison).

Developers: Matteo Giuliani, Marta Zaniolo, Andrea Castelletti, Paul Block, and Brian Zimmerman.

CSPA is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

The code is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with CSPA.  If not, see <http://www.gnu.org/licenses/licenses.en.html>.

