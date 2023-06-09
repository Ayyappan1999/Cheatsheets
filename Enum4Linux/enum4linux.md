Certainly! Here's a cheatsheet for enum4linux commands:

```
| Command                                      | Description                                                             |
|----------------------------------------------|-------------------------------------------------------------------------|
| `enum4linux -a <target>`                       | Perform all available enumeration options on the target.                |
| `enum4linux -U <target>`                       | Enumerate usernames on the target using null sessions.                  |
| `enum4linux -N <target>`                       | Enumerate NetBIOS information on the target.                            |
| `enum4linux -S <target>`                       | Enumerate share information on the target.                              |
| `enum4linux -P <target>`                       | Enumerate password policy information on the target.                    |
| `enum4linux -G <target>`                       | Enumerate group information on the target.                              |
| `enum4linux -U <username> -P <password> <target>` | Authenticate using the provided username and password.                |
| `enum4linux -M <module> <target>`               | Load and run a specific enum4linux module on the target.                |
| `enum4linux -L <target>`                       | List available enum4linux modules.                                      |
| `enum4linux -h`                                | Display the help menu with available options.                           |
| `enum4linux -M rpcclient <target>`              | Enumerate information using the RPC client module.                      |
| `enum4linux -A <target>`                       | Perform aggressive enumeration on the target.                           |
| `enum4linux -d <target>`                       | Enable debug mode for verbose output.                                   |
| `enum4linux -f <file>`                         | Read targets from a file.                                               |
| `enum4linux -u <username> -p <password> <target>` | Specify a username and password for authentication.                   |
| `enum4linux -n <count> <target>`                | Set the number of concurrent processes to run.                          |
| `enum4linux -w <workgroup> <target>`            | Set the target workgroup name.                                          |
| `enum4linux -s <share> <target>`                | Enumerate specific share on the target.                                 |
| `enum4linux -o <output_file> <target>`          | Specify an output file to save results.                                 |
| `enum4linux -k <target>`                        | Skip null session enumeration.                                          |
| `enum4linux -i <interface> <target>`            | Specify a network interface for enumeration.                            |
```
