# WIRESHARK

### When viewing packet capture output in Wireshark, the default columns displayed in the packet list pane include the following:
```
No. - The packet number or sequence number.
Time - The timestamp of the packet.
Source - The source IP address or hostname.
Destination - The destination IP address or hostname.
Protocol - The protocol used in the packet (e.g., TCP, UDP, HTTP).
Length - The length of the packet in bytes.
Info - A brief summary or description of the packet.
```
### IP Address Filters:
```
ip.addr == x.x.x.x: Filter packets with a specific IP address
ip.src == x.x.x.x: Filter packets with a specific source IP address
ip.dst == x.x.x.x: Filter packets with a specific destination IP address
```

### Protocol Filters:
```
tcp: Filter all TCP packets
udp: Filter all UDP packets
http: Filter all HTTP packets
dns: Filter all DNS packets
```

### Port Filters:
```
tcp.port == x: Filter packets with a specific TCP port
udp.port == x: Filter packets with a specific UDP port
```

### Logical Operators:
```
&& (and): Combine filters with an AND condition
|| (or): Combine filters with an OR condition
! (not): Negate a filter condition
```
### Wireshark Capture  Mode
```
Promiscuous mode - Sets interface to capture all packets on a network segment to which it is associated to
Monitor mode - Setup the wireless interface to capture all traffic it can receive (Unix/ Linux only)
```

### Other Filters:
```frame.len == x: Filter packets with a specific frame length
eth.src == xx:xx:xx:xx:xx:xx: Filter packets with a specific source MAC address
eth.dst == xx:xx:xx:xx:xx:xx: Filter packets with a specific destination MAC address
```

### Main Toolbar Item
```
TOOLBAR ITEM	                MENU ITEM	                    DESCRIPTION 
Start	                    Capture → Start	           Uses the same packet capturing options as the previous session, or uses defaults if no options were set
Stop	                    Capture → Stop	           Stops currently active capture
Restart	                  Capture → Restart	         Restart active capture session
Options…	                Capture → Options…	       Opens “Capture Options” dialog box
Open…	                    File → open…	             Opens “File open” dialog box to load a capture for viewing
Save As…	                File → Save As…	           Save current capture file
Close	                    File → Close	             Close current capture file
Reload	                  View → Reload	             Reload current capture file
Find Packet…	            Edit →Find Packet…	       Find packet based on different criteria
Go Back	                  Go → Go back	             Jump back in the packet history
Go Forward	              Go → Go Forward	           Jump forward in the packet history
Go to Packet… 	          Go → Go to Packet…	       Go to specific packet
Go to First Packet	      Go → Go to First Packet	   Jump to first packet of the capture file
Go to last Packet	        Go → Go to last Packet	   Jump to last packet of the capture file
Auto Scroll in Live       View → Auto Scroll in      Auto scroll packet list during live 
Capture	                           Live Capture	                                 capture
Colorize	                View → Colorize	           Colorize the packet list (or not)
Zoom In	                  View → Zoom In	           Zoom into the packet data (increase the font size)
Zoom Out	                View → Zoom Out	           Zoom out of the packet data (decrease the font size)
Normal Size	              View → Normal Size	       Set zoom level back to 100%
Resize Columns	          View → Resize Columns	     Resize columns, so the content fits the width
```




Certainly! Here's a comprehensive cheatsheet of common Wireshark filters and commands:

```
+-------------------------------------------------------------------------------------------------------------+
|                                Wireshark Filters and Commands Cheatsheet                                    |
+-----------------------------------+---------------------------------------------------------+-------------------+
|            Filter/Command         |                        Description                        |      Example      |
+-----------------------------------+---------------------------------------------------------+-------------------+
| ip.addr                          | Filter packets based on IP address                        | ip.addr == 192.168.1.1    |
+-----------------------------------+---------------------------------------------------------+-------------------+
| tcp.port                         | Filter packets based on TCP port                           | tcp.port == 80            |
+-----------------------------------+---------------------------------------------------------+-------------------+
| udp.port                         | Filter packets based on UDP port                           | udp.port == 53            |
+-----------------------------------+---------------------------------------------------------+-------------------+
| http                             | Filter HTTP traffic                                       | http                      |
+-----------------------------------+---------------------------------------------------------+-------------------+
| dns                              | Filter DNS traffic                                        | dns                       |
+-----------------------------------+---------------------------------------------------------+-------------------+
| ip.src == <ip>                   | Filter packets with a specific source IP address          | ip.src == 192.168.1.1     |
+-----------------------------------+---------------------------------------------------------+-------------------+
| ip.dst == <ip>                   | Filter packets with a specific destination IP address     | ip.dst == 192.168.1.1     |
+-----------------------------------+---------------------------------------------------------+-------------------+
| tcp.flags.syn == 1               | Filter packets with the SYN flag set                      | tcp.flags.syn == 1        |
+-----------------------------------+---------------------------------------------------------+-------------------+
| tcp.flags.ack == 1               | Filter packets with the ACK flag set                      | tcp.flags.ack == 1        |
+-----------------------------------+---------------------------------------------------------+-------------------+
| tcp.flags.fin == 1               | Filter packets with the FIN flag set                      | tcp.flags.fin == 1        |
+-----------------------------------+---------------------------------------------------------+-------------------+
| tcp.flags.reset == 1             | Filter packets with the RST flag set                      | tcp.flags.reset == 1      |
+-----------------------------------+---------------------------------------------------------+-------------------+
| frame.time >= <time>             | Filter packets with a timestamp greater than or equal to a specified time | frame.time >= "2022-01-01 12:00:00" |
+-----------------------------------+---------------------------------------------------------+-------------------+
| frame.len > <size>               | Filter packets with a length greater than a specified size | frame.len > 1000          |
+-----------------------------------+---------------------------------------------------------+-------------------+
| tcp.stream == <stream_id>        | Filter packets belonging to a specific TCP stream         | tcp.stream == 5           |
+-----------------------------------+---------------------------------------------------------+-------------------+
| ip.src_host == <host>            | Filter packets with a specific source host                | ip.src_host == "example.com" |
+-----------------------------------+---------------------------------------------------------+-------------------+
| ip.dst_host == <host>            | Filter packets with a specific destination host           | ip.dst_host == "example.com" |
+-----------------------------------+---------------------------------------------------------+-------------------+
| ip.src == <subnet>               | Filter packets with a specific source subnet              | ip.src == 192.168.1.0/24 |
+-----------------------------------+---------------------------------------------------------+-------------------+
| ip.dst == <subnet>               | Filter packets with a specific destination subnet         | ip.dst == 192.168.1.0/24 |
+-----------------------------------+---------------------------------------------------------+-------------------+
| ssl                              | Filter SSL/TLS traffic                                    | ssl                       |
+-----------------------------------+---------------------------------------------------------+-------------------+
| http.request.method == <method>  | Filter HTTP requests with a

 specific HTTP method          | http.request.method == GET |
+-----------------------------------+---------------------------------------------------------+-------------------+
| http.response.code == <code>     | Filter HTTP responses with a specific response code       | http.response.code == 200  |
+-----------------------------------+---------------------------------------------------------+-------------------+
| tcp.analysis.retransmission      | Filter packets identified as retransmissions              | tcp.analysis.retransmission |
+-----------------------------------+---------------------------------------------------------+-------------------+
| tcp.analysis.duplicate_ack       | Filter packets identified as duplicate ACKs               | tcp.analysis.duplicate_ack  |
+-----------------------------------+---------------------------------------------------------+-------------------+
| tcp.analysis.out_of_order        | Filter packets identified as out-of-order                 | tcp.analysis.out_of_order   |
+-----------------------------------+---------------------------------------------------------+-------------------+
| tcp.analysis.window_full         | Filter packets identified as window full                  | tcp.analysis.window_full    |
+-----------------------------------+---------------------------------------------------------+-------------------+
| follow                           | Follow TCP stream for selected packet                     | Right-click packet > Follow > TCP Stream |
+-----------------------------------+---------------------------------------------------------+-------------------+
| Statistics > Conversations       | Display conversation statistics                          | Statistics > Conversations |
+-----------------------------------+---------------------------------------------------------+-------------------+
| Statistics > Protocol Hierarchy  | Display protocol hierarchy statistics                    | Statistics > Protocol Hierarchy |
+-----------------------------------+---------------------------------------------------------+-------------------+
| File > Export Objects > <Protocol>| Export objects (e.g., images, files) of a specific protocol| File > Export Objects > HTTP |
+-----------------------------------+---------------------------------------------------------+-------------------+
```

These filters and commands will help you filter and analyze specific packets or protocols within Wireshark. Feel free to explore the Wireshark documentation or additional resources for more advanced filtering and analysis techniques.


