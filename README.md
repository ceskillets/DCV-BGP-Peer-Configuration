# DCV-BGP-Peer-Configuration 
This skillet will configure a BGP peer.  It needs to be combined with a redistribution profile in order to advertise routes to the peer.  This configuration assumes all of the default timers and values for BGP.

To use, fill out the requested variable values.  Once the configuration has been completed, combine this skillet with one that configures the redistribution profile, or configure the profile manually on the firewall.  The requested variables are:

•	local_address

•	local_as

•	local_interface

•	peer_as

•	peer_group_name

•	peer_ip

•	peer_name

•	peer_as

•	router_id

•	virtual_router_name
 
Support Policy
The code and templates in the repo are released under an as-is, best effort, support policy. These scripts should be seen as community supported and Palo Alto Networks will contribute our expertise as and when possible. We do not provide technical support or help in using or troubleshooting the components of the project through our normal support options such as Palo Alto Networks support teams, or ASC (Authorized Support Centers) partners and backline support options. The underlying product used (the VM-Series firewall) by the scripts or templates are still supported, but the support is only for the product functionality and not for help in deploying or using the template or script itself. Unless explicitly tagged, all projects or work posted in our GitHub repository (at https://github.com/PaloAltoNetworks) or sites other than our official Downloads page on https://support.paloaltonetworks.com are provided under the best effort policy.
