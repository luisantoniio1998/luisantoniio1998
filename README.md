```yaml
title: Luís Barros
id: 6c756973-6261-7272-6f73-000000000001
status: active
description: Detects the person quietly turning telemetry into signal.

author: Luís Barros
date: 2026/09/15

logsource:
  category: cybersecurity
  product:
    - splunk
    - sentinel
    - elastic

detection:
  selection:
    activity:
      - building detections
      - hunting anomalies
      - automating the boring parts
  condition: selection

falsepositives:
  - probably sleeping

level: curious
```

[![HTB Badge](https://www.htbbadge.tech/api/badge?user=1541841)](https://app.hackthebox.com/public/users/1541841)

`whoami` → [portfolio](https://luisantoniio1998.github.io/) · [linkedin](https://www.linkedin.com/in/-luis-barros-/) · [tryhackme](https://tryhackme.com/p/lb.)
