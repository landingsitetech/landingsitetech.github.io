---
title: "Install Caddy on macOS"
excerpt_separator: "<!--more-->"
categories:
  - Blog
tags:
  - macOS
  - caddy
---

# Install Caddy on macOS

Oper Terminal

```shell
curl -sS https://webi.sh/caddy | sh
```

If every OK,

```shell
source ~/.config/envman/PATH.env
```

Test
```shell
caddy --help
```


If the download failed, you can download the .tar.gz maunlly

Download [https://github.com/caddyserver/caddy/releases/download/v2.6.2/caddy_2.6.2_mac_amd64.tar.gz]()

then move the file the specific directory

```shell
mv ~/Downloads/caddy_2.6.2_mac_amd64.tar.gz ~/Downloads/webi/caddy/2.6.2/
```

Try again
