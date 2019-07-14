### dev

* Use ipaddr.4.0.0 interfaces (@avsm)

### v2.0.0 (2019-02-24)

* Adjust to mirage-protocols 2.0.0 and mirage-net 2.0.0 changes
* Ethernet is now responsible for prefixing the Ethernet header
* MTU is required from the underlying network interface instead of as argument
  to connect
* Ethif/ETHIF are now Ethernet/ETHERNET

### v1.0.0 (2019-02-01)

* Minor ocamldoc improvements (@avsm).
* Initial import from mirage-tcpip (@hannesm).
  Based on source code from mirage-tcpip.3.6.0.
