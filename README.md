# Generative Models (Fall 2025) | Course Website

This repository contains the source code for the official course website for **Generative Models (Fall 2025)** at Sharif University of Technology.

> \[!IMPORTANT\]
> **Students:** You are probably in the wrong place! This repository is just for the source code.
>
> ## [**Click Here for the Live Course Website!**](https://sut-cs-gm.github.io)

## Details

This site is built using [**MkDocs**](https://www.mkdocs.org/) with the [**Material for MkDocs**](https://squidfunk.github.io/mkdocs-material/) theme.

### How to Update Content

You do not need to know HTML or CSS. All course content is written in standard **Markdown** (`.md`) files.

1. **Find the content:** All website pages are located in the `docs/` directory.

   * `docs/index.md`: The homepage.
   * `docs/material/index.md`: The "Course Material" page.
   * `docs/homeworks/index.md`: The "Homeworks" page.
   * ...and so on.

2. **Edit the file:** Make your changes to the relevant `.md` file.

3. **Commit and push:** Commit your changes and push them to the `main` (or `master`) branch.

A GitHub Action is automatically configured. When you push a change, it will automatically build the static site and deploy it to the live URL. You do not need to do anything else.

### Previewing Changes Locally (Optional)

If you want to preview your changes on your local machine before pushing them, you can run the site locally.

1. **Clone the repository:**

   ```
   git clone [https://github.com/sut-cs-gm/sut-cs-gm.github.io.git](https://www.google.com/search?q=https://github.com/sut-cs-gm/sut-cs-gm.github.io.git)
   cd sut-cs-gm.github.io
   ```

2. **Set up a Python virtual environment** (Recommended):

   ```
   python -m venv venv
   source vVenv/bin/activate  \# On Windows, use `venv\Scripts\activate`
   ```

3. **Install the required packages:**
   *Note: You may need to add other plugins from `mkdocs.yml` to this list.*

   ```
   pip install mkdocs-material mkdocs-blog mkdocs-tags
   ```

4. **Run the local server:**

   ```
   mkdocs serve
   ```

5. **Open in browser:**
   Open [**http://127.0.0.1:8000**](https://www.google.com/search?q=http://127.0.0.1:8000) in your browser to see the live preview. The site will automatically refresh as you save changes to the Markdown files.

---

## Credits

* Designed by: [Mohammad Mohammadi](https://github.com/iMohammad97)
* Edited by: [Maryam Rezaee](https://github.com/msmrexe)