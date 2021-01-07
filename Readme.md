# Port AUTOSAR Drivers Version 4.0.3

## 												AUTOSAR Layers 
![Image of AUTOSAR](https://automotiveembeddedsite.files.wordpress.com/2016/12/autosar_layered_architecture_details.jpg?w=840)

In AUTOSAR, ordinary GPIO Driver is divided into 2 drivers:
- **Dio Driver** which responsible of writing/reading digital 0 or 1.
- **Port Driver** which responsible of setting all HW pins configurations (General Purpose DIO or alternative function, Analog or digital, input or output, etc.)

From the picture you can relate that Port & Dio are HW dependant, so that for every HW you need to build a new Dio & Port drivers

This projects implements Port Driver for TM4C123GH6PM

**There is a PDF generated by doxygen that describes the Port & Dio drivers components like:**
- Structures & Enums used in the code
- API names and its parameters
- How to use these APIs, structures and enums 



