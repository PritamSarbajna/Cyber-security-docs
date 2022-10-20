## Used syntax :

### For directory busting :

```
gobuster dir -u http://<ip_address>/ -w /usr/share/dirb/wordlists/small.txt -x php,html,txt,zip -o directory.txt
```

## For Vhost busting :

```
gobuster vhost -u <domain> -w /usr/share/seclists/Discovery/DNS/subdomains-top1million-20000.txt -v
```
