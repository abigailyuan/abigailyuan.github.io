# Meng Yuan’s Blog

This repository powers my personal blog, built with [Jekyll](https://jekyllrb.com/) and GitHub Pages. Here I share deep-dives into Information Retrieval (IR) evaluation, embedding interpretability, search-as-learning explorations, and my experiments with retrieval-augmented generation (RAG) and LLM reasoning.

---

## 🔗 Live Site

[https://mengyuan.github.io](https://mengyuan.github.io)

---

## 📥 Clone & Setup Locally

1. **Clone the repository**

   ```bash
   git clone git@github.com:mengyuan/mengyuan.github.io.git
   cd mengyuan.github.io
   ```

2. **(Optional) Preview locally**

   ```bash
   # Install dependencies
   gem install bundler
   bundle config path vendor/bundle
   bundle install

   # Serve with Jekyll
   bundle exec jekyll serve --livereload
   ```

   Then open [http://127.0.0.1:4000](http://127.0.0.1:4000) in your browser to preview changes in real time.

---

## 📝 Writing a New Post

1. **Create a new Markdown file** in the `_posts/` folder. Use the filename format:

   ```text
   _posts/YYYY-MM-DD-your-post-title.md
   ```
2. **Add front-matter** at the top of the file:

   ```markdown
   ---
   layout: post
   title:  "Your Post Title"
   date:   YYYY-MM-DD HH:MM:SS +1000
   categories: category1 category2
   ---
   ```
3. **Write your content** in Markdown below the front-matter.
4. **Save** the file.

---

## 🚀 Publish Changes

1. Stage and commit your changes:

   ```bash
   git add .
   git commit -m "Add new post: Your Post Title"
   ```
2. Push to GitHub:

   ```bash
   git push origin main
   ```

GitHub Pages will automatically rebuild the site. Your new post will appear at `https://mengyuan.github.io` shortly.

---

## ⚙️ Configuration

All site settings live in `_config.yml`:

```yaml
title: "Meng Yuan’s Blog"
description: "Exploring IR evaluation, embedding interpretability, and LLM-powered RAG."
baseurl: ""
url: "https://mengyuan.github.io"
remote_theme: pages-themes/minimal
plugins:
  - jekyll-feed
  - jekyll-remote-theme
```

Feel free to adjust theme, plugins, or add new pages as needed.

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo.
2. Create a branch: `git checkout -b feature/your-topic`.
3. Commit your changes: `git commit -m "Describe your changes"`.
4. Push to your fork and open a Pull Request.

---

## 📫 Contact

* **Email:** [meng.yuan@unimelb.edu.au](mailto:meng.yuan@unimelb.edu.au)
* **LinkedIn:** [https://www.linkedin.com/in/mengyuan](https://www.linkedin.com/in/abbymengyuan)
* **GitHub:** [https://github.com/mengyuan](https://github.com/abigailyuan)
