# rfid-upload
This program reads from an MFRC522 chip and publishes the tag ID to the specified MQTT channel.

## Hardware
- WEMOS d1 Mini
- RFID-RC522
- Any buzzer/led/virbration motor

## Setup
- solder everything together
- set the pins in the first few lines in `rfid-upload.ino`
- copy `config.h.example` to `config.h` and fill in your credentials
- upload and use
