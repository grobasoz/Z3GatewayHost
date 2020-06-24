# Z3GatewayHost
##  ZigBee Gateway Hosts for Silabs NCP

This version is for NCP firmware based on EmberZNet6.7.6

Normally run in Cygwin64, some additional files have been added to run from a Windows folder (tested with Win10-64 only). 

Download/Clone folder and run with command

__Z3gatewayHost -n0 -pCOMx__ for RTS/CTS flow hardware control

Or

__Z3gatewayHost -n1 -pCOMx__ for XOn/XOff flow software control

Alternatively run 
__Z3GatewayHost -h__ to get a list of command line options.

Address table size is set to 100.
