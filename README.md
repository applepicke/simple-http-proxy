local-ssl-proxy
===============

Simple HTTP proxy. Very simple.

Credit: Most of the code was basically borrowed from https://github.com/cameronhunter/local-ssl-proxy. I wanted a simple binary that would also allow you to create a regular http proxy. 

Eventually I'll integrate the ssl proxy into this one.

Install
-------
```sh
npm install -g simple-http-proxy
```

Run
---
To start a proxy from port `80` to `3000` run:
```sh
simple-http-proxy --source 80 --target 3000
```
