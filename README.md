# aws-sensehat An Amazing Project
Python script for sending Sense Hat data to AWS IoT

*This script runs on a Raspberry Pi with Sense Hat*

- When you push the joystick up, the temperature which has measured will be sent to AWS IoT over MQTT
- Temperature measurement is based on the CPU , Humidity and pressure temperature (The best one I found)
- Before running the script, some parameter inside the file must be replaced
- Certificates should be placed and indicated in the python file

