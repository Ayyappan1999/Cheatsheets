Certainly! Here's a cheatsheet for macchanger, a tool used for MAC address manipulation:

| Command                                    | Description                                                     |
|--------------------------------------------|-----------------------------------------------------------------|
| `macchanger -s <interface>`                 | Show the current MAC address of the specified interface.         |
| `macchanger -r <interface>`                 | Generate and set a random MAC address for the specified interface. |
| `macchanger -a <MAC_address> <interface>`   | Set a specific MAC address for the specified interface.           |
| `macchanger -l`                            | List available MAC addresses that can be used.                    |
| `macchanger -p <interface>`                 | Reset the MAC address of the specified interface to its permanent (original) MAC address. |
| `macchanger -e <interface>`                 | Enable MAC address randomization for the specified interface.     |
| `macchanger -m <mode> <interface>`          | Set the MAC address manipulation mode for the specified interface. Modes: `random`, `same`, `increment`, `decrement`. |
| `macchanger -b <vendor>`                    | Set the MAC address to a random address of the specified vendor.  |
| `macchanger -A`                            | Generate a random MAC address and display it.                     |
| `macchanger -v`                            | Enable verbose output for more detailed information.              |
| `macchanger -h`                            | Display the help menu for macchanger.                             |
| `macchanger -V`                            | Display the version information of macchanger.                    |
