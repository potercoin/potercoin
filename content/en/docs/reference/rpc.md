---
title: "RPC"
weight: 9
description: >
  Poter's JSON-RPC port is **16800**, default `rpc-secret` is empty.
---

## RPC authorization secret token
This document is referenced from https://aria2.github.io/manual/en/html/aria2c.html#rpc-authorization-secret-token

To use RPC method-level authorization, the user has to specify an RPC secret authorization token using the --rpc-secret option. For each RPC method call, the caller has to include the token prefixed with token:. Even when the --rpc-secret option is not used, if the first parameter in the RPC method is a string and starts with token:, it will removed from the parameter list before the request is being processed.