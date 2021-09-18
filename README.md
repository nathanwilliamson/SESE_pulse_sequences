# SESE_pulse_sequence
flow compensated double spin echo pulse sequence for NMR MOUSE and Kea2 system (Magritek, Aachen, Germany).  This code was used to collect experimental data for a manuscript authored by Cai, Williamson, Ravin and Basser, to be submitted to Frontiers in Physics in 2021. Pulse sequence diagrams and an explanation can be found there. Also see Williamson & Ravin, et al. eLife 2019 for DEXSY pulse sequnce. Please cite accordinly. 

Pulse sequence was written and implemented in Prospa 3.22. SESEcompensated_pp ais the pulse programs. Macro files are also included but the pulse sequences is typically called through a backdoor DEXSY_diagonalSlice_SESEcompensated_SESEuncompensated_MNoiseWobb_interleaveBD.mac is included as an example but note that it calls additional pulse programs not provided and will therefore need alteration.

