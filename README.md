# Smart-Irrigation-System-Using-Arduino

This project demonstrates a **Smart Irrigation System** that automatically waters plants based on the detected soil moisture levels. The system uses an **Arduino UNO** as the microcontroller, a **soil moisture sensor** to detect the dryness of the soil, and a **relay SPDT (Single Pole Double Throw)** to switch a water pump on or off using an **external power supply**.

The **soil moisture sensor** continuously measures the water content in the soil and sends an analog signal to the Arduino. When the soil becomes dry (i.e., the moisture value drops below a defined threshold), the Arduino activates the **relay SPDT**, which then connects the external power supply to the **DC water pump**, turning it on to irrigate the soil.

An **LED indicator**, connected to a digital pin through a **current-limiting resistor**, visually represents the status of the irrigation system—lighting up when the pump is operating. The **relay SPDT** acts as an electromechanical switch, isolating the low-power control circuit (Arduino) from the high-power load (pump and external supply), ensuring both **electrical safety** and **reliable switching**.

The external power supply is regulated through the relay to deliver the required current and voltage directly to the pump, preventing excess load on the Arduino board.

### Key Components:

* **Arduino UNO** – the main controller for logic and decision-making
* **Soil Moisture Sensor** – to detect moisture level in the soil
* **Relay SPDT (Single Pole Double Throw)** – for switching the pump with external power
* **DC Water Pump** – irrigates the soil when activated
* **External Power Supply (DC)** – provides sufficient power for the pump
* **LED Indicator + Resistor** – provides visual feedback of system status
* **Breadboard and Jumper Wires** – for circuit connections and prototyping

### Applications:

* Smart home gardening
* Precision agriculture
* Water conservation systems
* Automated greenhouse irrigation

This project helps reduce water wastage and manual effort, offering an **efficient and cost-effective solution** for automated plant watering systems.
