# rule

Personal rule sets, served via jsDelivr CDN.

## Subscription URLs

### Clash (`clash/` directory, YAML format)

| Rule | URL |
|------|-----|
| Claude | `https://cdn.jsdelivr.net/gh/kpkym/rule@main/clash/Claude.yaml` |

### Surge (`surge/` directory, list format)

| Rule | URL |
|------|-----|
| Claude | `https://cdn.jsdelivr.net/gh/kpkym/rule@main/surge/Claude.list` |

## Force refresh CDN

A GitHub Action automatically purges the cache on push to `main`. You can also purge manually:

- Clash: `https://purge.jsdelivr.net/gh/kpkym/rule@main/clash/Claude.yaml`
- Surge: `https://purge.jsdelivr.net/gh/kpkym/rule@main/surge/Claude.list`

Or with curl:

```bash
curl https://purge.jsdelivr.net/gh/kpkym/rule@main/clash/Claude.yaml
curl https://purge.jsdelivr.net/gh/kpkym/rule@main/surge/Claude.list
```

## Notes

- To pin a version, replace `@main` with a commit SHA or tag (e.g. `@v1.0.0`)
