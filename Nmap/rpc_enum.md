Certainly! Here's a cheatsheet in table format for RPC scan and SuperEnum Nmap scripts:
```
| NSE Script                                      | Description                                                   |
|-------------------------------------------------|---------------------------------------------------------------|
| `nmap -p 111 --script rpcinfo <target>`                   | Enumerate RPC services running on the target system.          |
| `nmap -p 111 --script rpc-grind <target>`                  | Perform an extensive RPC service enumeration.                 |
| `nmap -p 111 --script rpcap-info <target>`                 | Retrieve information about RPCAP (Remote Packet Capture) services. |
| `nmap -p 111 --script rpcbind-info <target>`               | Retrieve information about RPCBIND services.                  |
| `nmap -p 111 --script nfs-ls <target>`                      | Enumerate NFS (Network File System) shares.                  |
| `nmap -p 111 --script nfs-statfs <target>`                  | Retrieve statistical information about NFS shares.           |
| `nmap -p 111 --script msrpc-enum <target>`                  | Enumerate MSRPC (Microsoft Remote Procedure Call) services.  |
| `nmap -p 111 --script superenum <target>`                   | Perform an extensive enumeration of RPC services.            |
```

These NSE scripts can be executed with the `nmap` command, targeting port `111` (default RPC port). Adjust the `<target>` parameter to the IP address or hostname of the system you wish to scan and enumerate.
