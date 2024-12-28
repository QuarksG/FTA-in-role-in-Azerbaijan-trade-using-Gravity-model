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

![image](https://github.com/user-attachments/assets/32655ab0-463c-494e-85ca-aec8311af298)

# Import

![image](https://github.com/user-attachments/assets/854d0237-d185-45b0-b00e-6bf1bdbb9960)

# General Variables

![image](https://github.com/user-attachments/assets/4aa61f6c-f7e3-44c1-bbcd-abba4979b507)






    ## Project Structure
- `src/`: Scripts and source code for the analysis.
- `data/`: Contains input and processed data files.
- `results/`: Outputs and results of the gravity model analysis.

