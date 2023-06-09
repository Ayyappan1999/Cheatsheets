Certainly! Here's a cheatsheet for performing NetBIOS enumeration using the Windows command line:

```
|---------------------------------------------------------------------------------------------|
| Command                | Description                                                        |
|------------------------|--------------------------------------------------------------------|
| `nbtstat -A <IP>`      | Displays the NetBIOS name table of a remote system.                |
| `nbtstat -a <Name>`    | Displays the NetBIOS name table of a specific computer.            |
| `nbtstat -n`           | Displays the local NetBIOS name table.                             |
| `nbtstat -r`           | Displays the NetBIOS name cache, including WINS-resolved names.    |
| `nbtstat -RR`          | Purges and reloads the NetBIOS name cache.                         |
| `nbtstat -S`           | Displays the session table and name table of a remote computer.    |
| `net view`             | Lists all shared resources on the local machine.                   |
| `net view <IP>`        | Lists all shared resources on a remote system.                     |
| `net use \\IP\Share`   | Connects to a shared resource on a remote system.                  |
| `net use * /delete`    | Disconnects all network connections.                               |
| `net session`          | Lists all active sessions on the local machine.                    |
| `net session /list`    | Lists all active sessions on a remote system.                      |
| `nbtstat -s`                        | Displays the NetBIOS session table.                                  |
| `nbtstat -c`                        | Displays the NetBIOS remote cache name table.                        |
| `nbtstat -n <Adapter>`               | Displays the NetBIOS name table for a specific network adapter.      |
| `nbtstat -RR`                       | Releases and refreshes the NetBIOS names registered by the system.   |
| `nbtstat -S <SessionID>`             | Displays detailed information about a specific NetBIOS session.      |
| `net view /domain:<domain_name>`     | Lists all shared resources in a specific domain.                     |
| `net use /persistent:yes`            | Sets the persistent connection option for mapped network drives.     |
| `net use /persistent:no`             | Sets the non-persistent connection option for mapped network drives. |
| `net session /delete /ID:<SessionID>`| Ends a specific NetBIOS session.                                     |
| `net session /delete /all`           | Ends all NetBIOS sessions on the local machine.                      |

|-------------------------------------------------------------------------------------------------------------|
```

