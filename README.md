# sql-server-ha-setup
sql server always on availability groups lab

## Information
SQL Server 2022
Windows Server 2022
SSMS 2020

## Server Info

| Server|Ip Address|Descs|
|-------|----------|-----|
|UATADDC|192.168.105.2|Domain Controller|
|UAT-WF-CLS|192.168.105.11|Windows Failover Cluster|
|UATKBANK.COM||Domain Name||
|UATHUBDB01|192.168.105.31||
|UATHUBDB01|192.168.105.32||
|UAT-HUB-WEB-AGL|192.168.105.34||
|UAT-HUB-APP-AGL|192.168.105.35||

## Database Info

|Id|Descs|
|-|------|
|HUBWEB |Payment Hub Web Service|
|HUBAPP |Payment Hub App Service|

### Port Config

|Port|Type|Descs|
|----|----|-----|
|1433|TCP|SQL Server TCP-In|
|1434|UDP|SQL Server UDP-In|
|5022|TCP|SQL Server End-Point|
