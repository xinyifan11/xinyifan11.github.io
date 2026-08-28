# xinyifan11.github.io

Personal academic website for Xinyi (Cynthia) Fan, built with [Jekyll](https://jekyllrb.com)
and the [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) remote
theme, styled to match the [AcademicPages](https://github.com/academicpages/academicpages.github.io)
look (system sans-serif, 18px base, sticky author sidebar, underlined section headings).

## What lives where

| File | Purpose |
| --- | --- |
| `index.md` | Home page: About me, News, Publications, Service & Awards, Teaching |
| `_pages/cv.md` | CV page (linked from the top nav) |
| `_config.yml` | Site title, sidebar profile, social links (Email / LinkedIn / GitHub) |
| `_data/navigation.yml` | Top navigation items |
| `assets/css/main.scss` | Theme overrides |
| `assets/images/profile.jpg` | Sidebar profile photo |

## Running locally

Requires Ruby >= 3.0 (macOS system Ruby 2.6 is too old for the current gems).

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.
