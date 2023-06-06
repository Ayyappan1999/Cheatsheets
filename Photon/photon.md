# PHOTON

Certainly! Here's a cheatsheet for the Photon tool, a popular web crawler and directory scanner:

```
+-------------------------------------------------------+
|                     Photon Tool                        |
+-------------------------+-----------------------------+
|        Command          |         Description         |
+-------------------------+-----------------------------+
| python3 photon.py       | Run Photon tool             |
| -u <target_url>         | Specify target URL to scan  |
+-------------------------+-----------------------------+
| -l <target_list>        | Specify a file containing   |
|                         | a list of target URLs       |
+-------------------------+-----------------------------+
| -t <num_threads>        | Set the number of threads   |
|                         | for concurrent scanning     |
+-------------------------+-----------------------------+
| -r <num_retries>        | Set the number of retries   |
|                         | for failed requests         |
+-------------------------+-----------------------------+
| -c <cookies>            | Specify cookies to be       |
|                         | included in requests        |
+-------------------------+-----------------------------+
| -x <proxy>              | Set a proxy for requests    |
+-------------------------+-----------------------------+
| --delay <delay_time>    | Set a delay between         |
|                         | requests (in seconds)       |
+-------------------------+-----------------------------+
| --timeout <timeout>     | Set a timeout value for     |
|                         | requests (in seconds)       |
+-------------------------+-----------------------------+
| --user-agent <user_agent>| Set a custom user agent      |
+-------------------------+-----------------------------+
| --cookies-file <file>   | Load cookies from a file    |
+-------------------------+-----------------------------+
| --exclude <extensions>  | Specify file extensions to  |
|                         | exclude from scanning       |
+-------------------------+-----------------------------+
| --include <extensions>  | Specify file extensions to  |
|                         | include in scanning         |
+-------------------------+-----------------------------+
| --output <output_dir>   | Specify an output directory |
|                         | to save scan results        |
+-------------------------+-----------------------------+
| --dns                  | Enable DNS subdomain         |
|                         | enumeration                 |
+-------------------------+-----------------------------+
| --keys                 | Enable scanning for          |
|                         | sensitive keywords          |
+-------------------------+-----------------------------+
| --no-robots            | Ignore robots.txt file       |
|                         | for crawling                |
+-------------------------+-----------------------------+
| --only-urls            | Output discovered URLs       |
|                         | only, without scanning      |
+-------------------------+-----------------------------+
| --usernames-file <file> | Specify a file containing   |
|                         | a list of usernames for     |
|                         | username enumeration        |
+-------------------------+-----------------------------+
| --passwords-file <file> | Specify a file containing   |
|                         | a list of passwords for     |
|                         | password spraying           |
+-------------------------+-----------------------------+
| --plugins <plugin1,     | Specify a comma-separated   |
|   plugin2, ...>         | list of plugins to use      |
+-------------------------+-----------------------------+
| --update               | Update Photon tool to       |
|                         | the latest version          |
+-------------------------+-----------------------------+
| --version              | Display Photon version      |
+-------------------------+-----------------------------+
| --help                 | Display help menu           |
+-------------------------+-----------------------------+
```
