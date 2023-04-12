# Dorks
These are some of the many Google Dorking commands available. With these commands, you can search for specific information on the web and get more accurate and relevant results.

### Search for subdomains
- site:*.domain.com -www.domain.com

### Search for files in a domain
- site:domain.com filetype:log | filetype:pdf | filetype:txt | filetype:xlsx | filetype:doc | filetype:sql | filetype:conf | filetype:ini 

### Search API DOCS in domain
- site:domain.com inurl:apidocs | inurl:api-docs | inurl:swagger | inurl:api-explorer  

### Search inurl keywords
- site:domain.com inurl:config | inurl:env | inurl:setting | inurl:backup | inurl:admin | inurl:php 

### Search for information on other websites
- site:pastebin.com "domain.com"
- site:xdocs.pl "domain.com"
- site:scribd.com "domain.com"
- site:s3.amazonaws.com "domain.com"
- site:dev.azure.com "domain.com"
- site:blob.core.windows.net "domain.com"
- site:googleapis.com "domain.com"
- site:drive.google.com "domain.com"
- site:onedrive.live.com "domain.com"
- site:digitaloceanspaces.com "domain.com"
- site:sharepoint.com "domain.com"
- site:s3-external-1.amazonaws.com "domain.com"
- site:s3.dualstack.us-east-1.amazonaws.com "domain.com"
- site:dropbox.com/s "domain.com"
- site:box.com/s "domain.com"
- site:docs.google.com inurl:"/d/" "domain.com"

### XSS prone parameters
- inurl:q= | inurl:s= | inurl:search= | inurl:query= inurl:& site:domain.com

### Apache Server Status Exposed
- site:*/server-status apache
  
### Search in social networks
- KeyWord @facebook / @twitter / @instagram ...

