# Installation Scripts
Contains installation scripts for different tools. 

## ELK Stack
### Windows Server
**Script Location** : `/ELK Stack/Windows Server/elk-stack.ps1`    
**Usage**
| Requirement         | Command       |
|---------------------|---------------|
| No SSL              | `elk-stack.ps1 -ELKPath C:\ELK` |
| No SSL With Version | `elk-stack.ps1 -ELKPath C:\ELK -Version 8.1.0` |
| SSL                 | `elk-stack.ps1 -ELKPath C:\ELK -Version 8.1.0 -SSL -DNS some.dns.com` |
| SSL With Version    | `elk-stack.ps1 -ELKPath C:\ELK -Version 8.1.0 -SSL -DNS some.dns.com -Version 8.1.0` |    
**Note** : Version should be a valid version string of any elk product (Elasticsearch, Logstash, Kibana)    
**Note** : DNS is required if SSL is enabled
