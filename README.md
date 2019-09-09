# vrain

Here we provide datasets of a comprehensive set of uplink experiments between one srseNB and one srsUE node using a wireless channel in band 3.  

- srslte_v18.09.csv is the dataset used in DOI: 10.1145/3300061.3345431 with srsLTE v.18.09  
"CPU": CPU policy as defined in DOI: 10.1145/3300061.3345431  
"MCS": Fix MCS used for uplink transmission  
"SNR": Mean SNR mesuared  
"bsr": Mean Buffer State Report information as received by the eNB  
"buff_state1": Buffer state at the UE  
"buff_state2": Buffer state at the UE  
"dec_error": Mean decoding error rate measured  
"net_load": Mean load of Poisson-generated traffic (% of the saturation throughput with MCS 18)  
"throughput": Mean throughput measured (using TBS) (Mb/s)  
"txgain": TX gain at the UE  
"what": Type of host (computing) device  


- srslte_v19.03.csv is a newer and more comprehensive datased using srsLTE v.19.03  
"device": Type of host (computing) device  
"cpu": CPU policy as defined in DOI: 10.1145/3300061.3345431  
"mcs": Fix MCS used for uplink transmission  
"txpower": Tx power at the UE (dBm)  
"mean_traffic_load": Mean load of Poisson-generated traffic (Mb/s)  
"max_capacity": Max. throughput (using TBS, i.e., includding padding) measured for current load (given all txpower, mcs and cpu policies)
"max_gp_capacity": Max. goodput (data rate sent to application layer) measured for current load (given all txpower, mcs and cpu policies)
"mean_thr": Mean throughput measured (using TBS) (Mb/s)  
"mean_gput": Mean application-layer throughput (Mb/s)  
"mean_snr": Mean SNR mesuared  
"mean_q7": Mean QoS performance when Q=7000 bytes as defined in DOI: 10.1145/3300061.3345431  
"mean_q11": Mean QoS performance when Q=11000 bytes as defined in DOI: 10.1145/3300061.3345431  
"mean_q25": Mean QoS performance when Q=25000 bytes as defined in DOI: 10.1145/3300061.3345431  
"mean_bler": Mean bit error rate measured  
"mean_bsr": Mean Buffer States Reports
"mean_it": Mean number of turbodecoder iterations  
"mean_dectime": Mean subframe decoding time (usec)  
"mean_overflows": Mean number of overflows (O) from UHD driver  
"mean_underflows": Mean number of underflows (U) from UHD driver  
"mean_lates": Mean number of Lates (L) from UHD driver
"count": Number of experiments to compute mean and std. dev with equal configuration of <device, cpu, max_mcs, mean_txpower, mean_traffic_load>

