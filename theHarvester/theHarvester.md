# theHarvester

### theHarvester Cheatsheet

Here's a cheatsheet for the popular OSINT (Open Source Intelligence) tool called theHarvester. It is used for gathering information and conducting reconnaissance on various targets such as email addresses, subdomains, and more.
The package contains a tool for gathering subdomain names, e-mail addresses, virtual hosts, open ports/ banners, and employee names from different public sources (search engines, pgp key servers).

<pre>
+-------------------------------------------------------+
|                 theHarvester Tool                      |
+-------------------------+-----------------------------+
|        Command          |         Description         |
+-------------------------+-----------------------------+
| -d <domain>             | Set the target domain       |
+-------------------------+-----------------------------+
| -b <source>             | Specify data source to      |
|                         | harvest from (e.g.,         |
|                         | google, bing, linkedin)     |
+-------------------------+-----------------------------+
| -l <limit>              | Limit the number of         |
|                         | search results per source   |
+-------------------------+-----------------------------+
| -s <source>             | Include only specific       |
|                         | sources (e.g., google,      |
|                         | bing, linkedin)            |
+-------------------------+-----------------------------+
| -f <filename>           | Save results to a file      |
+-------------------------+-----------------------------+
| -e <emails_only>        | Show only email addresses   |
|                         | in the results              |
+-------------------------+-----------------------------+
| -n <num_threads>        | Specify the number of       |
|                         | threads to use for searching|
+-------------------------+-----------------------------+
| -c <country_code>       | Limit results to a specific |
|                         | country (e.g., US, GB)      |
+-------------------------+-----------------------------+
| --domain <domain_name>  | Set the target domain       |
|                         | (alternative to -d)        |
+-------------------------+-----------------------------+
| --csv                   | Save results in CSV format  |
+-------------------------+-----------------------------+
| --limit <limit>         | Limit the number of         |
|                         | search results per source   |
|                         | (alternative to -l)        |
+-------------------------+-----------------------------+
| --exclude <source>      | Exclude specific sources    |
|                         | from the search             |
+-------------------------+-----------------------------+
| --source_file <file>    | Specify a file containing   |
|                         | a list of sources to use    |
+-------------------------+-----------------------------+
| --user_agent <agent>    | Set a custom user agent     |
+-------------------------+-----------------------------+
| --dns_lookup            | Perform DNS lookup on the   |
|                         | target domain               |
+-------------------------+-----------------------------+
| --virtual_hosting       | Use virtual hosting         |
+-------------------------+-----------------------------+
| --shodan_api <API_key>  | Use a Shodan API key for    |
|                         | enumeration (requires       |
|                         | Shodan module)              |
+-------------------------+-----------------------------+
| --hunter_api <API_key>  | Use a Hunter.io API key for  |
|                         | email enumeration           |
+-------------------------+-----------------------------+
| --version               | Show theHarvester version   |
+-------------------------+-----------------------------+
| --help                  | Show help menu              |
+-------------------------+-----------------------------+
</pre>
