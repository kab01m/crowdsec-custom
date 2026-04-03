# Custom configuration files for crowdsec agent

## Installation

Just copy entire sub-directory structure into /etc/crowdsec and run ```systemctl restart crowdsec```

## lighttpd

Derived from official nginx parser this parser enable lighttpd logs parsing. Error logs are pretty different though, so we just do capture only error string.

## Cisco logs

Work in progress
