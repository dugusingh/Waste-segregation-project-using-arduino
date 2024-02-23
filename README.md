# Waste-segregation-project-using-arduino
# Dry and Wet Waste Segregation Project using Arduino

## Overview
This project aims to automate the process of segregating dry and wet waste using Arduino microcontrollers and various sensors. By implementing this project, users can efficiently sort different types of waste, contributing to waste management and recycling efforts.

## Components Used
- Arduino Uno or compatible microcontroller board
- Moisture sensor for detecting wet waste
- Ultrasonic sensor for detecting dry waste
- Servo motors or DC motors for actuation

## Functionality
The waste segregation system detects and identifies dry and wet waste using sensors. The moisture sensor is used to detect wet waste by measuring the moisture content, while the ultrasonic sensor is used to detect dry waste by measuring the distance to the waste item. Based on the type of waste detected, the system activates the corresponding actuator (e.g., servo motor) to sort the waste into separate bins. LED indicators provide visual feedback on the sorting process, while an optional LCD display can be used for user interaction and status display.

## Setup Instructions
1. Connect the moisture sensor and ultrasonic sensor to the Arduino board according to the provided circuit diagram.
2. Upload the Arduino sketch (`waste_segregation.ino`) to the Arduino board using the Arduino IDE.
3. Ensure that the sensors are calibrated and properly positioned to detect dry and wet waste accurately.
4. Power on the Arduino board and observe the system's operation. Adjust sensor parameters and thresholds as needed for optimal performance.
5. Monitor the LED indicators and optional LCD display for real-time feedback on the waste segregation process.

## Dependencies
- Arduino IDE: The project is developed using the Arduino programming environment. Ensure that you have the latest version of the Arduino IDE installed on your computer.
- Libraries: Depending on the sensors used, you may need to install additional libraries for sensor interfacing and control. Refer to the documentation provided with each sensor for library installation instructions.

## Contributing
Contributions to the project are welcome! If you have ideas for improvements or new features, feel free to open an issue or submit a pull request on GitHub.


## Acknowledgements
- Special thanks to [Arduino](https://www.arduino.cc/) for providing the Arduino platform and community support.
- Thanks to the creators and contributors of the libraries used in this project for their valuable contributions.

## Contact
For questions, feedback, or inquiries about the project, please contact [Navtej Kumar Singh](pbitsector.solution8935@gmail.com).
