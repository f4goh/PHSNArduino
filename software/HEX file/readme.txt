using PHSNA with jnva software (experimental firmware)

the trik is to make beleive that jna use an ad8302 while it is a ad8307

first PHSNA need to be calibrate with PHSNA_F4GOH_UNO.hex  (like using antscope software)
calibration value is stored on internal EEPROM

then upload phsnarduino_jvna.hex file with xloader

launch jnva and select VnArduino
in calibration menu select right frequency as your dds

ad9850 :  34359738
ad9851 :  23860477

after make open calibration as jnva required

have fun

Anthony, F4GOH




