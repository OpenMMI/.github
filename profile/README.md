# OpenMMI

Hi there and welcome to the OpenMMI project. OpenMMI's goal is to create a universal and open MMI system that can be used in many cars using a separate device sending output to your car's display. OpenMMI will come with some custom made features but will also support Apple CarPlay and Google Car. The intent is actually to let either of those be responsible for apps in the form of music, navigation, etc. The project is split up in different components: ui, os, fw, hw) you are a developer and want to contribute, find the component that you are comfortable with and start smashing keys. If you are a user and want to get help then for now the best thing to do is create a GitHub ticket.

## User Interface (ui)

Everything the user will see. The user interface will be created using Flutter and build for Linux but tested on Android for simplicity.

## Operating System (os)

The operating system. Embedded linux capable of running the ui and with drivers for the (to be decided) boards.

## Firmware (fw)

The firmware is responsible for some communication between hardware and the software. For example, it takes the user's car input (e.g. turning a knob, pressing the next song button) and translates it into a standardized input towards the operating system.

## Hardware (hw)

This repo will be mainly used to discuss the compatible hardware or special build operations required to get OpenMMI to work on unofficially supported hardware.
