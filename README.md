# vittodepe98.github.io

Personal academic homepage of **Vittoria De Pellegrini** — PhD candidate in Earth Science and Engineering at KAUST, DeepWave group.

🔗 **https://vittodepe98.github.io**

## Editing the site

Almost everything you will ever want to change lives in two files:

| File | What it controls |
|---|---|
| `_pages/about.md` | All page content: About Me, News, Publications, Educations, Experience |
| `_config.yml` | Your name, photo, bio, location and every sidebar link |

Other useful paths:

- `images/` — profile photo (`profile.jpg`) and publication teasers
- `_data/navigation.yml` — the top menu (keep entries in sync with the section headings in `about.md`)

Push to `main` and GitHub Pages rebuilds the site automatically.

## Google Scholar citation counter

The citation badge is filled in by a GitHub Action. To enable it, add a repository
secret named `GOOGLE_SCHOLAR_ID` with the value `aUvIDgUAAAAJ`
(Settings → Secrets and variables → Actions → New repository secret).

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

Requires Ruby with development headers. Optional — GitHub Pages builds the site for you.

## Credits

Built on the [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io) Jekyll template
by RayeRen, which is itself based on [minimal-mistakes](https://github.com/mmistakes/minimal-mistakes)
and [academicpages](https://github.com/academicpages/academicpages.github.io). MIT licensed.
