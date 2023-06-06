# CeWL - Custom Word List Generator

Certainly! Here's a cheatsheet for the `cewl` tool, a custom wordlist generator:

```
+-------------------------------------------------------+
|                     cewl Tool                          |
+-------------------------+-----------------------------+
|        Command          |         Description         |
+-------------------------+-----------------------------+
| cewl <url>              | Generate wordlist from the  |
|                         | specified URL               |
+-------------------------+-----------------------------+
| cewl <url> -w <output>  | Generate wordlist and save  |
|                         | it to a specified output     |
|                         | file                        |
+-------------------------+-----------------------------+
| cewl -d <depth> <url>   | Specify the maximum depth   |
|                         | of links to follow           |
+-------------------------+-----------------------------+
| cewl -m <min_word_len>  | Set the minimum word length |
| <url>                   | for generated words         |
+-------------------------+-----------------------------+
| cewl -M <max_word_len>  | Set the maximum word length |
| <url>                   | for generated words         |
+-------------------------+-----------------------------+
| cewl -w <output>        | Specify the output file     |
| -w <output>             | to save the generated        |
| <url>                   | wordlist                    |
+-------------------------+-----------------------------+
| cewl -a <accept_list>   | Specify a file containing   |
| <url>                   | a list of acceptable words  |
|                         | for generated words         |
+-------------------------+-----------------------------+
| cewl -e                 | Include email addresses in  |
| <url>                   | the generated wordlist      |
+-------------------------+-----------------------------+
| cewl -n                 | Include numbers in the      |
| <url>                   | generated wordlist          |
+-------------------------+-----------------------------+
| cewl -v                 | Verbose output, display     |
| <url>                   | detailed information        |
+-------------------------+-----------------------------+
| cewl -h                 | Display help menu           |
+-------------------------+-----------------------------+
```
