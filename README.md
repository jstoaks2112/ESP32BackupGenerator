# ESP32BackupGenerator
Firmware for an esp32 to run and control a backup generator

This Firmware running on an ESP32 dwevice will automatically start, stop, run a weekly test, and sense when a power failure occurs to automatically start up and engadge transfer switch or switchs. Engine monitoring such as RPM, Battery Voltage, Engine Temperature(optional) are available. Last runtime and Last run test data available to controller for logging.

The generator is a simple basic Onan 4 stroke gasoline 4.3k 110v single phase output. it has a basic coil ignition setup running on 12 volts with starterr battery. There are Hundreds of these units out in the field. mostly in RV's and Motor Coachs. This firmware and HArdware setup should work on any standard non electronic generator with few adjustments. 
