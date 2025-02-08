# Local CTI

This repository is for storing and managing Local CTI files for use in Graylog Lookup Tables and Pipeline Rules. These files are maintinaed specifically for us, so use at your own risk. Data is pulled from CTI reports published by various government and commercial entities.

The format for all files is a two-column CSV with the first column labeled CTI type (e.g., "ip", "hash") and the second labeled "desc". The first column contents should be clear. The second column should contain a description of where the first was gathered (e.g., CISA report title, internal investigation description, etc.)

- cti_ips.csv

To alert on threats associated with IP addresses

- cti_hashes.csv

To alert on threats associated with file hashes

- cti_uas.csv

To alert on threats associated with UserAgentStrings
