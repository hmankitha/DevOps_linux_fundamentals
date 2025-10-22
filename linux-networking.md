# Linux Networking Commands

Networking is a key part of Linux, especially for servers and cloud environments. 
Here are the basic commands I use to check and manage networks.



## Checking Connectivity

- `ping domain_or_ip` : Test if a host is reachable.
- `curl url` : Fetch a webpage from the terminal.
- `wget url` : Download files from the internet.



## Network Information

- `ifconfig` or `ip a` : Show network interfaces and their IP addresses.
- `hostname -I` : Display the system's IP address.
- `netstat -tulnp` : Show open ports and listening services.
- `ss -tuln` : View active sockets and connections.



## DNS and Routing

- `nslookup domain_name` : Check DNS records for a domain.
- `traceroute domain_or_ip` : Trace the route packets take to reach a host.
- `route -n` : Display the routing table of the system.



## Tips

- Always check your IP address and network interface before configuring services.
- Use `ping` first to confirm connectivity before troubleshooting further.
