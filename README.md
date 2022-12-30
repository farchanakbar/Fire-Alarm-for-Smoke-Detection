# Fire-Alarm-for-Smoke-Detection
## About Dataset
[Link to a dataset diabetes](https://www.kaggle.com/datasets/deepcontractor/smoke-detection-dataset)

## Quick Start Guide

* Problem Type : Binary Classification
* Target Variable : Fire Alarm

## Context
A smoke detector is a device that senses smoke, typically as an indicator of fire. Smoke detectors are usually housed in plastic enclosures, typically shaped like a disk about 150 millimetres (6 in) in diameter and 25 millimetres (1 in) thick, but shape and size vary.

--> Types of Smoke Detectors

Photoelectric Smoke Detector
A photoelectric smoke detector contains a source of infrared, visible, or ultraviolet light, a lens, and a photoelectric receiver. In some types, the light emitted by the light source passes through the air being tested and reaches the photosensor. The received light intensity will be reduced due to scattering from particles of smoke, air-borne dust, or other substances; the circuitry detects the light intensity and generates an alarm if it is below a specified threshold, potentially due to smoke. Such detectors are also known as optical detectors.

Ionization Smoke Detector
An ionization smoke detector uses a radioisotope to ionize air. If any smoke particles enter the open chamber, some of the ions will attach to the particles and not be available to carry the current in that chamber. An electronic circuit detects that a current difference has developed between the open and sealed chambers, and sounds the alarm

The author of this dataset has successfully created a smoke detection device with the help of IOT devices and AI model. (Check Acknowledgement )

## About the dataset
* UTC: Time when experiment was performed
* Temperature[C]: Temperature of surroundings, measured in celcius
* Humidity[%]: Air humidity during the experiment
* TVOC[ppb]: Total Volatile Organic Compounds, measured in ppb (parts per billion)
* eCO2[ppm]: CO2 equivalent concentration, measured in ppm (parts per million)
* Raw H2: The amount of Raw Hydrogen [Raw Molecular Hydrogen; not compensated (Bias, Temperature etc.)] present in surroundings
* Raw Ethanol: The amount of Raw Ethanol present in surroundings
* Pressure[hPa]: Air pressure, Measured in hPa
* PM1.0: Paticulate matter of diameter less than 1.0 micrometer
* PM2.5: Paticulate matter of diameter less than 2.5 micrometer
* NC0.5: Concentration of particulate matter of diameter less than 0.5 micrometer
* NC1.0: Concentration of particulate matter of diameter less than 1.0 micrometer
* NC2.5: Concentration of particulate matter of diameter less than 2.5 micrometer
* CNT: Sample Count. Fire Alarm(Reality) If fire was present then value is 1 else it is 0
* Fire Alarm: 1 means Positive and 0 means Not Positive

Collection of training data is performed with the help of IOT devices since the goal is to develop a AI based smoke detector device.
Many different environments and fire sources have to be sampled to ensure a good dataset for training. A short list of different scenarios which are captured:

* Normal indoor
* Normal outdoor
* Indoor wood fire, firefighter training area
* Indoor gas fire, firefighter training area
* Outdoor wood, coal, and gas grill
* Outdoor high humidity
* etc.

The dataset is nearly 60.000 readings long. The sample rate is 1Hz for all sensors. To keep track of the data, a UTC timestamp is added to every sensor reading.
