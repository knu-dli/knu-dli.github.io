# Data & Language Intelligence Lab — Website

Source for the DLI Lab homepage (Kyungpook National University), built with Jekyll and hosted on GitHub Pages.

## Editing content

Most updates only touch the YAML files in `_data/`:

| What | File |
| --- | --- |
| Members | `_data/members.yml` (photos go in `assets/img/members/`) |
| Publications | `_data/publications.yml` (lab members' names are bolded automatically) |
| Projects | `_data/projects.yml` |
| News | `_data/news.yml` (newest first; the home page shows the latest 5) |
| News posts | `_news/<name>.md`, linked from a news item with `post: <name>`; attachments (e.g. certificates) go in `assets/news/` |
| Navigation menu | `_data/navigation.yml` |

Page text lives in `index.html` (home), `join.md` (how to apply, including GKS applicants), `lab-guide.md` (how the lab works and what we expect), and `contact.html`.
Push to `main` and GitHub Pages rebuilds the site in about a minute.

## Local preview (optional)

Requires Ruby 3.x.

```bash
bundle install
bundle exec jekyll serve
```
