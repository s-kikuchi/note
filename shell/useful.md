## Shell useful command
### Filter Apache log
* For summarising the log data with the date
```
cut -d'[' -f2 FILE_PATH | cut -d' ' -f1 | cut -d':' -f1,2,3 | sort | uniq -c | grep 2018:02
```
* For checking the source IP address
```
cat /var/log/httpd/access_log | cut -d " " -f 3 | sort | uniq -c
```
### How to configure MaxClients in Apache configuration
https://qiita.com/bezeklik/items/85f4001a2517be5fe4c0
