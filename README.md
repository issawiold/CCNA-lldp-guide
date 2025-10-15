# CCNA-LLDP-Guide

lldp guide

\>en  
\#conf t  
fig#lldp run  
-must be done before specifying which interfaces to transmit or receive the lldp protocol on each device-  
-unlike cdp (which is Cisco only), this doesn't activate the data transfer globally-  
fig#int range f0/#-#  
if-range#lldp transmit  
if-range#lldp receive  
All the connections on the device must be of similar speed in Cisco for it to work on them all (fa, then all must be fa; ga, then all must be ga; a, then all must be a)  

====================================

For troubleshooting:  
\#show lldp (shows the status of lldp)  
\#show lldp neighbors (shows a list of the connected devices)  
\#show lldp neighbors detail (shows a detailed list about the lldp)
