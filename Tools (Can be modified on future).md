
---

### SQLMAP

The most popular tool to exploit SQL Injection, comes for default on kali linux.

```bash
sqlmap -u http://<url> --random-agent 
sqlmap -u http://<url> --random-agent --delay --threads=1 --level=1 --risk=1
```

---