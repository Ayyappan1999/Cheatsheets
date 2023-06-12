Here's a cheatsheet for WiFiphisher:

| Command                                                 | Description                                                           |
|---------------------------------------------------------|-----------------------------------------------------------------------|
| `wifiphisher`                                           | Launch the WiFiphisher tool.                                          |
| `wifiphisher -i <interface>`                             | Specify the interface to use for the attack.                          |
| `wifiphisher --essid <ESSID>`                            | Specify the target ESSID (Wi-Fi network name).                        |
| `wifiphisher --ap-mac <MAC>`                             | Specify the MAC address of the target access point.                   |
| `wifiphisher --channel <channel>`                        | Specify the Wi-Fi channel to use for the rogue access point.           |
| `wifiphisher --no-gateway`                               | Disable the automatic gateway detection.                              |
| `wifiphisher --no-phishing`                              | Disable the captive portal phishing page.                             |
| `wifiphisher --no-creds`                                 | Disable the collection of credentials.                                |
| `wifiphisher --no-handshakes`                            | Disable the collection of WPA/WPA2 handshakes.                        |
| `wifiphisher --no-polling`                               | Disable the AP polling for targets.                                   |
| `wifiphisher --channel-hop-time <seconds>`               | Set the duration for channel hopping in seconds.                       |
| `wifiphisher --deauth-interval <seconds>`                | Set the interval for deauthentication packets in seconds.              |
| `wifiphisher --deauth-packets <count>`                    | Set the number of deauthentication packets to send.                    |
| `wifiphisher --credentials <credentials_file.txt>`       | Specify a file containing pre-defined credentials for the phishing page. |
| `wifiphisher --html <custom_page.html>`                  | Specify a custom HTML phishing page.                                  |
| `wifiphisher --webroot <custom_webroot>`                 | Specify a custom web root directory.                                  |
| `wifiphisher --help`                                    | Display the help menu.                                                |
| `wifiphisher --no-jamming`                              | Disable the jamming of nearby Wi-Fi networks.                         |
| `wifiphisher --ignore-mac <MAC>`                         | Ignore a specific MAC address during the attack.                      |
| `wifiphisher --ignore-ssid <SSID>`                       | Ignore a specific SSID during the attack.                             |
| `wifiphisher --ignore-all`                               | Ignore all nearby networks during the attack.                         |
| `wifiphisher --target <target_file.txt>`                 | Specify a file containing a list of target SSIDs or MAC addresses.    |
| `wifiphisher --no-associations`                          | Disable the collection of associated client information.              |
| `wifiphisher --no-beacon`                                | Disable the broadcasting of rogue access point beacons.               |
| `wifiphisher --no-eviltwin`                              | Disable the creation of an Evil Twin access point.                    |
| `wifiphisher --no-update`                                | Disable automatic updates of the WiFiphisher tool.                    |
| `wifiphisher --timeout <seconds>`                        | Set the timeout duration for certain operations in seconds.           |
| `wifiphisher --proxy <proxy_address:port>`               | Specify a proxy server to use for internet access.                    |
| `wifiphisher --debug`                                    | Enable debug mode for more detailed output and logging.                |
| `wifiphisher --version`                                  | Display the version information for WiFiphisher.                       |
