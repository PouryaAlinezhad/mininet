# SDN emulation programs by python and mininet
 
Using Mininet, implemented the attached simple LAN topology, with no default controller, so we need
to input flows into the switches, to this end we can use the ovs-ofctl command to add flows into the
switches, we are using Openflow here, so we need to input the correct match fields and actions into
the switches, in this simple topology, we just need to tell the switches to match on input and then
output on the other port.

