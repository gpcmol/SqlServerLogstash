Logstash with SQL server
========================
Version Logstash 2.3.2

> First add a login to SQLServer (e.g. username=logstash, password=logstash):
https://youtu.be/3Lz9rFVRRfU

> Then enable TCP in SQL Server Configuration Manager
Look under SQL Server Network Configuration > set TCP on enabled and add port 1433 as in this video:
https://krishna21e.wordpress.com/2015/04/07/telnet-localhost-1433-not-working/

> Try to: telnet localhost 1433

> If this is right configure Logstash as follows:
execute the logstash file: <logstashfolder>/bin/logstash -f input.conf
