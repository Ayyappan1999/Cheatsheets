Certainly! Here's a cheatsheet for arpspoof, a tool used for ARP spoofing:

| Command                                        | Description                                                  |
|------------------------------------------------|--------------------------------------------------------------|
| `arpspoof -i <interface> -t <target> <gateway>` | Perform ARP spoofing, redirecting traffic from the target to the gateway. |
| `arpspoof -i <interface> -t <gateway> <target>` | Perform ARP spoofing, redirecting traffic from the gateway to the target. |
| `arpspoof -i <interface> -r`                    | Perform bidirectional ARP spoofing, intercepting traffic between the target and the gateway. |
| `arpspoof -i <interface> -c <client> <server>`  | Perform ARP spoofing, redirecting traffic from the client to the server. |
| `arpspoof -i <interface> -c <server> <client>`  | Perform ARP spoofing, redirecting traffic from the server to the client. |
| `arpspoof -i <interface> -p`                    | Poison the ARP cache of the target and the gateway.           |
| `arpspoof -i <interface> -s <target> <gateway>` | Poison the ARP cache of the target, redirecting traffic to the attacker. |
| `arpspoof -i <interface> -s <gateway> <target>` | Poison the ARP cache of the gateway, redirecting traffic to the attacker. |
| `arpspoof -i <interface> -D`                    | Disable the dynamic ARP caching on the local machine.          |
| `arpspoof -i <interface> -S`                    | Enable source MAC address spoofing.                           |
| `arpspoof -i <interface> -V`                    | Display the version information of arpspoof.                   |
| `arpspoof -h`                                  | Display the help menu for arpspoof.                            |
