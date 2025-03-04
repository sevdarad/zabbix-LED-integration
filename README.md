# zabbix-LED-integration
Introduction & Project Goal

In this project, I aim to enhance Zabbix alerting by integrating a multi-color LED notification system. In addition to the standard SMS alerts and dashboards provided to host owners, this system will activate an LED next to their monitors when a trigger reaches an alert state. The LED will change colors based on different alert levels, providing an immediate and visible indication of the system's status.

This documentation will cover the step-by-step process of implementing this functionality within Zabbix, including setting up a custom media type, configuring notifications, and integrating the LED control mechanism.

Hardware Requirements:

    LED: A multi-color LED that will be used to indicate different alert levels.
    Microcontroller: For this project, we are using the Raspberry Pi Pico, which will control the LED. It is essential to have the appropriate wiring and setup to ensure communication between the microcontroller and LED.

Software Requirements:

    Zabbix: The Zabbix monitoring system should be installed and properly configured. You can download it from the official Zabbix website: Zabbix Download.
    CircuitPython: CircuitPython needs to be installed on the Raspberry Pi Pico to run Python scripts. Ensure that the necessary setup is completed for the Pico. If you need help with this, you can refer to the guide: Raspberry Pi Pico IoT Demo.
    Python: Python must be installed to run scripts that handle the LED notifications. Make sure that the environment is prepared to run Python files on the Raspberry Pi Pico.
