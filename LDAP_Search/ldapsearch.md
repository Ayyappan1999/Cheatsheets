Certainly! Here's a cheatsheet for the `ldapsearch` command in table format:

| Command                                          | Description                                                        |
|--------------------------------------------------|--------------------------------------------------------------------|
| `ldapsearch -x -H ldap://<host>:<port> -b <baseDN>` | Perform a basic LDAP search using anonymous authentication.          |
| `ldapsearch -x -H ldap://<host>:<port> -b <baseDN> -D <bindDN> -w <password>` | Perform an authenticated LDAP search using a bind DN and password. |
| `ldapsearch -x -H ldap://<host>:<port> -b <baseDN> -D <bindDN> -W` | Prompt for the bind password interactively.                        |
| `ldapsearch -x -H ldap://<host>:<port> -b <baseDN> -D <bindDN> -w <password> -s sub <filter>` | Perform a sub-tree LDAP search with a specific filter.       |
| `ldapsearch -x -H ldaps://<host>:<port> -b <baseDN> -D <bindDN> -w <password>` | Perform an LDAP search over SSL/TLS using LDAPS.               |
| `ldapsearch -x -H ldap://<host>:<port> -b <baseDN> -D <bindDN> -w <password> -LLL` | Produce LDIF-formatted output.                                |
| `ldapsearch -x -H ldap://<host>:<port> -b <baseDN> -D <bindDN> -w <password> <attributes>` | Specify specific attributes to include in the search results. |
| `ldapsearch -x -H ldap://<host>:<port> -b <baseDN> -D <bindDN> -w <password> -E pr=100/noprompt` | Perform a paged LDAP search with a page size of 100 entries. |
| `ldapsearch -x -H ldap://<host>:<port> -b <baseDN> -D <bindDN> -w <password> -Z` | Start TLS encryption before performing the search.            |

These commands demonstrate different options and configurations for performing LDAP searches using the `ldapsearch` tool. Replace `<host>`, `<port>`, `<baseDN>`, `<bindDN>`, `<password>`, `<filter>`, and `<attributes>` with the appropriate values for your LDAP server and search requirements.
