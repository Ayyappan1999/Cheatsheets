Here's a cheatsheet for aircrack-ng:

| Command                                               | Description                                                               |
|-------------------------------------------------------|---------------------------------------------------------------------------|
| `aircrack-ng <capture_file.cap>`                      | Perform a WEP or WPA/WPA2 key cracking attack on a captured handshake.     |
| `aircrack-ng -a 1 -b <BSSID> -w <wordlist.txt>`        | Crack a WEP key for a specific BSSID using a wordlist.                     |
| `aircrack-ng -a 2 -b <BSSID> -w <wordlist.txt> <capture_file.cap>` | Crack a WPA/WPA2 handshake using a wordlist.                 |
| `aircrack-ng -a 2 -b <BSSID> -w <wordlist.txt> -e <ESSID> <capture_file.cap>` | Crack a WPA/WPA2 handshake for a specific ESSID using a wordlist. |
| `aircrack-ng -S <capture_file.cap>`                   | Generate statistics for the captured handshake file.                       |
| `aircrack-ng -r <ivs_file.ivs>`                        | Recover a WEP key from an IVS file.                                         |
| `aircrack-ng -z <capture_file.cap>`                    | Perform a cracking attempt using optimized key search.                      |
| `aircrack-ng -l <cracked_key.txt> <capture_file.cap>`  | Load a cracked WEP or WPA/WPA2 key from a file.                              |
| `aircrack-ng -w <wordlist.txt> -r <ptw_file.cap>`      | Perform a WEP key cracking attack using the PTW method.                      |
| `aircrack-ng -x <key_format> <capture_file.cap>`       | Convert a WPA/WPA2 key from one format to another.                           |
| `aircrack-ng -p <plain_key> <capture_file.cap>`        | Test a plain-text key against a captured handshake file.                     |
| `aircrack-ng -J <output_prefix> <capture_file.cap>`    | Convert a WPA/WPA2 handshake to Hashcat format.                              |
| `aircrack-ng -e <ESSID> -c <channel> <capture_file.cap>` | Filter the capture file by ESSID and channel.                            |
| `aircrack-ng --help`                                   | Display the help menu.                                                      |
