Here's a cheatsheet for airmon-ng:

| Command                                          | Description                                                             |
|--------------------------------------------------|-------------------------------------------------------------------------|
| `airmon-ng start <interface>`                    | Start monitor mode on the specified wireless interface.                 |
| `airmon-ng stop <interface>`                     | Stop monitor mode on the specified wireless interface.                  |
| `airmon-ng check`                                | Check for interfering processes before starting monitor mode.           |
| `airmon-ng check kill`                           | Kill interfering processes before starting monitor mode.                |
| `airmon-ng check none`                           | Disable interfering process check.                                      |
| `airmon-ng status`                               | Show the status of wireless interfaces and monitor mode.                |
| `airodump-ng <interface>`                        | Capture and display wireless network information.                       |
| `airodump-ng --channel <channel> <interface>`    | Capture wireless network information on a specific channel.              |
| `airodump-ng --bssid <BSSID> <interface>`        | Capture wireless network information for a specific BSSID.               |
| `airodump-ng --essid <ESSID> <interface>`        | Capture wireless network information for a specific ESSID.               |
| `airodump-ng --essid <ESSID> --channel <channel> <interface>` | Capture wireless network information for a specific ESSID on a specific channel. |
| `aireplay-ng -0 <count> -a <BSSID> -c <client> <interface>` | Send deauthentication packets to a client on a specific network.    |
| `aireplay-ng -1 0 -e <ESSID> -a <BSSID> -h <spoofed_MAC> <interface>` | Fake authentication with a specific network using a spoofed MAC address.    |
| `aireplay-ng -2 -b <BSSID> -h <spoofed_MAC> <interface>` | Perform a full handshake capture on a specific network using a spoofed MAC address. |
| `aireplay-ng -3 -b <BSSID> -h <spoofed_MAC> <interface>` | Perform an ARP request replay attack on a specific network using a spoofed MAC address. |
| `aireplay-ng -4 -b <BSSID> -h <spoofed_MAC> <interface>` | Perform an ARP injection attack on a specific network using a spoofed MAC address. |
| `aireplay-ng -5 -b <BSSID> -h <spoofed_MAC> <interface>` | Perform a client-less deauthentication attack on a specific network using a spoofed MAC address. |
| `aireplay-ng -6 -b <BSSID> -h <spoofed_MAC> <interface>` | Perform an interactive packet replay attack on a specific network using a spoofed MAC address. |
| `aireplay-ng -9 -e <ESSID> -a <BSSID> -h <spoofed_MAC> <interface>` | Perform an encrypted WEP packet recovery attack on a specific network using a spoofed MAC address. |
