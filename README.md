# Notice

This repository is a proof of concept for the standalone HTML content for PSG developers. It utilizes the [Hyde](https://github.com/poole/hyde) theme, which leverages a two-column display that pairs a prominent sidebar with uncomplicated content.

# Stage Your Content

Before making your updates live on the GitHub Pages site, you can view how your content will render while you're working by cloning this repository and running a Jekyll server on your local machine. To stage your content on a Jekyll server, follow the steps below.

### 1. Install Jekyll and other dependencies

* [Jekyll on macOS](https://jekyllrb.com/docs/installation/macos/)
* [Jekyll on Windows](https://jekyllrb.com/docs/installation/windows/)

### 2. Clone this repository

```
git clone https://github.com/michelle-hu-2021/mockup.git
```

### 3. Run site locally

```
cd mockup
bundle exec jekyll serve
```

### 4. Open site

Open <http://localhost:4000> in your browser, and voilà.

If you're making changes while the server is running, your terminal should indicate that you've updated the content and you can refresh the page to see your updates immediately.

### 5. Kill server

Kill the Jekyll server by typing `Ctrl + C` in your terminal. When you're ready to view your changes on the Jekyll server again, just type `bundle exec jekyll serve` in your terminal.

# Sidebar Menu

Create a list of navigation links in the sidebar by assigning each Jekyll page the correct layout in the page's [front-matter](http://jekyllrb.com/docs/frontmatter/).

```
---
layout: page
title: About
---
```

**Why require a specific layout?** Jekyll will return *all* pages with an alphabetical sort order. To ensure the first link is *Home*, we exclude the `index.md` page from this list by specifying the `page` layout.

# Add Content

To add additional content to this repository, create new Markdown files with the Jekyll front matter as shown above. Beneath the Jekyll front matter, you can insert your HTML content.

# License

Open sourced under the [MIT license](LICENSE.md).
