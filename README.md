# Unbound

NOTE: Please use the Unbound documentation to modify or understand what is happening to the DNS server.

Unbound is a recursive DNS server that can create custom DNS servers to either improve network reliability or minimize downtime. This is supposed to be a direct replacement for ISPs or public DNS servers if you want to manage your own network infrastructure. Usually the DNS server is one of the main issues when it comes to the internet going down, whether from the ISP's or public DNS server's side.

-----------------------------------------------------------------------

If issues appear on the DNS server, try using Pi-Hole's configuration example to see if Unbound is having issues or if the configuration file is having certain issues.

Installation of Unbound with Pi-Hole goes to Pi-Hole documentation:

- https://docs.pi-hole.net/guides/dns/unbound/?h=unbound

------------------------------------------------------------------------

The configuration file in Unbound could be used for any system that supports Linux. It's best to modify the configuration file for the system to fully utilize hardware resources and prevent bottlenecks when they come through authoritative DNS servers.

------------------------------------------------------------------------

Tweaks and Optimization for Unbound Documentation:

- https://unbound.docs.nlnetlabs.nl/en/latest/manpages/unbound.conf.html
