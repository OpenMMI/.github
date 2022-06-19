# OpenMMI

![Screenshot_1655635057](https://user-images.githubusercontent.com/580758/174476903-b4f0f0e2-09ef-4693-b9ab-0728887437f0.png)

Hi there and welcome to the OpenMMI project. OpenMMI's goal is to create a universal and open MMI system that can be used in many cars using a separate device sending output to your car's display.  If you are a user and want to get help then for now the best thing to do is create a GitHub ticket.

## Key Features
- Apple CarPlay
- Android Auto
- Multimedia (audio, video, CD, DVD)
- Communication (phone, contacts, messages, calendar over bluetooth)
- WiFi, web browser
- Integration with parking assistance (e.g. distance control, steering angle)
- Cameras (support for any RCA connected product basically)
- Vehicle information

## Contributing
If you are a software developer, embedded software engineer or hardware guru and want to contribute, find the component that you are comfortable with and start smashing those keys on your keyboard.

## Components
The project is split up in different components: ui, os, fw, hw

### User Interface (ui)

Everything the user will see. The user interface will be created using Flutter and build for Linux but tested on Android for simplicity. It is expected that thanks to the efforts in this project, Flutter will see more Linux compatibility.

### Operating System (os)

The operating system. Embedded linux capable of running the ui and with drivers for the (to be decided) boards.

### Firmware (fw)

The firmware is responsible for some communication between hardware and the software. For example, it takes the user's car input (e.g. turning a knob, pressing the next song button) and translates it into a standardized input towards the operating system.

### Hardware (hw)

This repo will be mainly used to discuss the compatible hardware or special build operations required to get OpenMMI to work on unofficially supported hardware.
