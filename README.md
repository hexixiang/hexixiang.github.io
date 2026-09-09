# hexixiang.github.io

Personal academic homepage of **Xixiang He** — <https://hexixiang.github.io>

Built with [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io) (MIT), a Jekyll
theme based on [academicpages](https://github.com/academicpages/academicpages.github.io).

## Editing

All page content lives in a single file: [`_pages/about.md`](_pages/about.md).
Site-wide settings (name, avatar, email, social links) are in [`_config.yml`](_config.yml);
the top navigation is in [`_data/navigation.yml`](_data/navigation.yml).

Optional sections (Honors and Awards, Invited Talks, Academic Services) are already written
and styled at the bottom of `about.md` — uncomment the block and fill them in.

## Google Scholar citation badge

The workflow in `.github/workflows/google_scholar_crawler.yaml` refreshes citation counts daily.
To enable it, add a repository secret named `GOOGLE_SCHOLAR_ID` with the value `724HNF4AAAAJ`
(Settings → Secrets and variables → Actions → New repository secret).

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.
