# UNICORNSCAN

Certainly! Here's a comprehensive cheatsheet for Unicornscan, a powerful network scanning tool:

```
+------------------------------------------------------------------------------------------------+
|                                    Unicornscan Commands Cheatsheet                             |
+---------------------------------+------------------------------------------------------------+
|               Command           |                         Description                        |
+---------------------------------+------------------------------------------------------------+
| -h, --help                      | Display help menu                                          |
| -m, --mode <mode>               | Set scan mode                                              |
| -I, --interface <iface>         | Set network interface                                      |
| -r, --range <range>             | Set target IP range                                        |
| -p, --ports <ports>             | Set target port(s)                                         |
| -q, --quick                     | Perform quick scan                                         |
| -s, --speed <speed>             | Set scan speed                                             |
| -t, --timeout <timeout>         | Set scan timeout                                           |
| -O, --output <file>             | Set output file                                            |
| --resume <file>                 | Resume a previous scan                                     |
| --status                        | Show status of current scan                                |
| --scaninfo                      | Show information about scan                                |
| --peers                         | Show peers' responses                                      |
| --sleep <time>                  | Set sleep time between scans                               |
| --hexdump                       | Print packets as hexdump                                   |
| --version                       | Display version information                                |
| --arp                           | Enable ARP mode                                            |
| --icmp                          | Enable ICMP mode                                           |
| --tcp                           | Enable TCP mode                                            |
| --udp                           | Enable UDP mode                                            |
| --udptraceroute                 | Perform UDP traceroute                                     |
| --packettrace                   | Perform packet trace                                       |
| --bpf <filter>                  | Set Berkeley Packet Filter (BPF)                           |
| --snarf                         | Snarf responses                                            |
| --scanconf <configfile>         | Set scan configuration file                               |
| --serviceprobes <probe_dir>     | Set service probes directory                              |
| --serviceprobe <probe_file>     | Set service probe file                                     |
| --serviceprobeseyecandy         | Enable service probes eyecandy                             |
| --servicediscovery              | Enable service discovery                                   |
| --servicediscoverydebug         | Enable service discovery debug mode                        |
| --servicediscoverydelay         | Set service discovery delay                                |
| --log <logfile>                 | Set log file                                               |
| --logconf <logconfigfile>       | Set log configuration file                                |
| --debug                         | Enable debug mode                                          |
| --verbose                       | Enable verbose output                                      |
| --quiet                         | Enable quiet mode                                          |
| --progress                      | Show progress                                              |
| --ignore-rst                    | Ignore TCP RST packets                                     |
| --ignore-tos                    | Ignore IP TOS field                                        |
| --max-queue <num>               | Set maximum number of packets to queue                     |
| --queue-bypass                  | Enable queue bypass                                        |
| --rawip                         | Enable raw IP mode                                         |
| --noarp                         | Disable ARP mode                                           |
| --noicmp                        | Disable ICMP mode                                          |
| --notcp                         | Disable TCP mode                                           |
| --noudp                         | Disable UDP mode                                           |
| --ttl <value>                   | Set IP TTL field                                           |
| --random                        | Use random source port                                     |
| --seq <sequence>                | Set TCP sequence number                                    |
| --ack <acknowledgment>          | Set TCP acknowledgment number                              |
| --ackack                        | Enable ACK-ACK mode                                        |
| --win <window>                  | Set TCP window size                                        |
| --mtu <value>                   | Set IP MTU size                                            |
| --tos <value>                   | Set IP TOS value                                           |
| --scan-delay <value>            | Set scan delay                                             |
| --bandwidth <value>             | Set bandwidth limit                                        |
| --ipid <value>                  | Set IP ID field                                            |
| --mss <value>                   | Set TCP maximum segment size                               |
| --icmp-type <type>              | Set ICMP type                                              |
| --icmp-code <code>              | Set ICMP code                                              |
| --icmp-id <id>                  | Set ICMP ID                                                |
| --icmp-seq <sequence>           | Set ICMP sequence number                                   |
| --udp-source-port <port>        | Set UDP source port                                        |
| --udp-destination-port <port>   | Set UDP destination port                                   |
| --tcp-source-port <port>        | Set TCP source port                                        |
| --tcp-destination-port <port>   | Set TCP destination port                                   |
| --spoof-ip <IP>                 | Spoof source IP address                                    |
| --spoof-mac <MAC>               | Spoof source MAC address                                   |
| --ttl-type <type>               | Set TTL type                                               |
| --ttl-value <value>             | Set TTL value                                              |
| --rp                      	    | Enable RP mode                                             |
| --rp-ipid <value>               | Set RP IP ID field                                         |
| --rp-ipopts <options>           | Set RP IP options                                          |
| --rp-tos <value>                | Set RP IP TOS value                                        |
| --rp-mtu <value>                | Set RP IP MTU size                                         |
| --rp-seq <sequence>             | Set RP TCP sequence number                                 |
| --rp-ack <acknowledgment>       | Set RP TCP acknowledgment number                           |
| --rp-win <window>               | Set RP TCP window size                                     |
| --rp-icmp-type <type>           | Set RP ICMP type                                           |
| --rp-icmp-code <code>           | Set RP ICMP code                                           |
| --rp-icmp-id <id>               | Set RP ICMP ID                                             |
| --rp-icmp-seq <sequence>        | Set RP ICMP sequence number                                |
+---------------------------------+------------------------------------------------------------+
```
