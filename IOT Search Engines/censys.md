# CENSYS IOT Search Engine

Certainly! Here's a cheatsheet for Censys, a search engine for internet-connected devices and IoT (Internet of Things) devices:

```
+-------------------------------------------------------+
|                Censys IoT Cheatsheet                   |
+-------------------------+-----------------------------+
|        Query            |         Description         |
+-------------------------+-----------------------------+
| tags:iot                | Search for IoT devices      |
|                         | and related information     |
+-------------------------+-----------------------------+
| ip:<IP_address>         | Search for devices with     |
|                         | a specific IP address       |
+-------------------------+-----------------------------+
| location.country:<country_code> | Search for devices  |
|                                | located in a specific      |
|                                | country                     |
+-------------------------+-----------------------------+
| location.city:<city_name>| Search for devices located  |
|                         | in a specific city           |
+-------------------------+-----------------------------+
| location.postal_code:<postal_code>| Search for devices |
|                                | located in a specific      |
|                                | postal code                 |
+-------------------------+-----------------------------+
| autonomous_system.asn:<ASN>| Search for devices        |
|                                | belonging to a specific    |
|                                | Autonomous System Number    |
+-------------------------+-----------------------------+
| parsed.subject_dn:"keyword"| Search for devices with  |
|                         | a specific keyword in the   |
|                         | subject distinguished name  |
+-------------------------+-----------------------------+
| parsed.issuer_dn:"keyword"| Search for devices with   |
|                         | a specific keyword in the   |
|                         | issuer distinguished name   |
+-------------------------+-----------------------------+
| parsed.x509.altnames:"keyword"| Search for devices     |
|                              | with a specific keyword   |
|                              | in the alternative names  |
|                              | of the X.509 certificate  |
+-------------------------+-----------------------------+
| parsed.x509.organization:"keyword"| Search for devices  |
|                                | with a specific keyword    |
|                                | in the organization name   |
|                                | of the X.509 certificate  |
+-------------------------+-----------------------------+
| parsed.x509.common_name:"keyword"| Search for devices   |
|                               | with a specific keyword    |
|                               | in the common name field   |
|                               | of the X.509 certificate  |
+-------------------------+-----------------------------+
| help                    | Display help documentation   |
+-------------------------+-----------------------------+
```
