# cisco2mikrotik
Cisco to Mikrotik configuration converter

# Language
python2

# License
GPLv3+

# Usage
run ./cisco2mikrotik --help for info

# Requires
* <https://pypi.org/project/ciscoconfparse/1.1.24>
* <https://pypi.org/project/ipaddr/2.1.11/>
* <https://github.com/Delgan/loguru/releases/tag/0.3.2>

# Supported features
* Loopback\*, \*Ethernet, Dot1q-subinterfaces (not shutdowned and not in vrf-s)
* interface descriptions
* manual interface names mapping
* IPv4 addresses
* manual IPv4 addreses mapping
* IPv4 static routes
* input/output ACL-s (standard/extented) on interfaces
* extended ACLs with the port range, multiple ports for dst ports and established clause
* line vty interfaces to look for std acls
* local users (with passwords where possible)
