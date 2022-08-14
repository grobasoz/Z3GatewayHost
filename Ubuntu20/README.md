# Z3GatewayHost
##  ZigBee Gateway Hosts for Silabs NCP - Ubuntu 20.04 Version

__Z3GatewayHost_6103__
* This version is for NCP firmware based on EmberZNet 6.10.3 - EZSP V8
  - Address Table Size = 100
  - Neighbor Table Size = 26
  - Packet Buffer Count = 250
  - Source Route Table Size = 200
  - Unicast Message Count = 32
  - Child Table Size = 32
  - Binding Table Size = 32


__Z3GatewayHost_710__
* This version is for NCP firmware based on EmberZNet 7.1.0 - EZSP V9
  - Address Table Size = 100
  - Neighbor Table Size = 26
  - Packet Buffer Count = 250
  - Source Route Table Size = 200
  - Unicast Message Count = 32
  - Child Table Size = 32
  - Binding Table Size = 32

<hr>
### Example of Run Command.
__Z3GatewayHost_xxx -fx -b115200 -p/dev/ttyUSB0__

Where
* -fx = Software Flow, -fh = Hardware Flow
* -b115200 = baud rate
* -p/dev/ttyUSB0 = Serial port

__Z3GatewayHost_xxx -h__ to get a list of command line options.

* NB Option -v doesn't seem to work correctly.