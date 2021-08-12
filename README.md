# tap-create
Creates tap devices and sets up a NAT

#### This was written because I wanted easier access to QEMU VMs since the default SLIRP networking is quite limited. Also, if you're using ethernet this is NOT what you want, setup a real bridge instead (this is a NAT)

### Note : Use dnsmasq.conf to start a DHCP server on the interface (br0) created
