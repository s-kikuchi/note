## Shell useful command
### Apache log check
* For summarising the log data with the date
```
cut -d'[' -f2 FILE_PATH | cut -d' ' -f1 | cut -d':' -f1,2,3 | sort | uniq -c | grep 2018:02
```
* For checking the source IP address
```
cat /var/log/httpd/access_log | cut -d " " -f 3 | sort | uniq -c
```
