# VivaQuant BLE Temperature Sensor

Welcome to the VivaQuant BLE Temperature Sensor project! This repository contains the source code and documentation for a Bluetooth Low Energy (BLE) temperature sensor developed using Simplicity Studio.

## Table of Contents
- [Introduction](#introduction)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Configuration](#configuration)
  - [Running the Sensor](#running-the-sensor)
- [Contact](#contact)

## Introduction
The VivaQuant BLE Temperature Sensor is designed to measure and transmit temperature data over BLE. It is built using the Silicon Labs hardware and the Simplicity Studio development environment.

## Getting Started

### Prerequisites
- Simplicity Studio installed on your development machine
- Silicon Labs EFR32BGxx Development Kit
- BLE-compatible device for testing (e.g., smartphone or BLE dongle)
- Basic knowledge of C programming and BLE concepts

### Installation
1. **Clone the repository:**
    ```bash
    git clone https://github.com/VivaQuant/BLE-Temperature-Sensor.git
    ```
2. **Open the project in Simplicity Studio:**
    - Launch Simplicity Studio.
    - Import the cloned repository as a new project.
3. **Build the project:**
    - Follow the build instructions provided in the Simplicity Studio documentation.

## Usage

### Configuration
- Modify the configuration files to set the desired parameters (e.g., advertising interval, connection interval).
- Ensure the sensor hardware is properly connected to the development kit.

### Running the Sensor
1. **Flash the firmware:**
    - Use Simplicity Studio to flash the compiled firmware onto the development board.
2. **Start the sensor:**
    - Power on the development board.
    - Use a BLE-compatible device to scan for and connect to the sensor.
    - Monitor the temperature data being transmitted.

## Contributing
We welcome contributions to improve and expand this project. To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## Contact
For any inquiries or support, please contact us at andrew.mtz03@outlook.com
