## Show the top 10 IPs with failed logins
```bash
> lastb | awk '{print $3}' | sort | uniq -c | sort -rn | head -10
```

## Show the top 10 usernames with failed logins
```bash
> lastb | awk '{print $1}' | sort | uniq -c | sort -rn | head -10
```
