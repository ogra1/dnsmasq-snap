This is a proof of concept snap of dnsmasq for use on UbuntuCore, 
it has all DNS features disabled and will only serve DHCP.

The current setup copies the default config into /var/snap/dnsmasq/current,
you can edit it there or modify the snap to ship a different config
from somewhere else by changing the install hook.

Dynamic generation of a config should be implemented from a configure hook
