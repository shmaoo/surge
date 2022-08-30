# surge
自用surge规则
## surge规则

个人自用---------------->自建以及在github搜集的规则，不适用他人


```html
[Rule]
PROCESS-NAME,v2ray,DIRECT
PROCESS-NAME,xray,DIRECT
PROCESS-NAME,clash,DIRECT
PROCESS-NAME,naive,DIRECT
PROCESS-NAME,trojan,DIRECT
PROCESS-NAME,trojan-go,DIRECT
PROCESS-NAME,ss-local,DIRECT
PROCESS-NAME,privoxy,DIRECT
PROCESS-NAME,leaf,DIRECT
PROCESS-NAME,Thunder,DIRECT
PROCESS-NAME,DownloadService,DIRECT
PROCESS-NAME,qBittorrent,DIRECT
PROCESS-NAME,Transmission,DIRECT
PROCESS-NAME,fdm,DIRECT
PROCESS-NAME,aria2c,DIRECT
PROCESS-NAME,Folx,DIRECT
PROCESS-NAME,NetTransport,DIRECT
PROCESS-NAME,uTorrent,DIRECT
PROCESS-NAME,WebTorrent,DIRECT
DOMAIN-SET,https://raw.githubusercontent.com/Jaffemao/surge/release/private.txt,DIRECT
DOMAIN-SET,https://raw.githubusercontent.com/Jaffemao/surge/release/reject.txt,REJECT
DOMAIN-SET,https://raw.githubusercontent.com/Jaffemao/surge/release/icloud.txt,DIRECT
DOMAIN-SET,https://raw.githubusercontent.com/Jaffemao/surge/release/apple.txt,DIRECT
DOMAIN-SET,https://raw.githubusercontent.com/Jaffemao/surge/release/google.txt,DIRECT
DOMAIN-SET,https://raw.githubusercontent.com/Jaffemao/surge/release/pikpak.txt,PROXY
DOMAIN-SET,https://raw.githubusercontent.com/Jaffemao/surge/release/proxy.txt,PROXY
DOMAIN-SET,https://raw.githubusercontent.com/Jaffemao/surge/release/direct.txt,DIRECT

RULE-SET,https://raw.githubusercontent.com/Jaffemao/surge/release/speedtest.txt,PROXY
RULE-SET,https://raw.githubusercontent.com/Jaffemao/surge/release/telegramcidr.txt,PROXY
RULE-SET,https://raw.githubusercontent.com/Jaffemao/surge/release/cncidr.txt,DIRECT
RULE-SET,https://raw.githubusercontent.com/Jaffemao/surge/release/adv.txt,REJECT
RULE-SET,LAN,DIRECT
FINAL,PROXY,dns-failed
```

