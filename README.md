
# Remote-Soil-Moisture-Sensing

Employs language-standard C++, Arduino Uno, and Uno-compatible LoRa transceivers to implement soil-moisture radio broadcasts.  Uses PC-Uno serial connectivity. No third-part services are involved. Windows PC acts as base station.

The first stage of the overall effort in precision irrigation is available: https://github.com/SoothingMist/Embeddable-Software-for-Irrigation-Control.


# Code Files

Each zip file has a ReadMe to explain what it does and how to use it, to include figures. If something is not clear, please post a bug report or start a discussion.

* SerialComm-PC-to-Uno.zip : Illustrates serial communications between Windows PC and Arduino Uno.

* LoRa-Transmit-Receive-SoilMoisture-Serial.zip : Demonstrates LoRa transmission and reception of soil-moisture readings. Uses PC as server to process received messages. 

* QCustomPlotter-plots-serial.zip : Replaces Stage-3 PC console process in LoRa-Transmit-Receive-SoilMoisture-Serial.zip. This is an initial trial with graphical plotting.


# License

GNU Affero General Public License v3.0

Permissions of this strongest copyleft license are conditioned on making available complete source code of licensed works and modifications, which include larger works using a licensed work, under the same license. Copyright and license notices must be preserved. Contributors provide an express grant of patent rights. When a modified version is used to provide a service over a network, the complete source code of the modified version must be made available.

This is not legal advice. Learn more about repository licenses: https://docs.github.com/articles/licensing-a-repository/#disclaimer.
Additional license information is here: https://github.com/SoothingMist/Remote-Soil-Moisture-Sensing/blob/main/LICENSE.
