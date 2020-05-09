# homeautomation-raspberrypi-nodered
A home automation project that uses Node-RED and a Raspberry Pi as a controller.

Flows
- Start/Stop Pi Camera using HTTP requests
- Camera streaming using WebSockets + motion detection (using OpenCV)
- Simple HTML Client app for controlling and viewing images that had motion

The package requires:
- python-function node
- 'fs' => see https://nodered.org/docs/user-guide/writing-functions#loading-additional-modules
