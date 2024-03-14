### Lab3-Embedded-System-Development

## Done by:

### Bagirishya Rwema(bdominiq)  and NShuti(enshuti)

Our Lab-3 showcases a meticulously designed environmental monitoring and control system. It utilizes a microcontroller to gather real-time data on ambient temperature and light. This data can then be manipulated for further analysis. The system leverages powerful functionalities like Analog-to-Digital Conversion (ADC) for sensor readings, Serial communication (UART) for data transfer, and peripheral interfacing (GPIO, I2C) for device control. 

**Header Section:** - The header section contains information about the file and It provides a brief overview of what the code does and its intended usage.

**Includes** - This section includes necessary header files required for the code to function properly. In this case, it includes standard C libraries like <stdio.h> and <string.h>, as well as a custom library for interfacing with an LCD screen over I2C (liquidcrystal_i2c.h).

**Variable Declarations and Initializations:** - Here, various global variables and structures are declared and initialized. These variables store sensor readings, calibration values, message strings for UART transmission, and control parameters for the program's operation.

**Peripheral Initialization Functions:** - This section includes functions responsible for initializing different hardware peripherals used in the microcontroller system, such as ADC, UART, GPIO, and I2C. Each initialization function configures the corresponding peripheral according to the desired settings.

**Main Function:** - The main function serves as the entry point for the program's execution. It begins with system initialization, including setting up the clock configuration and initializing peripherals. Inside an infinite loop, it continuously performs tasks such as reading sensor values, updating the LCD display, and controlling the LED based on predefined conditions.

**Error Handling Function:** - The error handling function (Error_Handler) is called in case of critical errors encountered during the program's execution. It typically disables interrupts and enters an infinite loop to halt the system's operation and indicate an error condition.

### The Output/Demo:

---
# Challenges :'('  -:')


**1) Peripheral Configuration :** :

Configuring and initializing the various peripherals (such as ADC, UART, and I2C) correctly was challenging. Understanding the datasheets and reference manuals required careful attention, and dealing with complex hardware configurations added to the difficulty.

**2) Debugging Sensor Readings:** :

Ensuring accurate readings from temperature and light sensors was challenging due to noise or interference issues in the analog signals.also ensuring proper calibration procedures for the sensors posed difficulties.

**3) LCD Interface:** :

Interfacing with an LCD screen over I2C proved tricky. Ensuring proper initialization and adherence to communication protocols was challenging, and issues such as addressing errors and timing conflicts required thorough debugging.

**3) UART Communication:** :

Establishing reliable UART communication between the microcontroller and external devices, such as a computer monitor, was challenging. Attention to baud rate settings, data formatting, and error handling was crucial to ensure proper synchronization and flow control.


-------