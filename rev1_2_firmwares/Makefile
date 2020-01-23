print:
	echo "\n you need to specify firmware version, eg: make upload_12004 \n"
upload_12005: 
	openocd -s ./openocd -f stlink-v2.cfg -f stm32f0x.cfg -c "program firmware_12005 verify reset exit 0x08000000"
upload_12004:
	openocd -s ./openocd -f stlink-v2.cfg -f stm32f0x.cfg -c "program firmware_12004 verify reset exit 0x08000000"
upload_12003:
	openocd -s ./openocd -f stlink-v2.cfg -f stm32f0x.cfg -c "program firmware_12003 verify reset exit 0x08000000"
