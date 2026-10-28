# shaarifsajid.github.io

Source for my personal portfolio site, served via GitHub Pages.

Plain HTML and CSS. No build step, no framework, no JavaScript, no dependencies.

```
index.html
assets/
  css/style.css
files/
  resume.pdf
  research/        poster PDFs linked from the Research section
```

To update the resume, replace `files/resume.pdf` with a new file of the
same name and push. The "Resume" link on the site always points to that
path, so no other changes are needed.

To preview locally, just open `index.html` in a browser, or serve the
directory with any static file server, e.g.:

```
python3 -m http.server 8000
```
