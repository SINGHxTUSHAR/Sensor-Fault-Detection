[![GitHub license](https://img.shields.io/github/license/SINGHxTUSHAR/Sensor-Fault-Detection.svg)](https://github.com/SINGHxTUSHAR/Sensor-Fault-Detection/blob/master/LICENSE)
[![GitHub contributors](https://img.shields.io/github/contributors/SINGHxTUSHAR/Sensor-Fault-Detection.svg)](https://GitHub.com/SINGHxTUSHAR/Sensor-Fault-Detection/graphs/contributors/)
[![GitHub issues](https://img.shields.io/github/issues/SINGHxTUSHAR/Sensor-Fault-Detection.svg)](https://GitHub.com/SINGHxTUSHAR/Sensor-Fault-Detection/issues/)
[![GitHub pull-requests](https://img.shields.io/github/issues-pr/SINGHxTUSHAR/Sensor-Fault-Detection.svg)](https://GitHub.com/SINGHxTUSHAR/Sensor-Fault-Detection/pulls/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)


[![GitHub watchers](https://img.shields.io/github/watchers/SINGHxTUSHAR/Sensor-Fault-Detection.svg?style=social&label=Watch&maxAge=2592000)](https://GitHub.com/SINGHxTUSHAR/Sensor-Fault-Detection/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/SINGHxTUSHAR/Sensor-Fault-Detection.svg?style=social&label=Fork&maxAge=2592000)](https://GitHub.com/SINGHxTUSHAR/Sensor-Fault-Detection/network/)
[![GitHub stars](https://img.shields.io/github/stars/SINGHxTUSHAR/Sensor-Fault-Detection.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/SINGHxTUSHAR/Sensor-Fault-Detection/stargazers/)

[![Open in Visual Studio Code](https://img.shields.io/static/v1?logo=visualstudiocode&label=&message=Open%20in%20Visual%20Studio%20Code&labelColor=2c2c32&color=007acc&logoColor=007acc)](https://open.vscode.dev/SINGHxTUSHAR/Sensor-Fault-Detection)



# Sensor Fault Detection 📡🔌:

`Wafer Sensor Fault Prediction`

Brief: In electronics, a wafer (also called a slice or substrate) is a thin slice of semiconductor, such as a crystalline silicon (c-Si), used for the fabrication of integrated circuits and, in photovoltaics, to manufacture solar cells. The wafer serves as the substrate(serves as foundation for contruction of other components) for microelectronic devices built in and upon the wafer.

It undergoes many microfabrication processes, such as doping, ion implantation, etching, thin-film deposition of various materials, and photolithographic patterning. Finally, the individual microcircuits are separated by wafer dicing and packaged as an integrated circuit.
![Designer](https://github.com/SINGHxTUSHAR/Sensor-Fault-Detection/assets/113624520/a6bbeecf-478b-4424-8c85-64508df72806)


## Problem Statement 📝:
`Data: Wafers data`

`Problem Statement`: Wafers are predominantly used to manufacture solar cells and are located at remote locations in bulk and they themselves consist of few hundreds of sensors. Wafers are fundamental of photovoltaic power generation, and production thereof requires high technology. Photovoltaic power generation system converts sunlight energy directly to electrical energy.

The motto behind figuring out the faulty wafers is to obliterate the need of having manual man-power doing the same. And make no mistake when we're saying this, even when they suspect a certain wafer to be faulty, they had to open the wafer from the scratch and deal with the issue, and by doing so all the wafers in the vicinity had to be stopped disrupting the whole process and stuff anf this is when that certain wafer was indeed faulty, however, when their suspicion came outta be false negative, then we can only imagine the waste of time, man-power and ofcourse, cost incurred.

`Solution`: Data fetched by wafers is to be passed through the machine learning pipeline and it is to be determined whether the wafer at hand is faulty or not apparently obliterating the need and thus cost of hiring manual labour.

## Table of Contents 📌:

- [Features](#features)
- [Requirements](#requirements)
- [Setup](#setup)
- [Usage](#usage)
- [Data](#data)
- [Models](#models)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Features 📣:
* Real-time monitoring of sensor data.
* Detection of anomalies or faults in sensor readings.
* Customizable threshold settings for fault detection.
* Logging and reporting of detected faults.

## Requirements 🗒️:

Ensure you have the following dependencies installed:

- Python (version 3.9)
- Jupyter Notebook
- Other dependencies (refer to the requirements.txt)

You can install the required Python packages using:

```bash
pip install -r requirements.txt
```


## Setup 🔼:

- Clone the repository:
```bash
git clone https://github.com/SINGHxTUSHAR/Sensor-Fault-Detection.git
cd Sensor-Fault-Detection
```
- Create a virtual environment (optional but recommended):
```bash
python -m venv venv
```
- Activate the virtual environment:
  - On Windows:
   ```bash
   venv\Scripts\activate
   ```
  - On macOS/Linux:
  ```bash
  source venv/bin/activate
  ```

## Usage 🏗️:

- Open the Jupyter Notebook:
```bash
jupyter notebook
```
- Navigate to the water-sensor-prediction.ipynb notebook and open it.
- Follow the instructions in the notebook to run the code cells.

## DataSet Link 💬:
[https://www.kaggle.com/datasets/himanshunayal/waferdataset](https://www.kaggle.com/datasets/himanshunayal/waferdataset)

## Models ✅️:
* `XGBClassifier`
* `GradientBoostingClassifier`
* `SVC`
* `RandomForestClassifier`

## Contributing :
If you'd like to contribute to this project, please follow the standard GitHub fork and pull request process. Contributions, issues, and feature requests are welcome!

## Suggestion 🚀: 
If you have any suggestions for me related to this project, feel free to contact me at tusharsinghrawat.delhi@gmail.com or <a href="https://www.linkedin.com/in/singhxtushar/">LinkedIn</a>.

## License 📋:
This project is licensed under the <a href="https://github.com/SINGHxTUSHAR/Sensor-Fault-Detection/blob/main/LICENSE">MIT License</a> - see the LICENSE file for details.
