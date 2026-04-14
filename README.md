# rule

Personal rule sets, served via jsDelivr CDN.

## Subscription URLs

### Clash (`c/` directory, YAML format)

| Rule | URL |
|------|-----|
| Claude | `https://cdn.jsdelivr.net/gh/kpkym/rule@main/c/Claude.yaml` |

### Surge (`s/` directory, list format)

| Rule | URL |
|------|-----|
| Claude | `https://cdn.jsdelivr.net/gh/kpkym/rule@main/s/Claude.list` |

## Force refresh CDN

A GitHub Action automatically purges the cache on push to `main`. You can also purge manually:

- Clash: `https://purge.jsdelivr.net/gh/kpkym/rule@main/c/Claude.yaml`
- Surge: `https://purge.jsdelivr.net/gh/kpkym/rule@main/s/Claude.list`

Or with curl:

```bash
curl https://purge.jsdelivr.net/gh/kpkym/rule@main/c/Claude.yaml
curl https://purge.jsdelivr.net/gh/kpkym/rule@main/s/Claude.list
```

## Notes

- To pin a version, replace `@main` with a commit SHA or tag (e.g. `@v1.0.0`)
