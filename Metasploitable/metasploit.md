# MEtasploitable Framework

Certainly! Here's a comprehensive Metasploit Framework cheatsheet that covers various aspects of the tool:

**General Commands:**

- `msfconsole`: Launches the Metasploit console.
- `msfupdate`: Updates the Metasploit Framework to the latest version.
- `search <keyword>`: Searches for modules, exploits, or payloads based on a keyword.
- `info <module>`: Displays detailed information about a specific module.
- `use <module>`: Selects a specific module for exploitation.
- `show options`: Displays the options available for the selected module.
- `set <option> <value>`: Sets a value for a specific option.
- `exploit`: Executes the selected module or exploit.
- `back`: Returns to the previous context or module.
- `exit`: Exits the Metasploit console.

**Module and Exploit Commands:**

- `use <module>`: Selects a specific module for exploitation.
- `search <keyword>`: Searches for modules based on a keyword.
- `info <module>`: Displays detailed information about a specific module.
- `show options`: Displays the options available for the selected module.
- `set <option> <value>`: Sets a value for a specific option.
- `exploit`: Executes the selected module or exploit.
- `back`: Returns to the previous module context.
- `reload_all`: Reloads all modules and scripts.
- `show advanced`: Displays advanced options for the selected module.

**Payloads:**

- `payloads`: Lists available payloads.
- `set payload <payload_name>`: Sets the payload for the current module.
- `show payloads`: Displays detailed information about available payloads.
- `generate`: Generates the selected payload.
- `set LHOST <local_ip>`: Sets the local IP address for the payload.
- `set LPORT <local_port>`: Sets the local port for the payload.
- `set RHOST <remote_ip>`: Sets the remote target IP address for the payload.

**Exploits:**

- `show exploits`: Lists available exploits.
- `use <exploit_name>`: Selects a specific exploit for exploitation.
- `show targets`: Displays available targets for the selected exploit.
- `set target <target_index>`: Sets the target for the exploit.
- `show payloads`: Displays compatible payloads for the selected exploit.
- `set payload <payload_name>`: Sets the payload for the exploit.
- `show options`: Displays the options required by the selected exploit.
- `exploit`: Executes the selected exploit.

**Session and Exploitation Commands:**

- `sessions`: Lists active sessions.
- `sessions -i <session_id>`: Interacts with a specific session.
- `sessions -u <session_id>`: Upgrades a session to a Meterpreter session.
- `sessions -k`: Kills all active sessions.
- `background`: Backgrounds the current session.
- `route`: Manages route settings for sessions.
- `exploit -j`: Executes the selected module or exploit in the background.
- `exploit -z`: Executes the selected module or exploit and immediately exits.

**Post-Exploitation:**

- `sysinfo`: Retrieves system information from the compromised target.
- `shell`: Opens an interactive shell on the compromised target.
- `upload <local_file> <remote_path>`: Uploads a file to the compromised target.
- `download <remote_file> <local_path>`: Downloads a file from the compromised target.

**Other Useful Commands:**

- `db_status`: Displays the status of the database connection.
- `db_connect <connection_string>`: Connects to a specified database.
- `db_hosts`: Lists hosts stored in the database.
- `db_services`: Lists services stored in the database.
- `db_import <file>`: Imports data from an XML file into the database.
- `load <script>`: Loads a specific Metasploit script.
- `unset <option>`: Unsets the value of a specific option.
- `help`: Displays the help menu.
- `exit`: Exits the `msfconsole` command-line interface.
