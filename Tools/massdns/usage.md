
```
massdns -r /root/Tools/massdns/lists/resolvers.txt -t A -o S /root/Desktop/demo.txt -w /root/Downloads/subdomains.txt
```

#### To look the result good
```
sed 's/A.*//' subdomains. txt | sed 's/CN.*//' | sed 's/\N..$//' > live_subdomains.txt
```
