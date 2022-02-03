# Z3GatewayHost
##  ZigBee Gateway Hosts for Silabs NCP

__Z3GatewayHost_676.exe__
* This version is for NCP firmware based on EmberZNet6.7.6  - Address Table Size = 100
  
__Z3GatewayHost_676-AT20.exe__
* This version is for NCP firmware based on EmberZNet6.7.6 - Address Table Size = 20

__Z3GatewayHost_678.exe__
* This version is for NCP firmware based on EmberZNet6.7.8 - Address Table Size = 100

__MpZ3TcCustomTcHost.exe__
* This version is for testing the <a href="https://github.com/grobasoz/zigbee-firmware/tree/master/EFR32%20Series%202/EFR32MG21A020F1024">MultiPan NCP</a> with EmberZNet release 7.0.1

<br>
<br>

__Normally run in Cygwin64, some additional files have been added to run from a Windows folder (tested with Win10-64 only)__

Download/Clone folder and run with command

__Z3gatewayHost_xxx -n0 -pCOMx__ for RTS/CTS flow hardware control

Or

__Z3gatewayHost_xxx -n1 -pCOMx__ for XOn/XOff flow software control

Alternatively run 
__Z3GatewayHost_xxx -h__ to get a list of command line options.
