# Laptop 1
This folder only contains README which explains how to install and excute the broker running on Laptop1.

Broker running on Laptop1 should be started first for all the connections to be established.

### Broker

For broker, we suggest using HiveMQ MQTT Broker
This can be run over cloud or your local machine. For our case, we downloaded the broker and ran it in the local machine. 
Please see the details provided in the HiveMQ MQTT Broker to run it as per your need. 

Link to download HiveMQ MQTT Broker: https://www.hivemq.com/downloads/

#### Steps to run the broker

##### Linux/Unix/MacOSX
```
cd <hivemq_install_directory>/bin
./run.sh
```


##### Windows
right click on <hivemq_install_directory>\bin\run.bat
select "Run as administrator"

This runs the broker in the defaut port :1883

See the README.txt file in the downloaded folder to see more documentation.