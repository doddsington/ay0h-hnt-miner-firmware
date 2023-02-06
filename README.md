# Helium Miner software for Some Syncrobit and all SenseCAP M1 miners
Balena OpenFleet controlled software for Sensecap Miners

When forking this fleet, set variables for all services:

	VARIANT=COMP-SENSECAPM1
	FREQ=915 (or your country's frequency)
	REGION_OVERRIDE=US915 (or your region's plan)
Region definitions: https://github.com/NebraLtd/hm-pktfwd/blob/master/pktfwd/config/region_config_filenames.py

Variables/Variants now pre-set.
Working on versions using i2c-1 location. Submit PR if you'd like to add compatibility for a specific miner type
currently runs on Seeed studios hardware, with SM/WM130X lora module, or equivelents.
