# blacklist
Process log files, search for predefined regex pattern, extract IP address if match is found, and add it to firewall

This script can be called from syslog, and it writes all events to its own logfile.

This particular implementation uses regex patterns to process Asterisk logs.

