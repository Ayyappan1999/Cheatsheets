Certainly! Here's a cheatsheet of common msfconsole commands in table view:

| Command                               | Description                                          |
|---------------------------------------|------------------------------------------------------|
| `search <keyword>`                    | Search for modules, exploits, payloads, or vulnerabilities.             |
| `use <module>`                        | Select a module for use.                                            |
| `show options`                        | Display options for the selected module.                                |
| `set <option> <value>`                 | Set a value for the specified option.                                   |
| `exploit`                             | Run the selected exploit module.                                        |
| `set PAYLOAD <payload>`                | Set the payload to be used in the exploit.                              |
| `set RHOSTS <target>`                  | Set the target host or range of hosts.                                  |
| `set RPORT <port>`                     | Set the target port.                                                    |
| `set LHOST <host>`                     | Set the local host for the exploit.                                     |
| `set LPORT <port>`                     | Set the local port for the exploit.                                     |
| `set VERBOSE true`                     | Enable verbose output.                                                  |
| `sessions -l`                         | List all active sessions.                                               |
| `sessions -i <session_id>`             | Interact with a specific session.                                       |
| `sessions -k`                         | Terminate all active sessions.                                          |
| `show payloads`                       | List available payloads.                                               |
| `show exploits`                       | List available exploits.                                               |
| `show auxiliary`                      | List available auxiliary modules.                                      |
| `show options`                        | Display current module options.                                         |
| `setg <option> <value>`                | Set a global option value.                                              |
| `unset <option>`                       | Unset a specified option.                                               |
| `exit`                                | Exit the msfconsole.                                                    |
| `help`                                | Display help information.                                               |
| `msfvenom -p <payload> <options>`                      | Generate a payload with the specified payload type and options.  |
| `msfvenom -p <payload> -f <format> <options>`          | Generate a payload in the specified output format.               |
| `msfvenom --list payloads`                             | List available payloads.                                         |
| `msfvenom --list formats`                              | List available output formats.                                   |
| `msfvenom -l encoders`                                 | List available encoders.                                         |
| `msfvenom -l payloads | grep <keyword>`               | Search for payloads with a specific keyword.                     |
| `msfvenom -p <payload> --list-options`                 | List available options for a specific payload.                   |
| `msfvenom -p <payload> --payload-options`              | List available options and their values for a specific payload.  |
| `msfvenom -p <payload> LHOST=<IP> LPORT=<port> -f <format>` | Generate a payload with specified listener IP and port.        |
| `msfvenom -p <payload> -e <encoder> -f <format>`       | Generate a payload with specified encoder and output format.     |
| `msfvenom -p <payload> -b <badchars> -f <format>`      | Generate a payload with specified bad characters and format.     |
| `msfvenom -p <payload> -x <template> -k -f <format>`   | Generate a payload with specified template and format.           |
| `msfvenom -p <payload> -i <iterations> -f <format>`    | Generate a payload with specified number of iterations and format. |
