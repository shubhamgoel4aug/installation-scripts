# Installation Scripts
Contains installation scripts for different tools. 

## ELK Stack
### Windows Server
**Script Location** : `/ELK Stack/Windows Server/elk-stack.ps1`    
**Usage**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*No SSL* : `elk-stack.ps1 -ELKPath C:\ELK`
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*No SSL Specific Version* : `elk-stack.ps1 -ELKPath C:\ELK -Version 8.1.0`
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Note** : Version should be a valid version string of any elk product (Elasticsearch, Logstash, Kibana)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*SSL* : `elk-stack.ps1 -ELKPath C:\ELK -Version 8.1.0 -SSL -DNS some.dns.com`
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Note** : DNS is required if SSL is enabled
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*SSL Specific Version* : `elk-stack.ps1 -ELKPath C:\ELK -Version 8.1.0 -SSL -DNS some.dns.com -Version 8.1.0`
