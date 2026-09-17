# Ex-12 Mini Project
## AUTOMATIC PLANT IRRIGATION SYSTEM USING ARDUINO

## ABSTRACT

Automatic plant irrigation is an important application in agriculture and gardening that helps provide the required amount of water to plants while reducing water wastage. This project presents the design and implementation of an Arduino-based automatic plant irrigation system using a soil moisture sensor and a water pump. 
The soil moisture sensor continuously detects the moisture level present in the soil and sends the sensor value to the Arduino microcontroller. The Arduino processes the sensor data and determines whether the soil is dry or sufficiently moist. When the soil becomes dry, the Arduino automatically activates the water pump through a relay module to supply water to the plant.
When the required moisture level is reached, the pump is automatically switched OFF. This system reduces the need for manual watering and ensures efficient water usage. The project demonstrates the integration of sensors, Arduino, relay control, and a water pump to create a simple, reliable, and cost-effective automatic irrigation system suitable for home gardens, agricultural fields, nurseries, and educational applications.

## CHAPTER 1 – INTRODUCTION

Automatic plant irrigation is a system designed to provide water to plants automatically based on the moisture level of the soil. Manual watering requires regular attention and may result in overwatering or underwatering. To overcome these problems, an automatic irrigation system can be used.
In this project, an Arduino UNO is used as the main controller.
A soil moisture sensor is used to detect the moisture content of the soil. When the soil becomes dry, the sensor sends a signal to the Arduino. The Arduino then activates the water pump through a relay module to supply water to the plant. When the soil reaches the required moisture level, the Arduino switches the pump OFF automatically.
This system helps reduce water wastage, saves time, and provides proper water supply to plants. It is a simple, low-cost, and efficient solution for home gardens, small agricultural areas, and plant nurseries.

## Objectives
The main objectives of the Automatic Plant Irrigation System are:

- To automatically detect the moisture level of the soil.
- To supply water to the plant when the soil becomes dry.
- To automatically switch OFF the water pump when sufficient moisture is detected.
- To reduce water wastage and manual effort.
- To develop a simple and low-cost irrigation system using Arduino.


## CHAPTER 2 – LITERATURE SURVEY

Automatic irrigation systems have been developed to reduce manual effort and improve the efficient use of water in agriculture and gardening. Traditional irrigation methods require regular monitoring and may lead to overwatering or water wastage.
Recent irrigation systems use soil moisture sensors to measure the moisture content of the soil. Microcontrollers such as Arduino can process the sensor readings and control a water pump automatically. When the soil becomes dry, the pump is switched ON, and when sufficient moisture is available, the pump is switched OFF.
Arduino-based irrigation systems are widely used because they are simple, low-cost, and easy to program. These systems can be useful for home gardens, plant nurseries, small farms, and educational applications. The use of automatic moisture-based control helps provide water according to the plant's requirement and reduces unnecessary water consumption.

## CHAPTER 3 – PROPOSED METHODOLOGY

The proposed system consists of the following main components:
- Arduino UNO
- Soil Moisture Sensor
- Relay Module
- Water Pump
- Water Tank
- Jumper Wires
- Power Supply



## CHAPTER 4 – HARDWARE DESCRIPTION

## ARDUINO UNO

Arduino UNO is a popular microcontroller board based on the ATmega328P. It is widely used in embedded system and automation projects because it is simple to program and provides digital and analog input/output pins. In the automatic plant irrigation system, the Arduino UNO receives the moisture value from the soil moisture sensor, processes the information, and controls the water pump through a relay module.

### Features:

* Arduino UNO Microcontroller
* ATmega328P processor
* 14 Digital I/O pins
* 6 Analog input pins
* USB connectivity
* Easy programming using Arduino IDE
* Low-cost and low-power operation

The Arduino UNO acts as the main controller of the automatic irrigation system. It continuously reads the soil moisture sensor value and decides whether the water pump should be switched ON or OFF.

<img width="750" height="500" alt="image" src="https://github.com/user-attachments/assets/f6261fcc-529e-4a9d-9f30-085db699d55e" />


## SOIL MOISTURE SENSOR

The soil moisture sensor is used to detect the moisture content present in the soil. It provides an electrical signal based on the moisture level, which is read by the Arduino through its analog input.

The sensor helps determine whether the soil is dry or sufficiently moist. When the soil becomes dry, the Arduino activates the water pump to supply water to the plant.

## RELAY MODULE

The relay module is used to control the water pump using the signal received from the Arduino. Since the Arduino cannot directly control the water pump, the relay acts as an electronic switch between the Arduino and the pump.

When the soil is dry, the Arduino activates the relay and turns ON the water pump. When sufficient moisture is detected, the relay is deactivated and the pump is switched OFF.

## WATER PUMP

The water pump is used to supply water from the water tank to the plant. It is controlled automatically by the Arduino through the relay module.

When the soil moisture level falls below the required level, the pump starts supplying water. Once the soil reaches sufficient moisture, the pump stops automatically.

## WATER TANK

The water tank stores the water required for irrigation. The water pump is connected to the water tank to transfer water to the plant through a suitable pipe.
The tank provides a continuous water source for the automatic irrigation system.

## JUMPER WIRES

Jumper wires are used to establish electrical connections between the Arduino, soil moisture sensor, relay module, and other components. They provide a simple and reliable connection between the components.

## POWER SUPPLY

A suitable power supply provides electrical power to the Arduino and other components of the irrigation system. The water pump should be supplied with the appropriate voltage and current required for its operation.

The power supply allows the system to operate continuously and automatically control the irrigation process.

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/dceca60c-4161-414f-92c9-8b60e902013d" />


# CHAPTER 5 – SOFTWARE IMPLEMENTATION

The system is programmed using the **Arduino IDE**. The program reads the data from the soil moisture sensor and processes it using the Arduino UNO. The Arduino continuously monitors the moisture level of the soil and determines whether the soil is dry or sufficiently moist. Based on the sensor value, the Arduino automatically controls the water pump through the relay module.

### The program performs the following steps:

● Initialize the Arduino and soil moisture sensor.

● Read the soil moisture sensor value.

● Process the sensor data.

● Compare the sensor value with the predefined moisture threshold.

● Turn ON the water pump when the soil is dry.

● Turn OFF the water pump when sufficient moisture is detected.

● Display the soil moisture value through the Serial Monitor.

# CHAPTER 6 – WORKING PRINCIPLE

The Arduino-based automatic plant irrigation system works based on soil moisture sensing and microcontroller control. The soil moisture sensor is placed in the soil near the plant to detect the moisture content. When the soil becomes dry, the sensor produces a corresponding electrical signal, which is read by the Arduino.

The Arduino processes the sensor value and compares it with a predefined threshold. If the soil is dry, the Arduino activates the relay module, which turns ON the water pump. The pump supplies water from the water tank to the plant. When sufficient moisture is detected in the soil, the Arduino switches OFF the relay and stops the water pump.

This provides a simple and efficient method for automatically watering plants and reducing unnecessary water usage.

# CHAPTER 7 – APPLICATIONS

The Automatic Plant Irrigation System can be used in various applications such as:

● Home gardens

● Agricultural fields

● Plant nurseries

● Greenhouses

● Terrace gardens

● Small-scale farming

● Smart gardening systems

The system can also be used in educational projects and other applications where automatic and efficient plant watering is required.

# CHAPTER 8 – RESULTS AND DISCUSSION

The developed Arduino-based automatic plant irrigation system successfully detects the moisture level of the soil using the soil moisture sensor. When the soil becomes dry, the sensor sends the corresponding value to the Arduino, which processes the data and activates the water pump through the relay module.

When the soil receives sufficient water and becomes moist, the Arduino automatically switches OFF the water pump. The soil moisture values can also be observed through the Serial Monitor.

The results demonstrate the successful integration of the Arduino UNO, soil moisture sensor, relay module, and water pump to create a simple, reliable, and cost-effective automatic irrigation system.

# CHAPTER 9 – CONCLUSION AND FUTURE SCOPE

## Conclusion

The Arduino-based Automatic Plant Irrigation System was successfully designed and implemented. The system automatically detects the moisture level of the soil and controls the water pump according to the moisture condition.

The project helped in understanding the working of soil moisture sensors, Arduino UNO, relay modules, water pumps, and embedded system programming. It provides a simple, reliable, and cost-effective solution for automatic plant watering while reducing manual effort and water wastage.

## Future Scope

The system can be further improved by adding additional sensors and IoT features for remote monitoring. A water-level sensor can also be added to monitor the water tank. Mobile applications, LCD displays, or cloud-based monitoring can be integrated in future versions to make the system more advanced and user-friendly.

## OUTPUT

<img width="1600" height="1200" alt="WhatsApp Image 2026-09-01 at 6 51 14 PM" src="https://github.com/user-attachments/assets/ca37e968-0aa1-4c1b-8713-73e217d28212" />

The Automatic Plant Irrigation System successfully detects the moisture level of the soil using the soil moisture sensor. When the soil becomes dry, the Arduino automatically turns ON the water pump through the relay module. The pump supplies water to the plant until the required moisture level is reached.

When the soil becomes sufficiently moist, the Arduino automatically turns OFF the water pump. The soil moisture values can also be viewed through the Serial Monitor.

Thus, the system successfully provides automatic watering to the plant, reduces manual effort, and helps prevent unnecessary water wastage.

