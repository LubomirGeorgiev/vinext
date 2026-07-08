---
"@vinext/cloudflare": patch
"vinext": patch
---

- fix(build): honor inline next config for static export (#2543)
- perf(build): use native typeof window folding (#2564)
- fix(app-router): handle redirects in route-miss fallbacks (#2553)
- perf(pages): reuse dev stylesheet dependency analysis (#2550)
- fix(app-router): preserve semicolons in redirect digests (#2487)
- fix: pass server externals to Nitro traceDeps (#2521)
- fix(pages): preserve fast refresh state (#2544)
- fix(routing): discover dot-directory routes (#2531)
