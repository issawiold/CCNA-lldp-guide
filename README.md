# CCNA-lldp-guide
lldp guide
>en
#conf t
fig#lldp run
-must be done before specifing which interfaces to transmit or recieve the lldp protocol on ech device-
-unlike cdp (which is cisco only) this doesn't activate the data trransfer globally
fig#int ra f0/#-#
if-range#lldp t (to transmit)
if-range#lldp r (to receive)
All the conection on the device must be of similar speed in cisco for it to work on them all(fa, then all must be fa, ga tehn all must be ga, a then all must be a)
====================================

For troubleshooting
show lldp ( shows the status of lldp)
show lldp ne (shows a list of the conected devices)
show lldp ne de ( shows a detailed list about the lldp)
