---
"@cloudflare/dofs": patch
"@cloudflare/computer": patch
---

`find` now accepts `exclude` e.g. `ws.fs.find("/workspace", "**/*.ts", { exclude: ["node_modules/**"], })`.
