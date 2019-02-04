## Shell useful command
### Apache log check
```
cut -d'[' -f2 FILE_PATH | cut -d' ' -f1 | cut -d':' -f1,2,3 | sort | uniq -c | grep 2018:02
```
