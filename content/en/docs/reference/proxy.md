---
title: "Proxy Guide"
weight: 8
description: 
---

## Proxy Setting Guide

This document is referenced from https://aria2.github.io/manual/en/html/aria2c.html#cmdoption-all-proxy

The proxy protocol only supports http or https, not support socks5, please convert to http protocol first.

Support simple user password authentication.

Please use a proxy client to convert the remote proxy server(SS, V2Ray) to a local http proxy.

Proxy value format: [http://][USER:PASSWORD@]HOST[:PORT]

[] Optional Parameter

🌰For Example:

http://127.0.0.1:6666

https://192.168.50.110:8443

http://user123:iampassword@127.0.0.1:7788