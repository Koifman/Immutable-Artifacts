https://attack.mitre.org/techniques/T1016/002/
https://detect.fyi/detecting-wifi-dumping-via-direct-winapi-calls-and-introduction-to-immutable-artifacts-8ad0661344c1


| Log Source     | Event ID | Description       | References |
|----------------|----------|-------------------|------------|
| Windows Security Logs, Sysmon | 4688, 1     | Netsh.exe usage with “key=clear” |  |
| Sysmon | 7     | wlanapi.dll loaded by suspicious process | [Link1](https://koifsec.medium.com/detecting-wifi-dumping-via-direct-winapi-calls-and-introduction-to-immutable-artifacts-8ad0661344c1)<br>[Link2](https://security.googleblog.com/2024/04/detecting-browser-data-theft-using.html) |
| Crypto-DPAPI | 16385     | SPCryptUnprotect | [Link1](https://koifsec.medium.com/detecting-wifi-dumping-via-direct-winapi-calls-and-introduction-to-immutable-artifacts-8ad0661344c1) |
