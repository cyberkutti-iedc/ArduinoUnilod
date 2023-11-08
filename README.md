# Unilod Arduino Support Package


## Introduction

Welcome to the Unilod Arduino Support Package, which allows you to add Unilod boards to your Arduino IDE via the Arduino Board Manager.

Unilod is a family of compact, versatile development boards powered by the ATtiny85 microcontroller. These boards are designed to empower students, hobbyists, and developers, making it easy to work on simple IoT projects, ethical hacking, sensors, PWM projects, and IR projects.

## Installation

To add Unilod boards to your Arduino IDE, follow these steps:

1. Open the Arduino IDE.

2. Go to `File > Preferences`.

3. In the "Additional Boards Manager URLs" field, add the following URL:


Replace `https://github.com/ArduinoUnilod/package_unilod_index.json` with the actual URL where your `package_unilod_index.json` file is hosted.

4. Click "OK" to save the preferences.

5. Go to `Tools > Board > Boards Manager`.

6. Search for "Unilod" and click "Install" to add the Unilod Arduino Support Package to your Arduino IDE.

## Supported Boards

The Unilod Arduino Support Package currently supports the following board:

- Unilod Tiny6C8D: A compact board based on the ATtiny85 microcontroller.

## Getting Started

To get started with Unilod boards, follow these steps:

1. Connect your Unilod board to your computer using a suitable programming tool (e.g., an AVR programmer).

2. Select the "Unilod" board from the "Tools > Board" menu in the Arduino IDE.

3. Write your code in the Arduino IDE.

4. Upload your code to the Unilod board.

## Support and Documentation

For help and documentation, visit the Unilod website: [Unilod Documentation](https://github.com/cyberkutti-iedc/Unilod/blob/main/README.md).

For technical support, contact us at cyberkutti@gmail.com.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---

We invite you to explore Unilod further on our [website](https://github.com/cyberkutti-iedc/Unilod/blob/main/README.md) and reach out to us at cyberkutti@gmail.com.

---

By [Sreeraj V Rajesh](https://instagram.com/sreeraj_vr)


**Please note:** You can download the `package_unilod_index.json` file and place it in the following directory: `users => appdata => arduino15` for a seamless installation process.(Windows)
