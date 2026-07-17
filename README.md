# Lind project website

This repository hosts the organization-level landing page for the
[Lind Project](https://github.com/Lind-Project), served at
[lind-project.github.io](https://lind-project.github.io).

The page introduces the Lind framework — safely executing untrusted POSIX
applications as mutually isolated compartments within a single unprivileged
host process — and links out to the realized backend and its documentation:

- [lind-wasm documentation](https://lind-project.github.io/lind-wasm/)
  (assets in [lind-wasm/docs](https://github.com/Lind-Project/lind-wasm/tree/main/docs))
- [lind-wasm](https://github.com/Lind-Project/lind-wasm)
- [lind-wasm-example-grates](https://github.com/Lind-Project/lind-wasm-example-grates)
- [lind-wasm-apps](https://github.com/Lind-Project/lind-wasm-apps)

The site is a single static page ([index.html](index.html)) plus logo assets
in [assets/](assets/), with no build step or external dependencies — edit and
push to `main` to deploy via GitHub Pages. `lindv1.png` is the original logo
source; `assets/lind-logo.png` is the transparent-background version used on
the page.
