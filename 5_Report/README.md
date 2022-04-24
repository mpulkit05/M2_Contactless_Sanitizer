# ABSTRACT
COVID pandemic has influenced human life in various sectors. Various attempts were made to reduce the virus transferring by work from home, social distancing, and also including hand hygiene. As COVID-19 are transferrable through touch and contact, there are WHO guidelines to clean or sanitize hands regularly to reduce the risk of infection. Dispensing of sanitizer from bottle and storage would require manual intervention. And so far, most of the available hand sanitizers do not operate automatically. This article aims to make an automatic hand sanitizer which finds it's use in hospitals, work places, offices, schools and much more to reduce the risk due to contact. Here, the system can sense the proximity with the help of ultrasonic sensor and sends signal to microcontroller. The controller processes the sensor data & actuates the pump and solenoid valve. And the result is the sanitizer liquid dispenses through mist nozzle.

# INTRODUCTION
Hygiene is an important aspect to remain healthy. There are various
aspects of hygiene. A clean hand is one of them. Hands generally
are touched at various surfaces and can be exposed to direct
contamination. Cleaning hands at regular interval is recommended by
various health organizations including WHO.
Hand hygiene is now regarded as one of the most important element
of infection control activities. In the wake of the growing burden
of health care associated infections (HCAIs), the increasing
severity of illness and complexity of treatment, superimposed by
multi-drug resistant (MDR) pathogen infections, health care
practitioners (HCPs) are reversing back to the basics of infection
preventions by simple measures like hand hygiene. This is because
enough scientific evidence supports the observation that if
properly implemented, hand hygiene alone can significantly reduce
the risk of cross-transmission of infection in healthcare
facilities (HCFs)1-5.

# Features 
* The automatic hand sanitizer dispensers can run for up to 1000 sanitization cycleswithout requiring a refill.
* Regular sanitization not only prevents the contraction of COVID-19 infection but also reduces the spread of it.

# 2H's & 2W's
* How automatic hand sanitizer dispenser work?
* How to use contactless hand sanitizer dispenser?
* Where to get contactless sanitizer dispenser?
* Why automatic hand sanitizer dispenser?

# TOOLS & SPECIFICATIONS
* ATMEGA32
  * SPECS      DESCRIPTION
  * Supplier:  Microchip Technology
  * Part No:   ATMEGA32-16AU
  * HTS:       8542310001
  * COO:       TH
  * ECCN:      EAR99
  * ADC Resolution: 10 bit
  * ![th](https://user-images.githubusercontent.com/101357248/164998426-37f3eb14-a0ff-49cc-a547-7a07f9733be0.jpg)

  
* ULTRASONIC SENSOR
 * Power Supply: DC 5V
 * Working Current: 15mA
 * Working Frequency: 40Hz
 * Ranging Distance : 2cm – 400cm/4m
 * Resolution : 0.3 cm
 * Measuring Angle: 15 degree
 * Trigger Input Pulse width: 10uS
 * Dimension: 45mm x 20mm x 15mm
 ![th (1)](https://user-images.githubusercontent.com/101357248/164998450-442468c7-8a55-47ed-895c-af576c6be559.jpg)

* ADAPTER
 * Input Voltage (V) 100 ~ 280 VAC @50 ~ 60Hz
 * Input current (mA) 100
 * Output Voltage (V) 5
 * Output current (A) 1
 * Load regulation (%) +/- 0.5
 ![th (2)](https://user-images.githubusercontent.com/101357248/164998463-df0f1db5-1ada-4ea0-9eb9-ba9072e5ccde.jpg)

* 3-6v Submersible Water Pump 
   Make sure that the water level is
   always higher than the motor. The dry run may damage the motor due
   to heating and it will also produce noise.
   • Operating Voltage (VDC) 2.5 to 6
   • Operating Current (mA) 130 to 220
   • Flow Rate (L/H) 80 to 120
   • Maximum Lift (mm) 40 to 110
   • Continuous Working Life (hours) 500
   • Driving Mode DC, Magnetic Driving
   • Material Plastic
   • Outlet outside diameter (mm) 7.5
   • Outlet inside diameter (mm) 5
   • Shipment weight 0.06 kg
   • Shipment dimensions 5 cm *4 cm *3 cm
   ![th (3)](https://user-images.githubusercontent.com/101357248/164998498-10e235ad-776c-48fc-96ca-9a4f87364fd7.jpg)
   
* PNP TRANSISTOR (BC547) :-
 • Transistor Type: NPN
 • Max Collector Current (IC): 100mA
 • Max Collector-Emitter Voltage (VCE): 45V
 • Max Collector-Base Voltage (VCB): 50V
 • Max Emitter-Base Voltage (VEBO): 6V
 • Max Collector Dissipation (Pc): 500 mW
 • Max Transition Frequency (fT): 300 MHz
![th (4)](https://user-images.githubusercontent.com/101357248/164998600-c24b92ea-b9b9-4dc0-8665-3ae0bad41f15.jpg)
# WORKING PRINCIPLE
![worki](https://user-images.githubusercontent.com/101357248/164998819-072d52ac-6e92-416b-80bc-0187b640bda9.PNG)
# Circuit Diagram
![Capture](https://user-images.githubusercontent.com/101357248/164998857-006512e0-0e30-4e63-aac8-e89b67011379.PNG)
![dfdf](https://user-images.githubusercontent.com/101357248/164998866-927c10b6-230b-455b-8a51-6f51c715cc28.PNG)
# TEST CASES
![test](https://user-images.githubusercontent.com/101357248/164998882-dfcf1784-29dc-440d-9050-f44a47897fbd.PNG)





