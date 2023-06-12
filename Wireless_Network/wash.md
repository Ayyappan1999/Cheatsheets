Here's a cheatsheet for the `wash` tool:

| Command                                           | Description                                                        |
|---------------------------------------------------|--------------------------------------------------------------------|
| `wash -i <interface>`                             | Start scanning for WPS-enabled access points on the specified interface. |
| `wash -C`                                         | Check if the WPS configuration is locked on the access point.       |
| `wash -s <seconds>`                               | Set the scanning duration in seconds.                              |
| `wash -B`                                         | Enable bruteforce mode for PIN guessing.                            |
| `wash -b <BSSID>`                                 | Specify a target access point by its BSSID.                         |
| `wash -t <threads>`                               | Set the number of threads to use for bruteforce mode.               |
| `wash -d <delay>`                                 | Set the delay between PIN attempts in milliseconds.                 |
| `wash -m <mac>`                                   | Set the MAC address to use for bruteforce mode.                     |
| `wash -l <logfile>`                               | Save the scan results to a logfile.                                 |
| `wash -f <format>`                                | Set the output format for the scan results.                         |
| `wash -h`                                         | Display the help menu.                                              |
