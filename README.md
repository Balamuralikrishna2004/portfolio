# Balamurali Krishna — Cybersecurity Portfolio

A responsive, cinematic portfolio for Balamurali Krishna M, showcasing cybersecurity, network engineering, and GRC experience. The site is built with plain HTML, CSS, and JavaScript and includes scroll-controlled image sequences, pointer-tracked visuals, and animated effects.

## Live site

After GitHub Pages is enabled, the portfolio will be available at:

<https://balamuralikrishna2004.github.io/Balamuralikrishna2004/>

## Run locally

Serve the project root with any static file server. For example, with Python:

```powershell
python -m http.server 8000
```

Then open <http://localhost:8000>.

The page loads its image sequences from `frames/`, so keep that folder alongside `index.html`.

## Project structure

```text
.
├── frames/
│   ├── eyes/       # Pointer-tracked eye sequence
│   ├── main/       # Scroll-controlled main sequence
│   └── storm.jpg
├── index.html
├── main.js
└── style.css
```

## Deployment

The [Pages workflow](.github/workflows/pages.yml) publishes the static site whenever a commit is pushed to `main`, and can also be started manually from the **Actions** tab.

To enable deployment, open the repository's **Settings → Pages** and set **Build and deployment → Source** to **GitHub Actions**. The first deployment will run after the workflow is pushed to the default branch.

## License

The project is licensed under the [MIT License](LICENSE).
