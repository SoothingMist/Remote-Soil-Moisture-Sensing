
# Remote-Soil-Moisture-Sensing

Employs web-based languages, Arduino Uno, and Uno-compatible LoRa transceivers to implement soil-moisture radio broadcasts.  Uses PC-Uno serial connectivity. No third-part services are involved. Windows PC acts as basestation. Basestation can also be hosted on a remote cloud system such as DigitalOcean (https://m.do.co/c/0023596ca262).

This is an evolving exploration into precision irrigation. The first phase of the overall effort in precision irrigation is available: https://github.com/SoothingMist/Embeddable-Software-for-Irrigation-Control.

# Code Files

LoRa-SoilMoisture-WebBased.zip : The main system. Contains all code modules.

DropoutTesting.zip : The beginnings of experiments with client/server when either halts, want to restart and reconnect without halting and restarting the whole system. Also want to remove starting-order as a requirement. This present version operates between Windoes and Linux systems across the internet or on localhost.

Each zip file has a ReadMe to explain the accompanying code modules, the associated hardware, how to put it all together, and how to use the resulting system. If something is not clear, please post a bug report or start a discussion. Would enjoy collaborating with those interested in this technology.

# License

GNU Affero General Public License v3.0

Permissions of this strongest copyleft license are conditioned on making available complete source code of licensed works and modifications, which include larger works using a licensed work, under the same license. Copyright and license notices must be preserved. Contributors provide an express grant of patent rights. When a modified version is used to provide a service over a network, the complete source code of the modified version must be made available.

This is not legal advice. Learn more about repository licenses: https://docs.github.com/articles/licensing-a-repository/#disclaimer.
Additional license information is here: https://github.com/SoothingMist/Remote-Soil-Moisture-Sensing/blob/main/LICENSE.
