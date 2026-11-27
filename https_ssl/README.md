# HTTPS SSL

| File | Purpose |
|---|---|
| `0-world_wide_web` | Shows the record type and destination of www, lb-01, web-01 and web-02 for a domain, using `dig` and `awk` |

## Usage
```bash
./0-world_wide_web example.tech          # all four subdomains
./0-world_wide_web example.tech web-02   # one subdomain
```
