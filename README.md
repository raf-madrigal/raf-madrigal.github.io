# raf-madrigal.github.io

Personal portfolio website for Rafael Madrigal — Senior Data Scientist, ML Engineer, and AI Researcher based in Toronto.

## Stack

- **Jekyll** static site generator
- Custom theme with dark/light mode (no external theme dependency)
- Inter font, CSS custom properties, fully responsive
- Deployed via GitHub Actions to GitHub Pages

## Local Development

```bash
# Install dependencies
bundle install

# Serve locally
bundle exec jekyll serve
```

Open [http://localhost:4000](http://localhost:4000)

## Structure

```
_layouts/       Custom layouts (base, home, page, post, project)
_includes/      Header, footer, head partials
_posts/         Blog posts / write-ups
assets/css/     Single SCSS stylesheet with dark/light themes
assets/images/  Profile photo and project images
assets/pdf/     CV and presentation PDFs
index.md        Homepage
works.md        Combined projects + writing page
tech-stack.md   Full tech stack page
```

## License

Content is copyright Rafael Madrigal. Code is available under the [MIT License](LICENSE.txt).
