EESchema Schematic File Version 4
LIBS:RJ10Adapter-cache
EELAYER 29 0
EELAYER END
$Descr A4 11693 8268
encoding utf-8
Sheet 1 1
Title "RJ FTDI Adapter"
Date "2019-05-11"
Rev "1.2"
Comp "haus-automatisierung.com"
Comment1 "Matthias Kleine"
Comment2 ""
Comment3 ""
Comment4 ""
$EndDescr
$Comp
L Connector:RJ10 J1
U 1 1 5CA8B8F5
P 3650 3800
F 0 "J1" H 3400 4150 50  0000 C CNN
F 1 "RJ10" H 3850 4150 50  0000 C CNN
F 2 "halibs:MEBP_44S" V 3650 3850 50  0001 C CNN
F 3 "~" V 3650 3850 50  0001 C CNN
	1    3650 3800
	1    0    0    -1  
$EndComp
$Comp
L Connector:Conn_01x06_Male J2
U 1 1 5CA8BB58
P 5650 3700
F 0 "J2" H 5850 4100 50  0000 R CNN
F 1 "Conn_01x06_Male" H 5850 4000 50  0000 R CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_1x06_P2.54mm_Vertical" H 5650 3700 50  0001 C CNN
F 3 "~" H 5650 3700 50  0001 C CNN
	1    5650 3700
	-1   0    0    1   
$EndComp
NoConn ~ 5450 3800
NoConn ~ 5450 3400
$Comp
L power:GND #PWR0101
U 1 1 5CA8C060
P 4250 3250
F 0 "#PWR0101" H 4250 3000 50  0001 C CNN
F 1 "GND" H 4255 3077 50  0000 C CNN
F 2 "" H 4250 3250 50  0001 C CNN
F 3 "" H 4250 3250 50  0001 C CNN
	1    4250 3250
	0    -1   -1   0   
$EndComp
$Comp
L power:PWR_FLAG #FLG0101
U 1 1 5CA8C179
P 4350 4000
F 0 "#FLG0101" H 4350 4075 50  0001 C CNN
F 1 "PWR_FLAG" H 4350 4174 50  0000 C CNN
F 2 "" H 4350 4000 50  0001 C CNN
F 3 "~" H 4350 4000 50  0001 C CNN
	1    4350 4000
	-1   0    0    1   
$EndComp
Text Label 4150 3600 0    50   ~ 0
V-
Text Label 4150 3900 0    50   ~ 0
Vin
Text Notes 3300 3900 2    50   ~ 0
GND: yellow (4)\nRX: green (3)\nTX: brown (2)\nVCC: white (1)
Wire Wire Line
	4650 3600 4650 3900
Wire Wire Line
	4650 3900 5450 3900
Wire Wire Line
	4050 3900 4350 3900
Wire Wire Line
	4600 3900 4600 3700
Wire Wire Line
	4600 3700 5100 3700
Wire Wire Line
	4350 4000 4350 3900
Connection ~ 4350 3900
Wire Wire Line
	4350 3900 4600 3900
Wire Wire Line
	4050 3600 4100 3600
Wire Wire Line
	4050 3800 4550 3800
Wire Wire Line
	4550 3800 4550 3500
Wire Wire Line
	4550 3500 5300 3500
Wire Wire Line
	4050 3700 4500 3700
Wire Wire Line
	4500 3700 4500 3650
Wire Wire Line
	4500 3650 4700 3650
Wire Wire Line
	4700 3650 4700 3600
Wire Wire Line
	4700 3600 5200 3600
Text Notes 5650 3900 0    63   ~ 0
DTR\nRX\nTX\nVCC\nCTS\nGND
$Comp
L RF_Module:ESP-12F U2
U 1 1 5CAF7450
P 4550 2000
F 0 "U2" H 4550 2978 50  0000 C CNN
F 1 "ESP-12F" H 4550 2887 50  0000 C CNN
F 2 "RF_Module:ESP-12E" H 4550 2000 50  0001 C CNN
F 3 "http://wiki.ai-thinker.com/_media/esp8266/esp8266_series_modules_user_manual_v1.1.pdf" H 4200 2100 50  0001 C CNN
	1    4550 2000
	1    0    0    -1  
$EndComp
$Comp
L Device:R R2
U 1 1 5CAF75B5
P 5450 2300
F 0 "R2" V 5243 2300 50  0000 C CNN
F 1 "10kΩ" V 5334 2300 50  0000 C CNN
F 2 "Resistor_SMD:R_0805_2012Metric_Pad1.15x1.40mm_HandSolder" V 5380 2300 50  0001 C CNN
F 3 "~" H 5450 2300 50  0001 C CNN
	1    5450 2300
	0    1    1    0   
$EndComp
$Comp
L Connector:USB_B_Micro J3
U 1 1 5CAF7777
P 2050 1200
F 0 "J3" V 2152 1530 50  0000 L CNN
F 1 "USB_B_Micro" V 2061 1530 50  0000 L CNN
F 2 "Connector_USB:USB_Micro-B_Molex_47346-0001" H 2200 1150 50  0001 C CNN
F 3 "~" H 2200 1150 50  0001 C CNN
	1    2050 1200
	0    -1   -1   0   
$EndComp
$Comp
L power:+5V #PWR01
U 1 1 5CAF7841
P 1850 700
F 0 "#PWR01" H 1850 550 50  0001 C CNN
F 1 "+5V" H 1865 873 50  0000 C CNN
F 2 "" H 1850 700 50  0001 C CNN
F 3 "" H 1850 700 50  0001 C CNN
	1    1850 700 
	1    0    0    -1  
$EndComp
Wire Wire Line
	1850 700  1850 800 
$Comp
L Regulator_Linear:AMS1117-3.3 U1
U 1 1 5CAF7A60
P 3100 800
F 0 "U1" H 3100 1042 50  0000 C CNN
F 1 "AMS1117-3.3" H 3100 951 50  0000 C CNN
F 2 "Package_TO_SOT_SMD:SOT-223-3_TabPin2" H 3100 1000 50  0001 C CNN
F 3 "http://www.advanced-monolithic.com/pdf/ds1117.pdf" H 3200 550 50  0001 C CNN
	1    3100 800 
	1    0    0    -1  
$EndComp
Wire Wire Line
	2800 800  2650 800 
Connection ~ 1850 800 
Wire Wire Line
	1850 800  1850 900 
Wire Wire Line
	3400 800  3500 800 
Wire Wire Line
	4550 800  4550 1200
Wire Wire Line
	3100 1100 3100 1200
Wire Wire Line
	3100 2900 4100 2900
Wire Wire Line
	4550 2900 4550 2700
Wire Wire Line
	4100 3600 4100 3250
Connection ~ 4100 3600
Connection ~ 4100 2900
Wire Wire Line
	4100 2900 4550 2900
Wire Wire Line
	4250 3250 4100 3250
Connection ~ 4100 3250
Wire Wire Line
	4100 3250 4100 2900
Wire Wire Line
	4100 3600 4650 3600
Wire Wire Line
	2450 1200 2650 1200
Connection ~ 3100 1200
Wire Wire Line
	3100 1200 3100 2900
$Comp
L Device:C C1
U 1 1 5CAF7D48
P 2650 1000
F 0 "C1" H 2765 1046 50  0000 L CNN
F 1 "100µF" H 2765 955 50  0000 L CNN
F 2 "Capacitor_SMD:C_0805_2012Metric_Pad1.15x1.40mm_HandSolder" H 2688 850 50  0001 C CNN
F 3 "~" H 2650 1000 50  0001 C CNN
	1    2650 1000
	1    0    0    -1  
$EndComp
$Comp
L Device:C C2
U 1 1 5CAF7DC3
P 3500 1000
F 0 "C2" H 3615 1046 50  0000 L CNN
F 1 "100µF" H 3615 955 50  0000 L CNN
F 2 "Capacitor_SMD:C_0805_2012Metric_Pad1.15x1.40mm_HandSolder" H 3538 850 50  0001 C CNN
F 3 "~" H 3500 1000 50  0001 C CNN
	1    3500 1000
	1    0    0    -1  
$EndComp
Wire Wire Line
	3500 850  3500 800 
Connection ~ 3500 800 
Wire Wire Line
	3500 800  3750 800 
Wire Wire Line
	3500 1150 3500 1200
Wire Wire Line
	3500 1200 3100 1200
NoConn ~ 2450 1300
NoConn ~ 2250 900 
NoConn ~ 2150 900 
NoConn ~ 2050 900 
Wire Wire Line
	2650 850  2650 800 
Connection ~ 2650 800 
Wire Wire Line
	2650 800  1850 800 
Wire Wire Line
	2650 1150 2650 1200
Connection ~ 2650 1200
Wire Wire Line
	2650 1200 3100 1200
$Comp
L Device:R R1
U 1 1 5CAFB45C
P 3750 1000
F 0 "R1" H 3820 1046 50  0000 L CNN
F 1 "10kΩ" H 3820 955 50  0000 L CNN
F 2 "Resistor_SMD:R_0805_2012Metric_Pad1.15x1.40mm_HandSolder" V 3680 1000 50  0001 C CNN
F 3 "~" H 3750 1000 50  0001 C CNN
	1    3750 1000
	1    0    0    -1  
$EndComp
Wire Wire Line
	3750 850  3750 800 
Connection ~ 3750 800 
Wire Wire Line
	3750 800  4550 800 
Wire Wire Line
	3750 1150 3750 1600
Wire Wire Line
	3750 1600 3950 1600
Wire Wire Line
	5150 2300 5300 2300
Wire Wire Line
	5150 1600 5450 1600
Connection ~ 4550 800 
Wire Wire Line
	5600 2300 5800 2300
Wire Wire Line
	5800 2300 5800 2900
Wire Wire Line
	5800 2900 4550 2900
Connection ~ 4550 2900
Wire Wire Line
	5300 3500 5300 3150
Wire Wire Line
	5300 3150 6350 3150
Connection ~ 5300 3500
Wire Wire Line
	5300 3500 5450 3500
Wire Wire Line
	5200 3600 5200 3050
Wire Wire Line
	5200 3050 6250 3050
Connection ~ 5200 3600
Wire Wire Line
	5200 3600 5450 3600
Wire Wire Line
	5100 3700 5100 4200
Wire Wire Line
	5100 4200 7400 4200
Wire Wire Line
	7400 4200 7400 800 
Connection ~ 5100 3700
Wire Wire Line
	5100 3700 5450 3700
Wire Wire Line
	5150 1700 6350 1700
Wire Wire Line
	6350 1700 6350 3150
Wire Wire Line
	6250 3050 6250 1500
Wire Wire Line
	5150 1500 6250 1500
$Comp
L Switch:SW_Push SW1
U 1 1 5CB0CEA1
P 5750 1400
F 0 "SW1" H 5750 1685 50  0000 C CNN
F 1 "SW_Push" H 5750 1594 50  0000 C CNN
F 2 "Button_Switch_SMD:SW_SPST_CK_RS282G05A3" H 5750 1600 50  0001 C CNN
F 3 "" H 5750 1600 50  0001 C CNN
	1    5750 1400
	1    0    0    -1  
$EndComp
Wire Wire Line
	5550 1400 5150 1400
Wire Wire Line
	5950 1400 6150 1400
Wire Wire Line
	6150 1400 6150 2300
Wire Wire Line
	6150 2300 5800 2300
Connection ~ 5800 2300
NoConn ~ 5150 1800
NoConn ~ 5150 1900
NoConn ~ 5150 2000
NoConn ~ 5150 2100
NoConn ~ 5150 2200
NoConn ~ 5150 2400
NoConn ~ 3950 2500
NoConn ~ 3950 2400
NoConn ~ 3950 2300
NoConn ~ 3950 2200
NoConn ~ 3950 2100
NoConn ~ 3950 2000
NoConn ~ 3950 1800
NoConn ~ 3950 1400
Text Label 4850 3500 0    50   ~ 0
RX
Text Label 4850 3600 0    50   ~ 0
TX
Wire Wire Line
	4550 800  5450 800 
$Comp
L Device:R R3
U 1 1 5CC9A463
P 5450 1000
F 0 "R3" H 5520 1046 50  0000 L CNN
F 1 "10kΩ" H 5520 955 50  0000 L CNN
F 2 "Resistor_SMD:R_0805_2012Metric_Pad1.15x1.40mm_HandSolder" V 5380 1000 50  0001 C CNN
F 3 "~" H 5450 1000 50  0001 C CNN
	1    5450 1000
	1    0    0    -1  
$EndComp
Wire Wire Line
	5450 850  5450 800 
Connection ~ 5450 800 
Wire Wire Line
	5450 800  7400 800 
Wire Wire Line
	5450 1600 5450 1150
$EndSCHEMATC
