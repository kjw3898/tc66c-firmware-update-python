# tc66c-firmware-update-python
firmware update manualy by python (serial)

# Usage
connect tc66c to PC with push K1 button 
if tc66c display bootloader release K1 button

any serial terminal monitor program and send "update\r\n" (some serial terminal program automaticaly add \r
n) I used arduino IDE serial monitor
after receive "uprdy", close the serial monitor program

then launch test.ipynb 


https://sigrok.org/wiki/RDTech_TC66C#Firmware_update
