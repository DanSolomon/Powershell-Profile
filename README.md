# Powershell-Profile

This code has been heavily modified to remove any pertinent details about machine names and pertinent details from things at UMIACS.

As such, this code can not be run as is (nor should it) but instead should serve as an example of my Powershell scripting abilities. 

The code was written to assist users with adding and removing Windows hosts to our network. As such, it handles the DNS, DHCP, Active Directory Object, and DHCP Allow Filter entry. Laptops were added using temporary IPs and as such have a seperate section in the code. 

There is a seperate function to remove a host from our network which was created to ensure that all aspects of the host are removed when the machine is retired or renamed. 
