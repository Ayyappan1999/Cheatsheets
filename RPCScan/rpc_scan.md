Certainly! Here's a cheatsheet for RPCScan commands in a table view:

```
| Command                                     | Description                                                      |
|---------------------------------------------|------------------------------------------------------------------|
| `rpcscan <target>`                           | Enumerate all RPC services running on the target system.          |
| `rpcscan -p <port> <target>`                 | Enumerate a specific RPC service running on the target system.    |
| `rpcscan -m <module> <target>`               | Perform a specific module-based enumeration on the target system. |
| `rpcscan -s <script> <target>`               | Execute a specific script-based enumeration on the target system. |
| `rpcscan -a <target>`                        | Perform a comprehensive enumeration of all RPC services.          |
| `rpcscan -p <port> -a <target>`              | Perform a comprehensive enumeration of a specific RPC service.    |
| `rpcscan -p <port> -m <module> <target>`     | Perform a module-based enumeration of a specific RPC service.     |
| `rpcscan -p <port> -s <script> <target>`     | Perform a script-based enumeration of a specific RPC service.     |
| `rpcscan -l <file>`                          | Load a list of targets from a file and enumerate their RPC services. |
| `rpcscan -o <output>`                        | Save the enumeration results to the specified output file.        |
```

Note that the actual available options and modules may vary depending on the version and configuration of the RPCScan tool you are using. Adjust the command parameters, such as `<target>`, `<port>`, `<module>`, `<script>`, `<file>`, and `<output>`, as per your specific requirements.
