# Workshop on crowdsourced data gathering

### Sensor box
Components:
* Raspberry Pi Zero W
* Particulate sensor SDS011, "Nova PM sensor" (+ flat white cable and USB-plug)
* Temperature/humidity/barometric pressure sensor BME280 (+ flat jumper wires, 4 wide)
* Power bank
* Casing

Once sensors are connected, connect the power bank, and the RPi should power up, indicated by a green light. Booting the device and starting up the bluetooth service takes approximately two minutes.

### Bt2Cloud (Android-application)
Download the [installer](https://github.com/City-of-Helsinki/bt2cloud-app/releases/download/v1.0.0rc/bt2cloud-release_v1.0.0rc.apk) and run it. This requires enabling Developer options (Settings -> About phone -> tap Build number 7 times)

To add a backend for sending the data, go to the Backends tab and press the green button in the corner:

<img src="https://github.com/VekotinVerstas/rpi-air-workshop/blob/master/images/bt2cloud_add_backend_010.png?raw=true" width="300">

Add the iot.fvh.fi backend (modify with your own username and password):

<img src="https://github.com/VekotinVerstas/rpi-air-workshop/blob/master/images/bt2cloud_add_backend_020.png?raw=true" width="300">

Make sure the backend you added is selected and blue:

<img src="https://github.com/VekotinVerstas/rpi-air-workshop/blob/master/images/bt2cloud_add_backend_030.png?raw=true" width="300">

Pressing the Send button should give a success message:

<img src="https://github.com/VekotinVerstas/rpi-air-workshop/blob/master/images/bt2cloud_add_backend_040.png?raw=true" width="300">
