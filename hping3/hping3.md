# HPING3 Cheatsheet

1. `hping3 -h`: Displays the help menu for hping3.

2. `hping3 -c <count> <target>`: Sends a specified number of packets to the target.

3. `hping3 -S <target>`: Sends a SYN packet to the target.

4. `hping3 -A <target>`: Sends an ACK packet to the target.

5. `hping3 -F <target>`: Sends a FIN packet to the target.

6. `hping3 -P <target>`: Sends a PUSH packet to the target.

7. `hping3 -R <target>`: Sends a RST packet to the target.

8. `hping3 -T <target>`: Sends a TCP packet to the target.

9. `hping3 -U <target>`: Sends a UDP packet to the target.

10. `hping3 -I <interface> <target>`: Sends packets through a specified network interface.

11. `hping3 -p <port> <target>`: Sends packets to a specified port on the target.

12. `hping3 -i <interval> <target>`: Sends packets at a specified interval.

13. `hping3 -S -c 1 -w 64 -p 80 <target>`: Sends a single SYN packet to port 80 on the target with a window size of 64.

14. `hping3 -S -c 1 -w 64 -p 80 --tcp-timestamp <target>`: Sends a single SYN packet to port 80 on the target with a window size of 64 and a TCP timestamp.

```
+------------------------------------------------------------------------------------+
|                              hping3 Commands Cheatsheet                            |
+---------------------------------+--------------------------------------------------+
|            Command              |                    Description                   |
+---------------------------------+--------------------------------------------------+
| -h, --help                      | Display help menu                                |
| -v, --version                   | Display version information                      |
| -c, --count <value>             | Set packet count                                 |
| -i, --interval <value>          | Set packet interval (ms)                         |
| -a, --spoof <IP>                | Spoof source IP address                          |
| -p, --destport <value>          | Set destination port(s)                          |
| -s, --data-size <value>         | Set packet data size                             |
| -t, --ttl <value>               | Set IP TTL/hop limit                             |
| -k, --keep                      | Keep source IP address                           |
| --fast                          | Fast mode (minimal output)                       |
| --faster                        | Faster mode (no output)                          |
| --icmp                          | Use ICMP protocol                                |
| --tcp                           | Use TCP protocol                                 |
| --udp                           | Use UDP protocol                                 |
| --scan <port_range>             | Perform port scanning                            |
| --traceroute                    | Perform traceroute                               |
| --syn                           | Set SYN flag                                     |
| --ack                           | Set ACK flag                                     |
| --fin                           | Set FIN flag                                     |
| --push                          | Set PUSH flag                                    |
| --rst                           | Set RST flag                                     |
| --urg                           | Set URG flag                                     |
| --ecn                           | Set ECN flag                                     |
| --cwr                           | Set CWR flag                                     |
| --tos <value>                   | Set IP TOS value                                 |
| --frag                          | Enable IP fragmentation                          |
| --morefrag                      | Enable more IP fragmentation                     |
| --dontfrag                      | Disable IP fragmentation                         |
| --rand-source                   | Use random source ports                          |
| --flood                         | Perform flood attack                             |
| --rand-data                     | Use random packet data                           |
| --file <filename>               | Read packet data from file                       |
| -E <file>                       | Read hex packet from file                        |
| -q, --quiet                     | Quiet mode                                       |
| -V, --verbose                   | Enable verbose output                            |
| -L, --log <filename>            | Log packets to file                              |
| --log-xml <filename>            | Log packets to XML file                          |
| -0, -1, -2, -3, -4, -5, -6, -7, |
| -8                              | Set IP ID field value                            |
| -B <value>                      | Set IP ID increment value                        |
| -j, --ipproto <value>           | Set IP protocol                                  |
| -y, --ipopts <value>            | Set IP options                                   |
| -Z, --tcp-timestamp             | Set TCP timestamp option                         |
| -A, --ack-ack                   | Set ACK-ACK option                               |
| -N, --next-header               | Set Next Header value                            |
| -O, --data-verify               | Enable data verification                         |
| -o, --data-pattern <pattern>    | Set packet data pattern                          |
| --sign <keyfile>                | Sign packets with key                            |
| --verify <keyfile>              | Verify packets with key                          |
| --read-length <value>           | Set packet read length                           |
| --tr-keep-ttl                   | Keep TTL on traceroute                           |
| --icmp-type <value>             | Set ICMP type                                    |
| --icmp-code <value>             | Set ICMP code                                    |
| --winid <value>                 | Set TCP window ID                                |
| --seqnum <value>                | Set TCP sequence number                          |
| --acknum <value>                | Set TCP acknowledgment number                    |
| --tcp-ts-truncate               | Truncate TCP timestamp                           |
| --tcp-ts-eol                    | Set TCP timestamp EOL flag                       |
| --tcp-ack-eol                   | Set TCP ACK EOL flag                             |
| --tcp-sport <value>             | Set TCP source port                              |
| --tcp-dport <value>             | Set TCP destination port                         |
| --udp-sport <value>             | Set UDP source port                              |
| --udp-dport <value>             | Set UDP destination port                         |
+---------------------------------+--------------------------------------------------+
```
