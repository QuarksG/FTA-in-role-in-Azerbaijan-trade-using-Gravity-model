## Dataframe headers in the CEPII Gravity Data

### **Link to the Data**
You can download the data from the following link:  
[CEPII Gravity Data](https://www.cepii.fr/DATA_DOWNLOAD/gravity/data/Gravity_csv_V202211.zip)


    data = {
        'year': [],
        'country_id_o': [],
        'country_id_d': [],
        'iso3_o': [],
        'iso3_d': [],
        'iso3num_o': [],
        'iso3num_d': [],
        'country_exists_o': [],
        'country_exists_d': [],
        'gmt_offset_2020_o': [],
        'gmt_offset_2020_d': [],
        'distw_harmonic': [],
        'distw_arithmetic': [],
        'distw_harmonic_jh': [],
        'distw_arithmetic_jh': [],
        'dist': [],
        'main_city_source_o': [],
        'main_city_source_d': [],
        'distcap': [],
        'contig': [],
        'diplo_disagreement': [],
        'scaled_sci_2021': [],
        'comlang_off': [],
        'comlang_ethno': [],
        'comcol': [],
        'col45': [],
        'legal_old_o': [],
        'legal_old_d': [],
        'legal_new_o': [],
        'legal_new_d': [],
        'comleg_pretrans': [],
        'comleg_posttrans': [],
        'transition_legalchange': [],
        'comrelig': [],
        'heg_o': [],
        'heg_d': [],
        'col_dep_ever': [],
        'col_dep': [],
        'col_dep_end_year': [],
        'col_dep_end_conflict': [],
        'empire': [],
        'sibling_ever': [],
        'sibling': [],
        'sever_year': [],
        'sib_conflict': [],
        'pop_o': [],
        'pop_d': [],
        'gdp_o': [],
        'gdp_d': [],
        'gdpcap_o': [],
        'gdpcap_d': [],
        'pop_source_o': [],
        'pop_source_d': [],
        'gdp_source_o': [],
        'gdp_source_d': [],
        'gdp_ppp_o': [],
        'gdp_ppp_d': [],
        'gdpcap_ppp_o': [],
        'gdpcap_ppp_d': [],
        'pop_pwt_o': [],
        'pop_pwt_d': [],
        'gdp_ppp_pwt_o': [],
        'gdp_ppp_pwt_d': [],
        'gatt_o': [],
        'gatt_d': [],
        'wto_o': [],
        'wto_d': [],
        'eu_o': [],
        'eu_d': [],
        'fta_wto': [],
        'fta_wto_raw': [],
        'rta_coverage': [],
        'rta_type': [],
        'entry_cost_o': [],
        'entry_cost_d': [],
        'entry_proc_o': [],
        'entry_proc_d': [],
        'entry_time_o': [],
        'entry_time_d': [],
        'entry_tp_o': [],
        'entry_tp_d': [],
        'tradeflow_comtrade_o': [],
        'tradeflow_comtrade_d': [],
        'tradeflow_baci': [],
        'manuf_tradeflow_baci': [],
        'tradeflow_imf_o': [],
        'tradeflow_imf_d': []
    }

# Export 
    Variable	Description	 Export 
    country_id_d	Destination country ID	Yes
    iso3_d	Destination ISO3 alphabetic	Yes
    iso3num_d	Destination ISO3 numeric	Yes
    country_exists_d	1 = Destination country exists	Yes
    gmt_offset_2020_d	Destination GMT offset (hours)	Yes
    main_city_source_d	Source of destination's most populated city	Yes
    legal_old_d	Destination legal system before transition	Yes
    legal_new_d	Destination legal system after transition	Yes
    heg_d	1 = Destination is current or former hegemon of origin	Yes
    pop_d	Destination Population, total in thousands	Yes
    gdp_d	Destination GDP (current thousands US$)	Yes
    gdpcap_d	Destination GDP per cap (current thousands US$)	Yes
    pop_source_d	Destination Population source	Yes
    gdp_source_d	Destination GDP source	Yes
    gdp_ppp_d	Destination GDP, PPP (current thousands international $)	Yes
    gdpcap_ppp_d	Destination GDP per cap, PPP (current thousands international $) \$	Yes
    gdp_ppp_pwt_d	Destination GDP, current PPP (2011 thousands US$) (PWT)	Yes
    gatt_d	Destination GATT membership	Yes
    wto_d	Destination WTO membership	Yes
    eu_d	1 = Destination is a EU member	Yes
    entry_cost_d	Destination Cost of business start-up procedures (% of GNI per capita)	Yes
    entry_proc_d	Destination Start-up procedures to register a business (number)	Yes
    entry_time_d	Destination Time required to start a business (days)	Yes
    entry_tp_d	Destination Days + procedures to start a business	Yes
    tradeflow_comtrade_d	Trade flows as reported by the destination, 1000 Current USD (source: UNSD)	Yes
    tradeflow_imf_d	Trade flows as reported by the destination, 1000 Current USD (source: IMF)	Yes![Uploading image.png…]()



    ## Project Structure
- `src/`: Scripts and source code for the analysis.
- `data/`: Contains input and processed data files.
- `results/`: Outputs and results of the gravity model analysis.

