# michelabonani.com

Personal academic website, built with [Hugo](https://gohugo.io) and deployed on Netlify.

## Where things live

| What | File |
|---|---|
| Bio text | `content/_index.md` |
| Papers, abstracts, figures, teaching | `data/research.yaml` |
| Name, links, email, CV path | `hugo.toml` |
| Paper PDFs and CV | `static/files/` |
| Figures shown under "Key figures" | `static/figures/` |
| Photo | `static/img/avatar.jpg` |
| Page layout | `layouts/index.html`, `layouts/partials/paper.html` |
| Styling | `assets/style.css` |

## Common edits

- **Update the CV:** replace `static/files/Bonani_CV.pdf` (keep the file name).
- **Add a paper:** copy an entry in `data/research.yaml`. Optional fields: `coauthors`, `journal`, `details`, `status`, `pdf`, `url`, `appendix`, `replication`, `slides`, `abstract`, `figures`.
- **Add figures to a paper:** put a PNG in `static/figures/`, then list it under the paper's `figures:` with a one-sentence `caption`.

## Preview locally

```
hugo server
```

then open http://localhost:1313.
