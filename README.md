# Diwakar Yadav Portfolio

Minimal Jekyll portfolio site intended for GitHub Pages at `https://dyadavrke.github.io/diwakar.yadav.github.io/`.

## Structure

- `index.html` - home page
- `about/` - background page
- `projects/` - project placeholders
- `blog/` - blog index
- `_posts/` - blog posts
- `reads/` - recent reads page
- `_data/reads.yml` - editable books and articles list
- `contact/` - contact links

The older Streamlit app is preserved in `webpage.py` as legacy code, but GitHub Pages uses the Jekyll/static site files.

## Local Preview

Use Ruby 3.x for the current GitHub Pages gem stack.

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://127.0.0.1:4000`.
