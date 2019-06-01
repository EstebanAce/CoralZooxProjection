The python code `Model-RCP-ode-monthly.py` produces times series of coral biomass, coral energy investment trait and symbiont biomass. 
The simulation takes as input several parameters which are defined within code and timeseries of monthly temperature scenarios from an input file of the type `.dat`.
The data for timeseries monthly temperature and their corresponding months are also included in this repository (`Monthly-SST-scenario.zip`), all the files should be extracted and put in the same directory as `Model-RCP-ode-monthly`. 
The occurence of bleaching is parametrised according to several literature data listed in the file `S-density-bleaching.pdf` 
The results of the simulation are saved in a predefined folder corresponding to each scenario, e.g. `Results/RCP26/`. 
These folders must be created prior running the code. 
