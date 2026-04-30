# Iterate Hawaii Proposals

Static client proposal pages, deployed via Cloudflare Pages to `proposals.iteratehi.com`.

## Structure

Each client gets a folder. The folder name becomes the URL path.

```
/                       → root placeholder ("proposals are accessed by direct link")
/kahalaclinic           → Kahala Clinic for Children and Family
```

## Adding a new client

1. Copy an existing client folder (e.g. `kahalaclinic/`) as a starting point.
2. Rename to the new client slug (lowercase, hyphenated).
3. Edit `index.html` for the new client.
4. Commit and push. Cloudflare Pages auto-deploys.

## Hosting

- Hosted on Cloudflare Pages, connected to this GitHub repo.
- Domain: `proposals.iteratehi.com` (subdomain of `iteratehi.com`).
- The apex `iteratehi.com` is reserved for the eventual main marketing site, which lives in a separate project.

## Privacy

Pages are not indexed by search engines (`robots noindex`). URLs use client slugs that are not public. Treat them as shareable-by-link only.
