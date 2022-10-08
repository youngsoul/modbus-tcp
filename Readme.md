# Modbus Example

## Slave Simulator

The slave simulator simulates a device or some hardware in the infrastructure.

https://www.modbusdriver.com/diagslave.html

download the linux version to the raspberrypi 

`tar xvf diagslave-3.2.tar.gz`

Run the diagslave with:
`sudo ./diagslave/arm-linux-gnueabihf/diagslave -m tcp -a 10 -p 502`

-a is the slave id, and this has to match what you send/read data from.

## Read / Write data to diagslave

Open the python files and update the IP address of the raspberry pi.  Execute the read/write in different terminals.

## Build

`pip-compile`

`pip install -r requirements.txt`


