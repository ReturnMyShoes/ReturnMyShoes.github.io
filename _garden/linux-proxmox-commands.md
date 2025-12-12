---
layout: single
title: "Linux & PromMox Commands" # <-- NEW TITLE
date: 2025-12-09
collection: garden
tags: [evergreen, meta, philosophy]
---
# Troubleshooting

journalctl, -xe, -u"service", -u "docker" -f        systemD logs
systemctl, status "service", restart "service",     what a service is doing
top, htop, btop
dmesg, --level=err, -w, 
lsblk, -f,
df, -h, 
du,
free -h,                                            total memory, swap
ss, -tulpn, -tunap, 
ps                                                  user processes
nginx -t,                                           config
