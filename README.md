The idea is monitor Jk-pb bms to home assistant used RS485 converter directly

#1st# you need to connect JK-Bms pb series used USB-RS485 port into RS485 your home assistant 
#2nd# makesure wiring correctly usually A-Orange, B-WhiteOrange, and Gnd-WhiteGreen
#3rd# Put the usb-rs485 into home assistant and find is connected into which port at HA

put yaml code into home assistant configuration.yaml and restart HA, the BMS will appear into modbus entities if success connecting

BMS Tested:
JK-PB2A15S16P

if want to connect 2 or more bms, change naming and slave
#sample#
DIP 1 - Slave: 1
DIP 2 - Slave: 2
DIP 3 - Slave: 3

