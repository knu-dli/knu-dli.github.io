# Data & Language Intelligence Lab — Website

Source for the DLI Lab homepage (Kyungpook National University), built with Jekyll and hosted on GitHub Pages.

## Editing content

Most updates only touch the YAML files in `_data/`:

| What | File |
| --- | --- |
| Members | `_data/members.yml` (photos go in `assets/img/members/`) |
| Publications | `_data/publications.yml` (lab members' names are bolded automatically) |
| Projects | `_data/projects.yml` |
| Navigation menu | `_data/navigation.yml` |

Page text lives in `index.html` (home), `join.md` (lab participation), `gks.md`, and `contact.html`.
Push to `main` and GitHub Pages rebuilds the site in about a minute.

## Local preview (optional)

Requires Ruby 3.x.

```bash
bundle install
bundle exec jekyll serve
```
