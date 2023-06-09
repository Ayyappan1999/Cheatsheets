OpenVAS (Open Vulnerability Assessment System) is an open-source vulnerability scanner that helps in identifying security issues in computer systems and networks. Here's a cheatsheet of common OpenVAS commands:

1. **OpenVAS Setup and Configuration:**

- `openvas-setup`: Launches the initial setup wizard to configure OpenVAS.
- `openvas-check-setup`: Checks the status of the OpenVAS setup and configuration.
- `openvas-start`: Starts the OpenVAS services.
- `openvas-stop`: Stops the OpenVAS services.
- `openvas-rebuild`: Rebuilds the OpenVAS database.

2. **Managing OpenVAS Scans:**

- `omp`: OpenVAS Management Protocol command-line tool for managing scans.
- `omp -u <username> -w <password> -G`: Lists available scan configurations.
- `omp -u <username> -w <password> -T`: Lists existing scan targets.
- `omp -u <username> -w <password> -C`: Lists existing scan tasks.
- `omp -u <username> -w <password> -iX <scan_config_file.xml>`: Imports a scan configuration from an XML file.
- `omp -u <username> -w <password> -iX <target_file.xml>`: Imports a target from an XML file.
- `omp -u <username> -w <password> -S <scan_config_id> -T <target_id>`: Starts a scan using a specific configuration and target.
- `omp -u <username> -w <password> -G | grep '<config_name>' | awk -F" " '{print $1}' | xargs -I % omp -u <username> -w <password> --xml=<output_file.xml> -X "<create_task><name>Task Name</name><config id=\"%\"/><target id=\"Target ID\"/></create_task>"`: Creates a scan task for a specific configuration and target.

3. **Viewing OpenVAS Scan Results:**

- `omp -u <username> -w <password> -R <report_id>`: Retrieves the results of a specific scan report.
- `omp -u <username> -w <password> --xml="<get_tasks/>"`: Retrieves the list of existing scan tasks.
- `omp -u <username> -w <password> --xml="<get_results task_id='Task ID'/>"`: Retrieves the results of a specific scan task.
- `omp -u <username> -w <password> --xml="<get_reports task_id='Task ID'/>"`: Retrieves the reports of a specific scan task.

4. **OpenVAS Administration:**

- `omp -u <username> -w <password> -L`: Lists the users in the OpenVAS system.
- `omp -u <username> -w <password> -U <create_user.xml>`: Creates a new user using the XML file.
- `omp -u <username> -w <password> -u <user_id> -U <update_user.xml>`: Updates an existing user using the XML file.
- `omp -u <username> -w <password> -U <delete_user.xml>`: Deletes a user using the XML file.

