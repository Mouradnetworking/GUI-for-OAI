## Table of Contents

- [Overview](#overview)
- [Youtube](#Youtube)
- [Features](#Features)
- [Usage](#usage)
- [Requirements](#Requirements)
- [License](#license)

## Overview
This Python GUI manages 5G simulation components: start/stop gNB and UE with RF simulator, SDR, Docker container control, configuration file, and GitHub access.

![Screenshot 2025-06-10 135536](https://github.com/user-attachments/assets/eb5f5cb2-4c9d-4072-aed6-b2d4dd37d738)


## Youtube
https://www.youtube.com/watch?v=SOSn9TCOz3o
## 5G Environment GUI

This repository contains a graphical user interface (GUI) developed in Python for controlling and managing various components of a 5G environment.

## Features

- **Start the gNB and UE with RF simulator and USRP:** Start the gNB (base station) and UE (user equipment).
- **Start/Stop Docker containers:** Start and stop Docker containers for additional components of the testbed.
- **Additional options:** Access additional options, checking logs, including opening relevant documentation on GitLab and access to the configuration file.

## Requirements

- Python 3.x
- Docker 

## Usage

1. Clone the repository to your local machine.
2. Ensure you have Python 3.x installed on your system.
3. Install the required dependencies using `pip install -r requirements.txt`.
4. Run the `mourad.py` file to launch the GUI.
5. Follow the on-screen instructions to interact with the simulation environment.

## License

This project is licensed under the [MIT License](LICENSE).
