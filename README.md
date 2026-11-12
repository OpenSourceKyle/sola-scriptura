# Sola Scriptura

Clone the site and the Bear Blog theme submodule, then build:

```bash
git clone --recurse-submodules git@github.com:OpenSourceKyle/sola-scriptura.git
cd sola-scriptura
hugo
```

If you already cloned without the theme:

```bash
git submodule update --init --recursive
hugo
```

`hugo` writes the site to `public/`. Run `hugo server` to preview it locally.
