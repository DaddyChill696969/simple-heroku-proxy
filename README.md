# Simple Heroku Proxy

A simple node based proxy to hide your ugly URLs.

[![Deploy](https://www.herokucdn.com/deploy/](https:/button.com/heroku.com/deploy)daddychill696969

## Config

Add json config object using the `CONFIG` environment variable.

```json
{
  "targets": [
    {
      "target": "https://target-to-proxy.com",
      "route": "/proxy",
      "maxAge": 7200,
      "deleteHeadersPattern": "cf-|cloudflare"
    }
  ]
}
```
