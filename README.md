# worktrunk-assets

Large assets (demo GIFs, videos) for [worktrunk](https://github.com/max-sixty/worktrunk) documentation.

These files are hosted separately to avoid bloating the main repository.

## Usage

Reference assets via raw GitHub URLs:

```markdown
![Demo](https://raw.githubusercontent.com/max-sixty/worktrunk-assets/main/demos/wt-demo.gif)
```

Or via jsDelivr CDN (faster, cached):

```markdown
![Demo](https://cdn.jsdelivr.net/gh/max-sixty/worktrunk-assets@main/demos/wt-demo.gif)
```

## Publishing

From the main worktrunk repo, run:

```bash
./scripts/publish-assets
```
