Fertilizer, Manure, Plant Residue
==================================

	.. role:: red
	    :class: red

	Nutrient inputs (Fertilizer, manure and plant residue) can added through obs files. These files need to be called in the project file (prj) under “Observations”. 

	Example (in prj file for calling nutriet input files):
	...
	Observations:

	build/Weather_STC.obs
	build/Fertilizer_application_N_up.obs
	build/Fertilizer_application_P_up.obs
	...

	The nutrient input files (obs) have the following structure:
	
	{comment}
	
	{variable}       {number of hrus}          {units of the load}
	  
	{year}	{mm}	{day}	{hour}	{min}	   {load in hru 1}	   {load in hru 2} {load in hru 3}....	 

	...

	The  {variable} allowed are:
	
    	1. Fertilizer
            • Fert_N_up
            • Fert_N_down
            • Fert_P_up
            • Fert_P_down
    	2. Manure
            • Man_N_up
            • Man_N_down
            • Man_P_up
            • Man_P_down
        3. Plant Residue
            • Res_N_up
            • Res_N_down
            • Res_P_up
            • Res_P_down

	Example:
	
	Steppler    Basin       (Diogo)
	
	Fert_N_up       4          (kg/km^2)        1           2           3           4 
	
	2005	9	8	1	0	   0.000	   0.000	   3.000	   0.000	   0.000	 
	
	2006	5	1	1	0	   0.000	   0.000	   0.000	   5.000	   0.000	 
