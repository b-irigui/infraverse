# Contributing to Infraverse

Thanks for helping keep Infraverse accurate and useful! By participating you agree to the [Code of Conduct](code-of-conduct.md).

## Ways to help

- **Fix an outdated or wrong cell.** Tools change licenses, rename products and add features all the time. Corrections are the most valuable contribution.
- **Add a tool to an existing table** (for example, a new CI/CD platform).
- **Propose a new category** (for example, secrets management, service mesh, log shipping). Please open an issue first so we can agree on the rows.
- **Add a how-to page** like the ones in [`cicd/`](cicd/).

## Guidelines

1. **Cite a source.** In your PR description, link the official docs, license file or announcement that backs up each change.
2. **Stay neutral in factual rows.** Opinions belong only in rows marked *(opinionated)*, such as "Best use case".
3. **Use the legend.** ✅ yes · ❌ no · ⚠️ partially, with a short `<sub>` note explaining the caveat.
4. **Link every tool to its official page**, not to a blog or reseller.
5. **Images:** add logos under `images/` (or `images/<vendor>/`), keep them small (ideally under 50 KB), and always set an `alt` text. Set only `height="50"` so the aspect ratio is kept.
6. **Keep columns and rows consistent** within a table: every row needs a cell for every tool.
7. **One topic per PR** makes reviewing much faster.

## Updating your PR

If maintainers ask for changes, just push new commits to the same branch — no need to open a new PR. If you're not sure how, [here is a guide](https://github.com/RichardLitt/knowledge/blob/master/github/amending-a-commit-guide.md) on the different ways you can update a PR.

Every PR runs an automatic link check, so please make sure new links resolve.
