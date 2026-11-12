# My Stories

A personal website for my story *Adventure of xxx*, its handwritten manuscript
and my illustrations. Built with [Hugo](https://gohugo.io/) and the
[PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme.

## Run it locally

```bash
git clone --recurse-submodules <this-repo-url> stories
cd stories
hugo server -D        # preview at http://localhost:1313
```

If you cloned without `--recurse-submodules`, fetch the theme first:
`git submodule update --init --recursive`.

## Where things are

| Folder | Contents |
|---|---|
| `content/adventure/` | The story, one file per chapter (`ch01.md`, `ch02.md`, …) |
| `assets/manuscript/` | Handwritten page for each chapter, named after it (`ch01.jpg`, …) |
| `content/illustration/` | One folder per illustration (`index.md` + image) |
| `content/about.md` | About page |
| `layouts/`, `assets/css/` | Site templates and styling |

## License

**The stories, manuscript scans and illustrations** in this repository
(`content/` and `assets/manuscript/`) are © 2026 Your Name and licensed under
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International
(CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/).
See [`LICENSE`](LICENSE) for the full legal text.

In short, you may share and adapt this work, as long as you:

- **give credit** to the author and link to the licence,
- **do not use it for commercial purposes**, and
- **share any adaptations under the same licence.**

For commercial use, please contact the author.

**Third-party parts keep their own licences:**

- PaperMod theme (`themes/PaperMod/`): MIT, see its own `LICENSE`.
- Courier Prime font (`static/fonts/courier-prime/`): SIL Open Font License 1.1, see `OFL.txt`.
- Special Elite font (`static/fonts/special-elite/`): Apache License 2.0, see `LICENSE.txt`.
