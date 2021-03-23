Master Configuration File and Initial Condition
=================================================

	The configuration file in CRHM has .prj extension. The following variables are needed  to set up the water quality components of the new modules. We only specify here aspects related to water quality.
	
	1. Shared by multiple modules:
            • Shared atmos_mWQ <0 to 10>

    	2. WQ_pbsmSnobal: 
            • WQ_pbsmSnobal snow_conc <0 to 1000>
    	3. WQ_soil: 
            • WQ_Soil cov_type <0 to 2>
            • WQ_Soil CV_SWE <0 to 1>
            • WQ_Soil gw_conc_init <0 to 1>
            • WQ_Soil Sd_conc_init <0 to 10>
            • WQ_Soil sr_mix_rate <0 to 1000>
            • WQ_Soil parleach <0 to 1>

    	4. WQ_Netroute_M_D: 
           (none)
    	5. WQ_Soil_BGC: 
            • WQ_Soil_BGC ccmax1 <0 to 10>
            • WQ_Soil_BGC gcmax1 <0 to 10>
            • WQ_Soil_BGC surfsoil_massSolub_init <0 to 1000>
            • WQ_Soil_BGC surfsoil_masslabileNmass_init <0 to 1000>
            • WQ_Soil_BGC surfsoil_masslabilePmass_init <0 to 1000>
            • WQ_Soil_BGC surfsoil_massrefractoryNmass_init <0 to 1000>
            • WQ_Soil_BGC surfsoil_massrefractoryPmass_init <0 to 1000>
            • WQ_Soil_BGC conc_soil_rechr_init <0 to 1000>
            • WQ_Soil_BGC conc_soil_lower_init <0 to 1000>
            • WQ_Soil_BGC fertperiod <1 to 100>
            • WQ_Soil_BGC kho <0 to 100>
            • WQ_Soil_BGC klh <0 to 100>
            • WQ_Soil_BGC klo <0 to 100>
            • WQ_Soil_BGC kof <0 to 100>
            • WQ_Soil_BGC koflim <0 to 100>
            • WQ_Soil_BGC labileCmass_init <0 to 1E6>
            • WQ_Soil_BGC labileNmass_init <0 to 1E6>
            • WQ_Soil_BGC labilePmass_init <0 to 1E6>
            • WQ_Soil_BGC litterperiod <1 to 100>
            • WQ_Soil_BGC manureinogNfrac <0 to 1>
            • WQ_Soil_BGC fertandman_inogNfrac_NO3Nfrac <0 to 1>
            • WQ_Soil_BGC fertandman_inogNfrac_NO3Nfrac <0 to 1>
            • WQ_Soil_BGC manureinogPfrac <0 to 1>
            • WQ_Soil_BGC minc <0 to 100>
            • WQ_Soil_BGC pardegrhN <0 to 1>
            • WQ_Soil_BGC pardegrhP <0 to 1>
            • WQ_Soil_BGC pardenN <0 to 100>
            • WQ_Soil_BGC pardisfN <0 to 1>
            • WQ_Soil_BGC pardisfP <0 to 1>
            • WQ_Soil_BGC pardishN <0 to 1>
            • WQ_Soil_BGC pardishP <0 to 1>
            • WQ_Soil_BGC parminfN <0 to 1>
            • WQ_Soil_BGC parminfP <0 to 1>
            • WQ_Soil_BGC plant_uptk_NO3N <0 to 10>
            • WQ_Soil_BGC plant_uptk_NH4N <0 to 10>
            • WQ_Soil_BGC plant_uptk_SRP <0 to 10>
            • WQ_Soil_BGC refractoryCmass_init <0 to 1E6>
            • WQ_Soil_BGC refractoryNmass_init <0 to 1E6>
            • WQ_Soil_BGC refractoryPmass_init <0 to 1E6>
            • WQ_Soil_BGC resCamount <0 to 1>
            • WQ_Soil_BGC resfast <0 to 1>
            • WQ_Soil_BGC soimf <0 to 100>
            • WQ_Soil_BGC soimr <0 to 100>
            • WQ_Soil_BGC wp <1 to 66>
            • WQ_Soil_BGC erodibility <0 to 100>
            • WQ_Soil_BGC cohesion <0 to 100>



