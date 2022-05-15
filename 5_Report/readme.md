# ABSTRACT #

Wiper is a fundamental part that used to clear raindrops or any water off of the vehicle's windscreen. The past framework used to actuate the wiper physically and the most common way of pulling up the wiper is hard to be dealt with. Hence, this framework is proposed to take care of these issues. The targets of this undertaking are to overhaul the more established vehicles framework by giving programmed cleaning framework, to work on the framework by utilizing sensor with actuator and to plan a fundamental program that will completely work with the framework. The idea of this proposed wiper framework is comparable with other existing ordinary wiper. Disregarding eliminating
water from windscreen. As the end for the undertaking, the outcomes shows all the point
targets are effectively accomplished. The wiper framework was well practically concurring the water condition from an external perspective of a
vehicle. This venture showed a commitment on the plan of the programmed wiper framework for the future exploration in this equivalent field. It
is prescribed that the framework to have a concentrate on the wiper material that been utilized to make a wiper in light of the fact that the driver at hot
furthermore, environment nation are dealing with the issues respects to the wiper material

# INTRODUCTION #
 The operational speed of a wiper is controlled by a wiper speed control system in accordance with frequencies. The pulse signal is digitally processed to provide a control signal. A wiper driver circuit receives the control signal and adjusts the operational speed or timing in line with it.
 
 # SOFTWARE REQUIREMENTS #
 
 GNU Toolchain
 STM Cube IDE
 QEMU
 
 
 
 # USES
  * This control system is utilised in printing and scanning machines ,heat ventilation, air conditioning, and security systems. 
  * This module can be found in a variety of household products.


## WORKING PRINCIPLE ##
# Ignition Key Position at ACC :
The Red LED is ON, if the user button is pressed and held for 2 secs
# Wiper ON:
Wiper is OFF: On press of the user input, Blue, Green and Orange LEDs come ON one at a time with the set frequency, The frequency changes on every alternate key press, 3 frequency levels with 1, 4 and 8 Hz
# Wiper OFF:
Wiper is ON: The LED glow pattern stops on the 4th press; the wiper action starts next press onwards as mentioned in step 2
# Ignition Key Position at Lock:
The Red LED is OFF, if the user button is pressed and held for 2 secs


## 4 W'S
 # WHAT IS WIPER SYSTEM
  Windscreen wipers are necessary for maintaining sufficient view for the driver, especially in modern high-speed cars.
 # WHY WIPER SYSTEM
   To keep the windscreen clean enough to give adequate view of vehicle screen at all times.
 # WHEN SHOULD USE WIPER SYSTEM 
  The windshield wipers remove rain and snow from the screen windshield, while the headlights improve visibility at night.
 # WHO DISCOVERED WIPER SYSTEM
  Mark Anderson invented on 1902
   


# TEST CASES and Corresponding Output

## High Level Test Cases
| Test ID | Description | Exp.i/p | Exp.o/p | Actual o/p | STATUS |
| --------|:------------|:--------|:--------|:-----------|:-------------|
| 1 | check if the BUTTTON is pressed  | program execution | Microcontroller/Engine will starts | LED ON(RED)| PASS |
| 2 | check if the BUTTTON is pressed  | program execution | WIPER starts | LED ON(BLUE)| PASS |
| 3 | check if the BUTTTON is pressed  | program execution | WIPER starts | LED ON(GREEN)| PASS |
| 4 | check if the BUTTTON is pressed  | program execution | WIPER starts | LED ON(ORANGE)| PASS |
| 5 | check if the BUTTTON is pressed  | program stops | Microcontroller/Engine stops | LED TURNED OFF| PASS |









## Low Level Test Cases
| Test ID | Description | Exp.i/p | Exp.o/p | Actual o/p | STATUS |
| --------|:------------|:--------|:--------|:-----------|:-------------|
| 1 | check if the BUTTTON is pressed  | program execution | Microcontroller/Engine starts | LED ON(RED)| PASS |
| 2 | check if the BUTTTON is pressed again | program execution | WIPER starts and speed of wiper is slow | LED ON(BLUE)| PASS |
| 3 | check if the BUTTTON is pressed again | program execution | WIPER starts and speed of wiper is moderate | LED ON(GREEN)| PASS |
| 4 | check if the BUTTTON is pressed again | program execution | WIPER starts and speed of wiper is good | LED ON(ORANGE)| PASS |
| 5 | check if the BUTTTON is pressed again | program starts | Microcontroller/Engine stops | LED TURNED OFF| PASS |

# ON STATE #
![usercase](https://github.com/Ashishsunku/practise/blob/f71375a48e1064b4ea2c14d1947f56b3f23a9886/op1.png)

# Wiper at LOW Speed #
![usercase](https://github.com/Ashishsunku/practise/blob/f71375a48e1064b4ea2c14d1947f56b3f23a9886/op2.png)

# Wiper at Moderate Speed #
![usercase](https://github.com/Ashishsunku/practise/blob/f71375a48e1064b4ea2c14d1947f56b3f23a9886/op3.png)

# Wiper at High Speed #
![usercase](https://github.com/Ashishsunku/practise/blob/f71375a48e1064b4ea2c14d1947f56b3f23a9886/op4.png)

# Wiper is at OFF state #
![usercase](https://github.com/Ashishsunku/practise/blob/f71375a48e1064b4ea2c14d1947f56b3f23a9886/op5.png)
