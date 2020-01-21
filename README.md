# Smart Gas Sensor


## Authors

* Sylvain Dupouy
* Flavien Guillard

## Description

This project is divided into multiple subpart :

* A KiCad project to integrate the gas sensor inside the [`KiCad`](https://github.com/Nieflav/kicad_project) submodule
* An Arduino sample code inside the [`Arduino`](https://github.com/Sydpy/ArduinoGasMonitoring) submodule

This project was develop around a cstom gas sensor manufactured at AIME ( Center for Micro-Nano  Electronics) Toulouse. The sensor datasheet is available [here](https://github.com/MOSH-Insa-Toulouse/2019_MOSH_A2_SmartGasSensor/raw/master/doc/Gas_Sensor_Datasheet.pdf).

The KiCad project provides a reference Arduino shield integration of the sensor along with a LoRA module. The Arduino sample code uses the MQ-9 commercial gas sensor that has a similar operating interface as our custom sensor and thus, could be quite easily adapted.

Visit both submodules for more information.
