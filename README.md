# tap-create
Creates tap devices and sets up a NAT

#### If you're using ethernet then this is NOT what you want, setup a real bridge instead (this is a NAT)

#### This was written because I wanted easier access to QEMU VMs since the default SLIRP networking is quite limited

### Note : Use dnsmasq.conf to configure a DHCP server on the interface (br0) created
