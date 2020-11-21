# DDOS
DDoS Tool that supports:

    DNS Amplification (Domain Name System)
    NTP Amplification (Network Time Protocol)
    SNMP Amplification (Simple Network Management Protocol)
    SSDP Amplification (Simple Service Discovery Protocol)
Donation would be much appreciated: <a href="saweria.co/SECURITY87">here</a>

# Requirements

    OS Supports raw sockets
    Python 2.7
    Pinject

# _____           __    __              
	  / ___/____ _____/ /___/ /___ _____ ___ 
	  \__ \/ __ `/ __  / __  / __ `/ __ `__ \
	 ___/ / /_/ / /_/ / /_/ / /_/ / / / / / /
	/____/\__,_/\__,_/\__,_/\__,_/_/ /_/ /_/ 
	https://github.com/OffensivePython/Saddam
	   https://twitter.com/OffensivePython

Usage: 
Saddam.py target.com [options]        # DDoS
Saddam.py benchmark [options]         # Calculate AMPLIFICATION factor


Options:
  -h, --help            show this help message and exit
  -d FILE:FILE|DOMAIN, --dns=FILE:FILE|DOMAIN
                        DNS Amplification File and Domains to Resolve (e.g:
                        dns.txt:[evildomain.com|domains_file.txt]
  -n FILE, --ntp=FILE   NTP Amplification file
  -s FILE, --snmp=FILE  SNMP Amplification file
  -p FILE, --ssdp=FILE  SSDP Amplification file
  -t N, --threads=N     Number of threads (default=1)
