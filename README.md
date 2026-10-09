# ultra.vaked.dev — what ultra is

> *not a setting. a lap — run end to end, at performance, with love.*

Live URL: **[https://ultra.vaked.dev](https://ultra.vaked.dev)**

---

## ✦ What this is

A showcase, in the constellation's own voice, of what **ultra** means here: not
"auto-assist off, lean, fast" (that's the setting) but the **loop closed** —
`reflect → improve → wire → polish → push → readme`, with nothing left
half-wired and the tree ending pushed and readme'd.

The page is also the receipt: it lists the surfaces shipped in one sitting
(`koan`, `weave`, `disco`, the studies, the engine bridges), the live ternary
pulse, and the one rule — *a plausible branch may be ranked; only a verified
branch may be bound.*

## ✦ Deploy

Static site on **Cloudflare Pages** (project `ultra-vaked-dev`):

```bash
wrangler pages deploy . --project-name ultra-vaked-dev --branch main --commit-dirty=true
```

DNS: proxied `CNAME ultra.vaked.dev → ultra-vaked-dev.pages.dev` in the
`vaked.dev` zone; the Pages custom domain is attached.

## ✦ Constellation standards

- **robots.txt** — anti-AI scraper rules.
- **_headers** — `no-cache` + `X-Robots-Tag: noai, noimageai` + a strict CSP.
- **Lovetta Lane footer** — sister-site backreferences.
- **live ternary signature** — `{−1, 0, +1}` recomputed every 3s (the pulse).

*the loop, closed · 0 + 1 · fine touch from within · vaked.dev*
