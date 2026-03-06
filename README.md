# Jun's Blog

A personal blog built with [Hugo](https://gohugo.io) using the [Cactus](https://github.com/monkeyWzr/hugo-theme-cactus) theme. Deployed locally.

## Stack

- **Static site generator:** Hugo v0.131.0
- **Theme:** hugo-theme-cactus (git submodule)
- **Color theme:** classic

## Project Structure

```
blog/
├── content/
│   ├── posts/          # Blog posts (Markdown)
│   └── about.md        # About page
├── layouts/
│   ├── index.html              # Homepage override (removes dynamic tag font sizing)
│   ├── partials/
│   │   ├── head.html           # Head override (fixes Hugo v0.131 compatibility, relative CSS URLs)
│   │   └── footer.html         # Footer override (copyright only, no nav links)
│   ├── _default/
│   │   └── terms.html          # Tags page override (removes dynamic font sizing)
│   └── posts/
│       └── single.html         # Post page override (uses standard header instead of sidebar nav)
├── static/
│   └── css/
│       └── custom.css          # Removes # prefix on h2 headings
├── themes/
│   └── cactus/                 # Theme (git submodule)
├── public/                     # Generated static site (deploy this)
└── hugo.toml                   # Site configuration
```

## Configuration

Key settings in `hugo.toml`:

- `baseURL` — set to the deployed domain
- `colortheme` — `dark`, `light`, `white`, or `classic`
- `postsOnHomePage` — number of posts shown on homepage
- `[[params.social]]` — social links shown in "Find me on" section

## Usage

### Add a new post

```bash
hugo new content posts/my-post-title.md
```

Set `draft = false` in the front matter when ready to publish.

### Add tags to a post

```toml
tags = ["linux", "programming"]
```

### Run dev server

```bash
hugo server --buildDrafts --port 1313
```

### Build for deployment

```bash
hugo --minify
```

Then deploy the `public/` directory to your web server.

## Theme Customizations

- **Dynamic tag font sizes removed** — the Cactus theme scales tag fonts by post count, which looks broken with few posts. This is disabled on both the homepage and tags page.
- **Consistent header on post pages** — the theme uses a sidebar nav on post pages; overridden to use the standard top header.
- **No `#` prefix on headings** — the theme adds a `#` before all `h2` headings via CSS; removed via `custom.css`.
- **Relative CSS URLs** — stylesheets use relative paths so the site works regardless of domain or protocol.
- **Footer links removed** — footer shows copyright only.
- **Hugo v0.131 compatibility** — removed reference to deprecated `_internal/google_analytics_async.html`.
