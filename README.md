# 🌿 Play Therapy Website

A simple [Jekyll](https://jekyllrb.com/) website built to support a new **Play Therapy** business.
This site is designed to be lightweight, easy to maintain, and simple to run locally for editing and updates.

---

## 🚀 Getting Started

### 1. Check Prerequisites

You’ll need **Ruby**, **Bundler**, and a few system libraries installed.

Run these commands to check your setup:

```bash
ruby -v
gem -v
bundle -v
```

If any of these return “command not found,” follow the [Jekyll installation guide](https://jekyllrb.com/docs/installation/) for your operating system.

---

### 2. Install Dependencies

In your cloned project folder:

```bash
cd your-site-folder
bundle install
```

This installs all required Ruby gems for Jekyll and its plugins.

---

### 3. Run the Site Locally

To serve the website on your local machine:

```bash
bundle exec jekyll serve
```

Then open your browser to:

👉 [http://localhost:4000](http://localhost:4000)

You should now see the site running locally.

---

### ⚙️ 4. Optional: Update Dependencies

If the project is old or you want to refresh dependencies:

```bash
bundle update
```

This updates gems to their latest compatible versions.

---

## 🧩 Frontend Development (Optional)

If the site includes custom styles or JavaScript, you can also use Node.js tools.

Install npm dependencies:

```bash
npm install
```

Run the development build:

```bash
npm run dev
```

### Update Styles

To modify site styling:

- Core SCSS variables live in `src/scss/*.scss`
- Add your own overrides in `src/scss/_user_.scss`

Then build styles:

```bash
npm run styles:expanded
npm run styles:minified
```

### Generate Scripts

```bash
npm run scripts:expanded
npm run scripts:minified
```

### Generate Icon Fonts

```bash
npm run icon-font
```

---

## 📝 Content Updates

To update website content:

1. **Locate the page:**
   Pages are stored in the `_pages` directory, organized in a structure matching the website URLs.

2. **Edit the file:**
   Most pages use Markdown (`.md`), though some may be plain HTML.

3. **Preview locally:**
   Run `bundle exec jekyll serve` to preview your changes.

4. **Submit a Pull Request:**
   When ready, open a PR and assign it to one of the maintainers:

   - @davehorsfall
   - @felicityguest
   - @lifan0127

---

## 🐳 Optional: Develop in a Dev Container

This project includes a `.devcontainer/devcontainer.json` file.
If you use [VS Code](https://code.visualstudio.com/) or [GitHub Codespaces](https://github.com/features/codespaces), you can open the project directly inside a **preconfigured Ruby development environment** — no local setup required.

---

## 💡 Tips

- If Jekyll fails to start, delete `Gemfile.lock` and run `bundle install` again.
- Always use `bundle exec` when running Jekyll to ensure version consistency.
- To deploy updates, push changes to the main branch (if connected to GitHub Pages).

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

**Maintained by:** [Dave Horsfall](https://github.com/davehorsfall)
**Project Type:** Jekyll Static Website
**Purpose:** Website for a Play Therapy business

#1087c3 Blue
#e88949 Orange
#73b0e3 Light blue
