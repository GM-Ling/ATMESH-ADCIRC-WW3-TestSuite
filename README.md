# ATMESH-ADCIRC-WW3-TestSuite
This repository is for storing test case for CoastalApp.

Test 1: Shinncecock_test_ATM_ADC_WW3_CoastalApp
****Notes:
*The setup of ww3 is ready for the NOAA-EMC/WW3 version.
*For running the scalability version of ww3, need to change the followings:
 -'ww3_grid.inp' time steps to: 150. 150. 150. 150.
 -'ww3_multi.inp' reads more options('no' 'no'):  
  'inlet'  'no' 'no' 'CPL:native' 'no' 'no' 'no' 'no' 'no' 'no'   1  1  0.00 1.00  F 
