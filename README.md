# False positive details

### CVE-2016-10542
If java project name contains word `ws`, owasp dependency check `mvn clean org.owasp:dependency-check-maven:3.3.2:check` returns a vulnerability with severity `medium`.    

However as perdescription of this vulnerability, it is relevent for node js project

