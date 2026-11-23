# What you can do on this site

For the owner. Nothing on this site waits on you: it is live at https://sovereign-website.startups.sovereignweb.site/, built only from public sources, and every page is checked on each push. Everything below is optional, and you can do it yourself, here or on GitHub.

## Change it yourself

1. **Edit a fact.** Open `content/facts.json` on GitHub and change the words. Every fact names its source (an `s` number from the `sources` list); add a source for anything new.
2. **Rebuild.** Run `python3 tools/build.py`. It writes all five designs into `site/`.
3. **Publish.** Commit to `dev`. The pipeline checks the pages, deploys them and tags the version; `/version.json` on the live site shows which commit is live.
4. **Pick the home page.** It opens on The Showroom now. Set `home` in `content/facts.json` to any of: `hand-over` (The Hand-over), `showroom` (The Showroom), `sovereign-website` (Identity: Sovereign Website), `maturity` (Identity: the maturity check), `newsroom` (The Newsroom).
5. **Add a photo or a screenshot.** Put it in `site/img/` and add it to `content/facts.json` with its credit and source.

## Things you could add

- **The first handed-over site.** It is off the showroom for now: your record allows listing it without naming its owner, and its address carries the owner's name. Featuring the owner needs their own word.
- **Any answer in `docs/questions.md`.** Each one, once answered with a source, becomes a fact on the site.
