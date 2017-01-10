# TSOC_PSoC4L - PSoC4 (Large) Embedded Module :


The TSOC_PSoC4L is a [PSoC4-Programmable System on Chip](http://www.cypress.com/documentation/datasheets/psoc-4-psoc-4200l-family-datasheet)
based board with integrated USB and Li-Po battery power and charging functions, 
in an Embedded Module format for the new thingSoC, Internet of Things open standard.


The TSOC_PSoC4L is a low cost, embeddable module featuring a PSoC4 "Large" device :

* 32-bit MCU Subsystem (48MHZ ARM Cortex-M0)
* USB Full-Speed Controller - 16 Endpoints
* Li-Po battery connector and integrated USB charger
* Programmable Analog Blocks (4 blocks)
* Programmable Digital Blocks (8 blocks)
* 3.3 Volt or 5.0 Volt Operation
* Serial Communication (3 Ports)
* Counter/Timers/PWMs (8 Ports)
* CAN (controller area network) Controller
* Battery Charge Status LED
* USER LED
* USER Pushbutton
* Optional 32Khz Oscillator for Real-Time Clock
* Optional High Precision Oscillator
* Optional FM24W256-G NVSRAM (32K Bytes Nonvolatile SRAM)
* [thingSoC Compliant Module](http://www.thingsoc.com)
* [Mikrobus Compatible Module](http://www.mikroe.com/mikrobus/) 


[![thingSoC TSOC_PSoC4L](https://raw.githubusercontent.com/thingSoC/TSOC_PSoC4L/master/TSOC_PSoC4L/images/TSOC_PSoC4L_model.png?raw=true)TSOC_PSoC4L](https://github.com/thingSoC/TSOC_PSoC4L)

**thingSoC Reference Designs** are example thingSoC implementations that implement
various reference and testing circuits for demonstrating the use of the thingSoC libraries.
These reference designs can serve as starting templates for user designs.

---------------------------------------

## TSOC_PSoC4L Instructions

The TSOC_PSoC4L comes preprogrammed with a command line interpreter (CLI)
that runs on the enumerated USB COM port by default. It can be changed to
run onother ports interactively.

Immediately after plugging in the USB or Li-Po battery power the TSOC_PSoC4L will :

1) Runs a USB bootloader for ten (10) seconds to allow you to update the firmware.
   Use the [Cypress Bootloader Host](http://www.cypress.com/documentation/application-notes/an68272-psoc-3-psoc-4-psoc-5lp-and-psoc-analog-coprocessor-uart)
   to load new firmware into the device to customize it.

2) Runs the RSVP command line interpreter with the following commands :
  * commands : display the list of currenyl available commands
  * info : display the firmware revision number and other board details
  * echo : echo the current command
  * test adc : display all current ADC channel values
  * test uart : sends test string to all UART ports
  * test boot : run the bootloader
  * console x : changes the console to port "X"
  * connect x y : connect port x to port y until the user button is pressed to exit  
    where :  X (Y) = 
    0 - USB Port
    1 - UART1 Port
    2 - UART2 Port
    3 - I2C1 Port
    4 - I2C2 Port
    5 - SPI1 Port
    6 - SPI2 Port

---------------------------------------
## Other Applications

The TSOC_PSoC4L can also drive other devices, such as Servos, Motors, Relays and more.
This requires custom firmware at the current time.


---------------------------------------

## TSOC_PSoC4L Status <a name="TSOC_PSoC4L_status"/>

**11/06/2016:** 
Revision 1.0 - Initial Layout released to OSHpark

---------------------------------------
## TSOC_PSoC4L Model Images


[![thingSoC TSOC_PSoC4L](https://raw.githubusercontent.com/thingSoC/TSOC_PSoC4L/master/TSOC_PSoC4L/images/TSOC_PSoC4L_top.png?raw=true)TSOC_PSoC4L](https://github.com/thingSoC/TSOC_PSoC4L)


[![thingSoC TSOC_PSoC4L](https://raw.githubusercontent.com/thingSoC/TSOC_PSoC4L/master/TSOC_PSoC4L/images/TSOC_PSoC4L_bot.png?raw=true)TSOC_PSoC4L](https://github.com/thingSoC/TSOC_PSoC4L)


---------------------------------------

## TSOC_PSoC4L Documentation Index <a name="TSOC_PSoC4L_documentation_index"/>

[TSOC_PSoC4L Project](http://thingsoc.github.io/projects/TSOC_PSoC4L.html)

[TSOC_PSoC4L Hardware](https://github.com/thingSoC/TSOC_PSoC4L/tree/master/TSOC_PSoC4L/hardware)


---------------------------------------

## thingSoC Documentation Index <a name="thingSoC_documentation_index"/>

[thingSoC Organization Website](http://thingSoC.github.io)

[thingSoC FAQ - Frequently Asked Questions](http://thingsoc.github.io/support/faq.html)

---------------------------------------

[![thingSoC](http://thingsoc.github.io/img/projects/thingSoC/thingSoC_thumb.png?raw=true) 
*thingSoC*](http://thingsoc.github.io)
