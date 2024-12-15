# Multi-Cosplay_Board
The board should be capable of driving nearly any electrically active cosplay suit or project including props. The system must also remain cheap and affordable with inter and extrapolation capabilities allowing it to be reducibly complex and still function. The software must also be easy to configure and implement (as this is a platform supported by [ARCOS](https://github.com/XCR1793/ARCOS)).

## Features
* Movement detection via the [ICM-20948](https://invensense.tdk.com/products/motion-tracking/9-axis/icm-20948/), which allows users to track their linear and angular accelerations for animations that require shaking, turning or any other activity requiring user displacement.
* Designed with a small form-factor which users can take advantage of by hiding the circuit board in tight spaces to not get it in the way of aesthetics.
* Fast processing core being the [ESP32-S3 Modules](https://www.espressif.com/en/products/socs/esp32) contains a 280Mhz dual core processor allowing partial asynchronous parallel calculations required for detecting user input and computing sequences at the same time whilst remaining as affordable as possible.

## Roadmap
* Milestone: Nothing Yet
* Work In Progress: Ideation & PCB Component Placement & Feature Integration
* Planned: MCB Version 1
* Planned: ARCOS Integration