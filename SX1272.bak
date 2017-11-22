EESchema Schematic File Version 2
LIBS:power
LIBS:device
LIBS:transistors
LIBS:conn
LIBS:linear
LIBS:regul
LIBS:74xx
LIBS:cmos4000
LIBS:adc-dac
LIBS:memory
LIBS:xilinx
LIBS:microcontrollers
LIBS:dsp
LIBS:microchip
LIBS:analog_switches
LIBS:motorola
LIBS:texas
LIBS:intel
LIBS:audio
LIBS:interface
LIBS:digital-audio
LIBS:philips
LIBS:display
LIBS:cypress
LIBS:siliconi
LIBS:opto
LIBS:atmel
LIBS:contrib
LIBS:valves
LIBS:stm32
LIBS:switches
LIBS:battery_management
LIBS:ESD_Protection
LIBS:u-blox
LIBS:tracking_device
LIBS:RF_Modules
LIBS:Electromechanical
LIBS:Test_Point
LIBS:electomech-misc
LIBS:_electromech
LIBS:Mounting_Hole
LIBS:tracking_device-cache
EELAYER 25 0
EELAYER END
$Descr A4 11693 8268
encoding utf-8
Sheet 3 3
Title "LoRa Transceiver"
Date ""
Rev "1"
Comp ""
Comment1 ""
Comment2 ""
Comment3 ""
Comment4 ""
$EndDescr
Text HLabel 5700 3050 2    60   UnSpc ~ 0
DIO0
Text HLabel 4400 3350 0    60   UnSpc ~ 0
SX1272_RESET
$Comp
L CONN_COAXIAL J11
U 1 1 59B49CF4
P 6200 3550
F 0 "J11" H 6210 3670 50  0000 C CNN
F 1 "SMA" V 6315 3550 50  0000 C CNN
F 2 "tracking_device:RP-SMA" H 6200 3550 50  0001 C CNN
F 3 "" H 6200 3550 50  0001 C CNN
	1    6200 3550
	1    0    0    -1  
$EndComp
Text HLabel 4400 3150 0    60   UnSpc ~ 0
SCK
Text HLabel 4400 2950 0    60   UnSpc ~ 0
MISO
Text HLabel 4400 3050 0    60   UnSpc ~ 0
MOSI
Text HLabel 4400 3250 0    60   UnSpc ~ 0
NSS
Text HLabel 5700 2950 2    60   UnSpc ~ 0
DIO1
Text HLabel 5700 2850 2    60   UnSpc ~ 0
DIO2
Text HLabel 5700 3350 2    60   UnSpc ~ 0
DIO3
Text HLabel 5700 3250 2    60   UnSpc ~ 0
DIO4
Text HLabel 4400 3450 0    60   UnSpc ~ 0
DIO5
Text HLabel 6750 3150 2    60   UnSpc ~ 0
VDD
$Comp
L RFM95W U7
U 1 1 59ED83FF
P 4700 3600
F 0 "U7" H 4750 4450 60  0000 C CNN
F 1 "RFM95W" H 5200 4450 60  0000 C CNN
F 2 "tracking_device:RFM95W" H 5200 4450 60  0001 C CNN
F 3 "" H 5200 4450 60  0001 C CNN
	1    4700 3600
	1    0    0    -1  
$EndComp
$Comp
L C C23
U 1 1 59EDA1E2
P 6550 3300
F 0 "C23" H 6575 3400 50  0000 L CNN
F 1 "10u" H 6575 3200 50  0000 L CNN
F 2 "Capacitors_SMD:C_0805_HandSoldering" H 6588 3150 50  0001 C CNN
F 3 "" H 6550 3300 50  0001 C CNN
	1    6550 3300
	1    0    0    -1  
$EndComp
Wire Wire Line
	6050 3550 5600 3550
Wire Wire Line
	5600 3450 6150 3450
Wire Wire Line
	5600 2850 5700 2850
Wire Wire Line
	5700 2950 5600 2950
Wire Wire Line
	5600 3050 5700 3050
Wire Wire Line
	5600 3150 6750 3150
Wire Wire Line
	5600 3250 5700 3250
Wire Wire Line
	5700 3350 5600 3350
Wire Wire Line
	4400 3450 4500 3450
Wire Wire Line
	4500 3350 4400 3350
Wire Wire Line
	4400 3250 4500 3250
Wire Wire Line
	4500 3150 4400 3150
Wire Wire Line
	4400 3050 4500 3050
Wire Wire Line
	4500 2950 4400 2950
Connection ~ 6550 3150
Wire Wire Line
	6550 3850 6550 3450
Text HLabel 5550 3850 0    60   UnSpc ~ 0
GND
Text Label 6100 3850 2    60   ~ 0
RADIO_GND
Wire Wire Line
	5550 3850 6550 3850
Text Label 6150 3450 2    60   ~ 0
RADIO_GND
Text Label 3950 3600 0    60   ~ 0
RADIO_GND
Text Label 4000 2850 0    60   ~ 0
RADIO_GND
Wire Wire Line
	4500 2850 4000 2850
Wire Wire Line
	4500 3550 4500 3600
Wire Wire Line
	4500 3600 3950 3600
Wire Wire Line
	6200 3750 6200 3850
Connection ~ 6200 3850
$EndSCHEMATC
