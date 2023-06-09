Nikto commands cheatsheet:

```
| Command                                 | Description                                                          |
|-----------------------------------------|----------------------------------------------------------------------|
| `nikto -h <target_host>`                | Perform a basic scan on the target host                              |
| `nikto -h <target_host> -o <output_file>` | Save scan results to a file                                          |
| `nikto -h <target_host> -F csv`           | Output results in CSV format                                         |
| `nikto -h <target_host> -F htm`           | Output results in HTML format                                        |
| `nikto -h <target_host> -p <port>`        | Scan a specific port                                                 |
| `nikto -h <target_host> -ssl`             | Force SSL connection                                                 |
| `nikto -h <target_host> -id <custom_header>` | Set custom headers in the request                                  |
| `nikto -h <target_host> -T <timeout>`      | Set the connection timeout                                           |
| `nikto -h <target_host> -C <cookie_string>` | Set cookie(s) for the request                                       |
| `nikto -h <target_host> -useragent <user_agent>` | Set a custom user agent                                          |
| `nikto -h <target_host> -evasion <technique>`     | Use evasion technique during the scan                            |
| `nikto -h <target_host> -r <range>`                | Scan a range of IP addresses                                     |
| `nikto -h <target_host> -404string <string>`       | Set a custom string to identify 404 responses                    |
| `nikto -h <target_host> -mutate <method>`          | Mutate attacks using different HTTP methods                      |
| `nikto -h <target_host> -p <port_range>`           | Scan a range of ports                                             |
| `nikto -h <target_host> -Cgidirs <directories>`    | Provide a list of CGI directories to scan                        |
| `nikto -h <target_host> -Plugins <plugins>`        | Enable or disable specific plugins                                |
| `nikto -h <target_host> -Tuning <tuning_options>`  | Configure scan tuning options                                     |
| `nikto -h <target_host> -E`                        | Enable advanced checks                                            |
| `nikto -h <target_host> -X <custom_file>`          | Use a custom Nikto configuration file                            |
| `nikto -h <target_host> -ask <type>`               | Ask for user input during the scan                                |
```
