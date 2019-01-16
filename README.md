# Simple-Network-management-Protocol

* Perl 
* Python
* Php
* SqLite3
* Influxdb
* Grafana

1. Creating subagent
> This script creates a custom SNMP counter to an enterprise OID with an mathematical algorithm and then probes for a single OID.

2. GetTrapR
> This script 
A script (1) which models a custom SNMP counter and makes it available through an enterprise OID. Another script to probe (2) the SNMP agent and find the rate of change for several counters between successive probes/samples. A wrapper script (3) around the SNMP prober output to Influx DB after necessary processing and Configuring to Grafana. Creating a system that listens for SNMP traps (4).

